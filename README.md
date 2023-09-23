# Label Studio in Docker

Welcome to the **Label Studio in Docker** repository!

Label Studio is a versatile tool designed for data annotation,
supporting various data types ranging from text and audio to
images and videos. By hosting it in Docker, we've eliminated
the hassles associated with setup and dependencies, providing
you a smooth experience right out of the box.

This repository provides a convenient way to run Label Studio
within a Docker container, simplifying the setup and execution
processes. Whether you're a machine learning enthusiast or a
seasoned data scientist, this project aims to streamline your
dataset creation experience.

For those interested, this project was inspired and built upon
the experiences detailed in a
[Russian publication](https://dzen.ru/a/ZQLV97l1HHUtnmVh) about
the project.

> Inside the project, there's a [datasets](./datasets) directory
which contains sample files to help you create basic datasets.

## Quick Start

Clone the repository:

```shell
git clone https://github.com/EvilFreelancer/docker-label-studio.git
cd docker-label-studio
```

Copy the distribution docker-compose file:

```shell
cp docker-compose.dist.yml docker-compose.yml
```

Copy the environment example file to set up your environment variables:

```shell
cp .env.example .env
```

Finally, run the project:

```shell
docker-compose up -d
```

## Links

* [Original Label Studio Website](https://labelstud.io/)
* [Label Studio GitHub Repository](https://github.com/HumanSignal/label-studio)
* [Related Project: ru-toxicml-api](https://github.com/EvilFreelancer/ru-toxicml-api)
