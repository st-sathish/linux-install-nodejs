### **Node js Installation in Ubuntu 14.04 via PPA:**

##### **Add the below PPA repository:**

```sh
sudo add-apt-repository ppa:chris-lea/node.js
```
![Add PPA Repository](https://github.com/st-sathish/linux-install-nodejs/raw/master/screenshots/nodejs_0.png)

##### **Run the below command to update the added repository:**

```sh
sudo apt-get update
```

##### **Install nodejs:**

```sh
sudo apt-get install nodejs
```
![Install nodejs](https://github.com/st-sathish/linux-install-nodejs/raw/master/screenshots/nodejs_1.png)


##### **This step is optional:**

> npm is bundled with node.js and will be installed automatically if you install this way.If you want to make 
> sure you've got the very most recent release of npm,you can do:

```sh
sudo npm install npm -g
```
![Install npm](https://github.com/st-sathish/linux-install-nodejs/raw/master/screenshots/nodejs_2.png)

##### **Check a version:**

```sh
node --version
```
![version](https://github.com/st-sathish/linux-install-nodejs/raw/master/screenshots/node_version.png)

License
----

MIT