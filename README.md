```sh
sudo npm install pm2@latest
git clone https://github.com/galperins4/tbw
cd ~/dpos-pm2
cp node.json ~/ark-node/node.json (change node directory for matching coin)
cd ~/ark-node/
pm2 start node.json --only ark_mainnet (change selection after only for matching coin)
```
