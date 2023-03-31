# konga-adhoc

`konga-adhoc` creates a temporary namespace (konga-adhoc) and a temporary konga deployment
in the currently selected kubernetes context and exposes a kong instance through a web interface
on http://127.0.0.1:1337

## Usage

Use konga-adhoc like this:

```
Usage:
  konga-adhoc <kong-namespace> [service] [port]

  service  - the name of the kong service to connect to (default: kong)
  port     - the port of the kong service (default: 8001)

```
