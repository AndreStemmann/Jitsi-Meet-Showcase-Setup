# Sample Jitsi-Meet Config

The following Jitsi-Meet sample-setup is capable of managing around 35 Users per
Conference on old hardware, depending on your bandwidth.
Furthermore it's running on a different port 8443, has an authentification and a
working Etherpad.

## Installation
Adapt the configs to your needs, it's just a showcase for common questions from
the Jitsi Userspace of how to on another port, howto auth and howto etherpad
and howto on old hardware.

Sample Jitsi-Meet-config
├── jitsi
│   ├── etc
│   │   ├── jitsi
│   │   │   ├── jicofo
│   │   │   │   ├── config_org
│   │   │   │   ├── logging.properties_org
│   │   │   │   └── sip-communicator.properties_org
│   │   │   ├── meet
│   │   │   │   └── your.fancy.domain.com-config.js_org
│   │   │   └── videobridge
│   │   │       ├── 20-jvb-udp-buffers.conf_org
│   │   │       ├── config_org
│   │   │       ├── logging.properties_org
│   │   │       └── sip-communicator.properties_org
│   │   └── sysctl.d
│   │       └── 99-custom.conf_org
│   └── usr
│       └── share
│           └── jitsi-meet
│               ├── interface_config.js_org
│               └── title.html_org
├── nginx
│   └── etc
│       └── nginx
│           └── sites-available
│               └── your.fancy.domain.com.conf_org
├── prosody
│   └── etc
│       └── prosody
│           └── conf.avail
│               └── your.fancy.domain.com.cfg.lua_org
└── README.md
