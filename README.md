Procto
======

A script to set up a reverse proxy VM with

  * Let's Encrypt certificate
  * Nginx to proxy remote HTTPS to remote HTTP
  * SSH to proxy remote HTTP to local HTTP


Usage
-----

  * Clone it, copy `config.example` to `config` and fill it
  * Use `provision` command to provision your remote VM
  * Use `start` command to proxy remote HTTPS to local HTTP
  * Use `stop` command to stop the proxy
