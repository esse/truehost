# Truehost

This is a straightforward script, created to easily access the IP address of associated host using the console.

Why not merely use regular host command? It doesn't respect system DNS resolve policy and goes straight to the DNS - which makes using it together with dnsmasq or DNS split horizon by VPN pointless.

## Install

Just copy file to `/usr/bin`. Or anywhere you want to.

## Usage

```
$ truehost google.com
216.58.209.14
```
