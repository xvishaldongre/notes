# Git and Github CLI Setup on Linux Mint 20.3 "Una" (via Ubuntu 20.04 LTS)

# Config Git
```
git config --global user.name "xvishaldongre"
git config --global user.email "xvishaldongre@gmail.com"
```

## Installing Github Cli 

## One liner (Binary)
```
curl -s https://api.github.com/repos/cli/cli/releases/latest \
| grep -E "*linux_amd64.deb" \
| cut -d : -f 2,3 \
| tr -d \" \
| wget -qi - \
sudo apt install -y ./gh*
```

## Manuall (Binary)
1. Open `https://github.com/cli/cli/releases/latest`
2. Download `gh_x.xx.x_linux_amd64.deb`
3. Install using `sudo apt install -y ~/Downloads/gh*`

