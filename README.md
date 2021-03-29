# QuantLib-Demo

A sandpit to get the Quantlib library built (from source) on Debian Linux.

One of the tasks details the installation of the library using apt, but is commented out.

# Setup Instructions

1. Prepare a vanilla Debian Server with VirtualBox ([help](https://linuxhint.com/install_debian10_virtualbox/)).

2. Install ansible ([help](https://linuxhint.com/install_ansible_debian10/)).

3. Install Git ([help](https://linuxhint.com/install_git_debian_10/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/QuantLib-Demo.git && cd QuantLib-Demo && ./build.sh
# Takes a while to build.
```
