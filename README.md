# ports
Using the Ports Collection inside Jail

```sh
pkg install -y git
git clone https://github.com/freebsd/freebsd-ports.git /usr/ports

# Latest branch:
git -C /usr/ports pull 

# As needed, switch /usr/ports to a different quarterly branch:
git -C /usr/ports switch 2023Q1