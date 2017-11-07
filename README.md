# Radicale IMAP

IMAP authentication plugin for [Radicale](http://radicale.org/).

## INFORMATION

This is only a copy for trial and error to understand, how this works.
Problem is, running radicale with radicale_imap in a docker-container and dovecot bare-metal, the authentication hangs, and I don't know why.

## Installation

```shell
$ python3 -m pip install --upgrade git+https://github.com/Unrud/RadicaleIMAP
```

## Configuration

```ini
[auth]
type = radicale_imap

# IMAP server host name
# Syntax: address:port
# For example: imap.server.tld
#imap_host =

# Use StartTLS to secure the connection
# Requires Python >= 3.4
#imap_secure = True
```

## License

[GPL-3.0](https://github.com/Unrud/RadicaleIMAP/blob/master/COPYING)
