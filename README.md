# Usage

wget https://github.com/bobcatminer/dist/raw/main/diagnoser 

chmod +x diagnoser 

./diagnoser start -d

./diagnoser stop

./diagnoser version

# Access 44168

http://${IP}:44168

```
wget -O temp.json http://localhost:44168/temp.json && cat temp.json

wget -O miner.json http://localhost:44168/miner.json && cat miner.json

wget -O facts.json http://localhost:44168/facts.json && cat facts.json
```
