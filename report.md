#### Debain

bash

apt-get update

apt-get install git, installed

apt-get -y install libopenmpi-dev

apt install libgl1-mesa-glx



```
conda create -y -n spinningup python=3.6
conda activate spinningup
conda install pytorch==1.4.0 torchvision==0.5.0 cpuonly -c pytorch

# pip install
git clone https://github.com/borninfreedom/spinningup.git
cd spinningup
pip install -e .

# run the script or the code
```



clean build..



What is my aim?

build the repo for deploy pybullet training

- training
- log
- smallest



TODO

- CPU or GPU
- bebian or centos or ubuntu?
- codna based?
- remove other packages?

---



import ppo.ppo error

![image-20210417120023470](https://tva1.sinaimg.cn/large/008eGmZEgy1gpmy0yz17cj31fv0u0wwd.jpg)

why this problem? debain?



change to anaconda

git clone my repo

cd xx

docker build -t zanehuang/pybullet_spinningup:cpu .



git pull















### Ubuntu

![CleanShot 2021-04-17 at 12.06.00@2x](https://tva1.sinaimg.cn/large/008eGmZEgy1gpmy6u55q0j31l20u04qp.jpg)

```
docker run -p 6080:80 -v /dev/shm:/dev/shm dorowu/ubuntu-desktop-lxde-vnc
```