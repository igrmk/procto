Procto
======

A script to set up a reverse proxy VM with

  * Let's Encrypt certificate
  * Nginx to proxy remote HTTPS to remote HTTP
  * SSH to proxy remote HTTP to local HTTP


Usage
-----

  * Clone it, copy `example.conf` to `~/.procto/<config name>.conf` and fill it
  * Use `provision <config name>` command to provision your remote VM
  * Use `start <config name>` command to proxy remote HTTPS to local HTTP
  * Use `stop <config name>` command to stop the proxy
