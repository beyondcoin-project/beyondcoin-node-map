![image](https://beyondcoin.io/beyondcoin-200x200.png)


# Beyondcoin node map

Visualizes Beyondcoin nodes on the map.

## What you need

Beyondcoind

You need a running beyondcoind on the same system you want to run beyondcoin-node-map on Port 3332 

## Clone the repo:

```
git clone https://github.com/beyondcoin-project/beyondcoin-node-map.git
```

## Get Free GEO IP (this populates IP data)

* install and run freegeoip   *Source https://github.com/fiorix/freegeoip
```
cd ~ wget https://github.com/fiorix/freegeoip/releases/download/v3.2/freegeoip-3.2-linux-amd64.tar.gz
```
```
tar xvfz freegeoip-3.2-linux-amd64.tar.gz
```
```
cd freegeoip-3.2-linux-amd64
```
```
chmod +x freegeoip
```
```
./freegeoip --quota-max 0
```
## Get Node
```
npm i
```
## To Run
```
sudo node app.js
```

## Open http://your-website.com. (default port is 80)

It's caching Beyondcoin Node IP's every 24 hrs into `.cache` folder.


![Map](https://github.com/beyondcoin-project/beyondcoin-node-map/blob/master/images/Beyondcoin-map.png?raw=true)
