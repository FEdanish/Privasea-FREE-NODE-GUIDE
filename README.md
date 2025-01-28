<h1>The easiest guide to run a Privanetix Node</h1>

<h>💎Youtube video tutorial: https://youtu.be/nJ3fyyUwd3E?si=d26SiArlBF1l3siW</h>

🫰💸💴🤑💲💰

<h>💎You can run the node with multiple tricks:</h>

1> By Using WSL on PC [FREE Steps]

2> By using free terminals on Mobile [FREE]

3> By using VPS 24X7 [ Investment ]

<h1>Install Docker</h1>

```console
sudo apt update -y && sudo apt upgrade -y

sudo apt-get update
sudo apt-get install ca-certificates curl gnupg
sudo install -m 0755 -d /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
sudo chmod a+r /etc/apt/keyrings/docker.gpg

echo \
  "deb [arch="$(dpkg --print-architecture)" signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  "$(. /etc/os-release && echo "$VERSION_CODENAME")" stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt update -y && sudo apt upgrade -y

sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

# Docker version check
docker --version
```
