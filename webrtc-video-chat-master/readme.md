# WebRTC Video Chat


To start the signaling server and client server, run `npm start`. You can open the page at `http://localhost:5500/`.

For the turn-server,

```bash
cd ./turn-server
./build.sh
./build/turn-server --public-ip=<your_public_ip>
```

When running locally, you can test by opening the page in different browser tabs. You can also test connecting from different devices on the same local network if you're using https.

command args:

- `--ssl-cert-path` path to ssl cert (not required when running locally)
- `--ssl-key-path` path to ssl key (not required when running locally)
- run node commands with `--prod` to use proper port numbers
- run turn server with `--public-ip <your_public_ip>` (set to your local ip address when running locally)

