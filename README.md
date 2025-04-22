# drif-protocol

Simple Self‑hosted Solo Bitcoin Mining with sovereign CKPool + Bitcoin Core.

## Guides

- **PC/macOS/Linux**: [PDF Guide](./docs/drif_protocol_pc_guide.pdf)  
- **Umbrel Home**: [PDF Guide](./docs/drif_protocol_umbrel_guide.pdf)  

## Quickstart

1. Clone this repo  
2. Copy `examples/ckpool.conf.sample` → `conf/ckpool.conf` and edit with your RPC creds & BTC address  
3. Copy `examples/bitcoin.conf.sample` → `~/.bitcoin/bitcoin.conf` and edit for RPC & ZMQ  
4. Launch Docker CKPool and point your miner at `stratum+tcp://<YOUR_HOST_IP>:3333`  

## Examples

- `examples/ckpool.conf.sample`  
- `examples/bitcoin.conf.sample`  

## License

This project is released under the MIT License. See [LICENSE](./LICENSE) for details.
