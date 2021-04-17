<!-- TABLE OF CONTENTS -->

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#TODO">TODO</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->

## About The Project

Robot learning projects are usually tested in a system with a GUI interface. After the test, we want to deploy the project on a server for large-scale training to improve training efficiency. However, the local training environment may cause hardware compatibility issues during migration and deployment. Docker is. I want to develop a Pybullet robot learning container based on Docker.

Here's why:
* Portability: Docker is an open-source application container engine that allows developers to package their applications and dependencies into a portable image and then publish to any popular Linux or Windows machine.
* Efficient: Through Docker, you can control the server's CPU or GPU resources and run multiple containers for training simultaneously. And we aggregate the experimental data results of all containers through wandb.

A list of commonly used resources that I find helpful are listed in the acknowledgements.



### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Docker](https://www.docker.com/)
* [Pybullet](https://pybullet.org/)
* [anaconda3 dockerfile](https://github.com/ContinuumIO/docker-images/tree/master/anaconda3)
* [wandb](https://wandb.ai/)



<!-- USAGE EXAMPLES -->

## Usage

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Install docker at https://docs.docker.com/get-docker/



### Docker pull (recommend)



### Build image from dockerfile

1. Clone the repo

~~~
git clone https://github.com/zebin-huang/docker_pybullet.git
~~~

2. Build docker image from dockerfile. It will take some minutes to build the image.

~~~
docker build -t your_name/pybullet_spinningup:cpu .
~~~

3. Run the docker image

~~~
mkdir src

~~~

4. Pip install spiningup, you can replace your env

```
bash
conda activate spinningup
# clone my version, I made some changes.
git clone https://github.com/borninfreedom/spinningup.git
cd spinningup
pip install -e .
```



<!-- TODO -->

## TODO

- wandb support
- GPU image development
- Docker multiple container deployment
- Docker CPU/GPU resource management
- Remove unnecessary dependencies



<!-- LICENSE -->


## License

Distributed under the Apache License 2.0  License. See `LICENSE` for more information.



<!-- CONTACT -->

## Contact

Your Name - [@Zebin Huang](https://github.com/zebin-huang)

Project Link: [https://github.com/zebin-huang/docker_pybullet](https://github.com/zebin-huang/docker_pybullet)



<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements
- [borninfreedom](https://github.com/borninfreedom)/[kuka-reach-drl](https://github.com/borninfreedom/kuka-reach-drl)

* [othneildrew](https://github.com/othneildrew)/[Best-README-Template](https://github.com/othneildrew/Best-README-Template)

