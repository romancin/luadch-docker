# Luadch

This is a completely funcional Docker image with Luadch application.

![docker pulls](https://img.shields.io/docker/pulls/romancin/luadch.svg) ![docker stars](https://img.shields.io/docker/stars/romancin/luadch.svg) [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=X2CT2SWQCP74U)

Latest versions:

![Docker Image Version (latest semver)](https://img.shields.io/docker/v/romancin/luadch/v2) ![docker size](https://img.shields.io/docker/v/romancin/luadch/v2) 

[![](https://images.microbadger.com/badges/version/romancin/luadch.svg)](https://microbadger.com/images/romancin/luadch "Docker image version")
[![](https://images.microbadger.com/badges/image/romancin/luadch.svg)](https://microbadger.com/images/romancin/luadch "Docker image size")
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=X2CT2SWQCP74U)

You can invite me a beer if you want ;) 

Based on Alpine Linux, which provides a very small size.

Tested and working on Synology and QNAP, but should work on any x86_64 devices.

Sample run command:

```bash
docker run -d --name=luadch \
-e PGID=0 -e PUID=0 -e TZ=Europe/Madrid \
-p 5000:5000 \
-p 5001:5001 \
-v "/share/Container/luadch:/config"
romancin/luadch:latest
```

or use 

docker-compose up -d 

after you edited the file previously to meet your needs.
