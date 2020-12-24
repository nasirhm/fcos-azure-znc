# Ignition config for ZNC IRC Bouncer

Ignition configuration to run a Podman container for ZNC IRC Bouncer as a service.

ZNC's default administrator account details are below; be sure to immediately after installation and change these credentials!:

```
core
C0reOsL!fe
```

It'll automatically try to join the `#fedora-coreos` channel on Freenode.

As the nick is unregistered, when connected with a client it'll join `#fedora-unregistered` channel on `chat.freenode.net`.

You can connect to the bouncer with an IRC client with \<IP_Address\>:12345
