# Secure Cash (SCSX) - Blockchain Explorer
Block explorer for Secure Cash CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon egamecashd. It should be accessible from the Internet. Run egamecashd with open port as follows:
```bash
./scashcoind --enable-cors=* --enable_blockexplorer --rpc-bind-ip=0.0.0.0
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
