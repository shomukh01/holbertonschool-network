# Networking basics #1

Solutions for the home IP and local network utility exercises.

- `0-change_your_home_IP`: configure `localhost` as `127.0.0.2` and `facebook.com` as `8.8.8.8` in `/etc/hosts` (run with `sudo`).
- `1-show_attached_IPs`: list active IPv4 addresses assigned to up interfaces.
- `2-port_listening_on_localhost`: listen for a local TCP connection on port 98 and print received input.

Scripts target Ubuntu 22.04; Task 1 requires `iproute2` and Task 2 requires netcat-openbsd. The hosts script edits `/etc/hosts` and should only be run when intended.
