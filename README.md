# VEROT APT Repository

Official APT repository for the VEROT programming language.

## Install

```bash
echo "deb [trusted=yes] https://verotcodspro.github.io/verot-apt stable main" | sudo tee /etc/apt/sources.list.d/verot.list

sudo apt update

sudo apt install verot
