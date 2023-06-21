# MarsRover

## Instructions

[See instructions here](https://katalyst.codurance.com/simple-mars-rover)

## Getting started


### With Docker

If you plan on running the test with docker, run the `./install` command first.


### Install dependencies

Run `composer install` to get dependencies.

Alternatively, you can install dependencies using docker with `docker-compose run --rm php composer install`.

### Ensemble Programming

In the case we want to do Ensemble programming, also known as Mob Programming, and each of us want to use it's own setup, or because we are working remotly, you can install [mob.sh](https://mob.sh/).
Mob.sh will help us to do the code hand over via git.

## Run tests

You can run tests with PhpUnit using `./vendor/bin/phpunit`.

If you prefer using docker you can run tests with `docker-compose run --rm php ./vendor/bin/phpunit`.

A Test Run Logger is installed and logs all test runs. At the end of the kata you
can take a moment to review the logs and see if you see strange patterns. To make it easier
to review you can write the time when you're entering or leaving a refactoring phase, or when
you're facing difficulties. If you see something weird, what could have you done differently to avoid it?



