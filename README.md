# v2ray tcp+tls+web (beta)
automated script for v2Ray (TCP+TLS+Web)

## Usage
```
curl -ssL https://raw.githubusercontent.com/phlinhng/v2ray-tcp-tls-web/beta/install.sh | bash
```
The above command will download the script, save it to `/usr/local/bin/v2script`, make it excutable and start it. To run the script again once installed, just use the following command:
```
v2script
```

## TODO
+ [x] Show installation(is installed/not installed) status on script startup
+ [x] Show current subscriton link if existed
+ [ ] Integrate [tindy2013/subconverter](https://github.com/tindy2013/subconverter)
+ [ ] Integrate [9seconds/mtg](https://github.com/9seconds/mtg)
+ [x] Switch to docker ~~nginx~~ caddy
+ [ ] Add CentOS Support
+ [x] use random webpage template