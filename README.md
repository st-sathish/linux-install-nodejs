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

The MIT License
===============

Copyright (c) 2016 Sathish Thangathurai

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
