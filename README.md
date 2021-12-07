ChattyRaspi script
======

ChattyRaspi script allows you to run arbitrary code on your machine by using Alexa interface.

Installation
------------

```sh
pip install chattyraspi-script
```

Basic examples
--------------

```bash

$> chattyraspi-script \
       --config-file devices_configuration.yaml \
       --on-cmd "systemctl start openvpn.service" \
       --off-cmd "systemctl stop openvpn.service" \
       --is-on-cmd "systemctl status openvpn.service"

```
