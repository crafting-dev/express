# Access Local Network

For security reasons, _Crafting Express_ by default blocks accessing local network from the system.
If specific remote services should be accessed, the IP address or CIDRs must be explicitly allowed during installation.

## Allow IPs and CIDRs

Add `--allow-subnets=IP/32,CIDR...` to `cs express start`.
If _Crafting Express_ is already running, also add `--restart`.

## About localhost

It's not possible for Crafting to access services listening on `localhost`.
Particularly on MacOS, `host.docker.internal` can be used to access services listening on `localhost`,
and `host.docker.internal` is automatically configured as accessible, no need to use `--allow-subnets`.

On other OS, find a reachable IP, e.g. the IP of `eth0`, or `docker0` bridge on Linux,
and add that with `--allow-subnets`.
Make sure the service is listening on these IPs, not just `127.0.0.1`, and they can be accessed using the IPs.

## DNS Extender

_Crafting_ system has a [DNS Extension](https://docs.sandboxes.cloud/features/sandbox-networking.html#dns-extenders) mechanism
inside the workspaces.
It can be used to provide a better experience rather than accessing external IPs directly.
