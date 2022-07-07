# automate-bukkit
automatically update bukkit patchs and plugins 

## startup.sh
```
while true
do
git clone -b main-bukkit --single-branch https://github.com/IngGameTeam/automate-bukkit
cp -r automate-bukkit/bukkit/* ./
rm -rf automate-bukkit
./run.sh
done
```