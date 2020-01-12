# Setup Spark environment for this course.

Please raise issue/pull-request incase you get some problem or question.

## MacOS/Linux
1. Install latest virtual box
2. Install latest vagrant by execute this command
```bash
$ brew cask install vagrant
```
3. Download and put `package.box` to `/Users/your_user_name/.vagrant.d/boxes`
4. Execute this command to create new VM box
```
$ vagrant box add sparkmooc-VAGRANTSLASH-base2 ~/your_user_name/.vagrant.d/boxes/package.box
```
5. Clone this project
```
$ git clone https://github.com/spark-mooc/mooc-setup.git
```
**OR** download and extract
```
https://github.com/spark-mooc/mooc-setup/archive/master.zip
```
6. Inside `mooc-setup` folder, Execute command
```
$ vagrant up
```
7. Browse to `http://127.0.0.1:8001` by browser

## Windows
1. Install Virtual box and Vagrant
2. Download and put `package.box` to `C:/Users/you_user/.vagrant.d/boxes`
3. Execute command to create new VM box
```
$ vagrant box add sparkmooc-VAGRANTSLASH-base2 C:/Users/you_user/.vagrant.d/boxes/package.box
```
4. Clone this project in case of you have git in your laptop
```
$ git clone https://github.com/spark-mooc/mooc-setup.git
```
**OR** download or extract
```
https://github.com/spark-mooc/mooc-setup/archive/master.zip
```
5. Inside `mooc-setup` folder, Execute command
```
$ vagrant up
```
7. Browse to `http://127.0.0.1:8001` by browser