WebSockets Support (from 1.5-dev)
=================================


In uWSGI 1.5 a high performance websockets (rfc 6455) implementation has been added.

Albeit lot of different solutions exist for the problem, most of them rely on higher-level languages implementation, that rarely
are good enough for topics like gaming or streaming.

The uWSGI websockets implementation is compiled in by default and can be combined with the Channels subsystem (another new feature of the 1.5 tree)


Handshaking
***********