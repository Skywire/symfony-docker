# Symfony Docker

A simple docker setup for Symfony applications

# Installation

`composer require skywire/symfony-docker`

Copy `.env.docker.dist` to `.env.docker` and add your required Docker configuration

# Usage

Core docker config is in `docker-compose.yml` and various DockerFiles in `skywire/docker`

Local overrides can be created in `docker-compose.override.yml` which is empty by default.

All files expect for `docker-compose.override.yml` will be overwritten on `composer install`
