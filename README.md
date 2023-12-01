# Personal Portfolio

## Development guide
This site is built using Eleventy as a static site & hosted on Netify, for free! :).  
Eleventy requires Node (Debian setup):  
https://github.com/nodesource/distributions  
```
sudo apt-get update
sudo apt-get install -y ca-certificates curl gnupg
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
NODE_MAJOR=20
echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_$NODE_MAJOR.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list
sudo apt-get update
sudo apt-get install nodejs -y
```

Eleventy setup:
```
npm install
npx @11ty/eleventy
npx @11ty/eleventy --serve
```

## Background info
I previously used Wordpress hosted on Bluehost (for 150€ a year) and sadly that ended up with my website hacked and I had to take it down. 
I never really liked Wordpress as in order to achieve my vision had to use lots of plugins, some of which have only trial versions (such as Elementor) and the building experience felt a bit limited without hacky workarounds (e.g. inner section inside inner section -_- etc.).
My site is only a portfolio as well, there is no backend whatsoever, so Wordpress is a bit overkill for this purpose. Although using a static page also restrics my ability to add a shop to my site in the future, or anything else requiring backend.
