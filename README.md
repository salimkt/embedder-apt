# BlueMesh apt repository

```bash
echo 'deb [trusted=yes] https://raw.githubusercontent.com/salimkt/embedder-apt/main ./' | sudo tee /etc/apt/sources.list.d/bluemesh.list
sudo apt update
sudo apt install bluemesh-embedder
```

Flat, unsigned repository (`trusted=yes`) — see scripts/publish_apt.sh for why.
Older versions are retained so a pinned install keeps working.
