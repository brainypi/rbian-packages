A PPA repository for Rbian Custom packages:

# Usage

```bash
curl -SsL https://brainypi.github.io/rbian-packages/bullseye/KEY.gpg | sudo apt-key add -
sudo curl -SsL -o /etc/apt/sources.list.d/rbian-packages.list https://brainypi.github.io/rbian-packages/bullseye/rbian-packages.list
sudo apt update
```
