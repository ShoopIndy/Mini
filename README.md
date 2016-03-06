# Mini
Using QuickCheck Mini for Elixir

This repository contains some examples on how to use Quviq's free QuickCheck version, called QuickCheck Mini.

Of course, the examples also work with the full version of QuickCheck.

Before you can use this repository, make sure you have QuickCheck installed. You can download QuickCheck Mini from www.quviq.com (or alternatively, use Dockerfile which will install QuickCheck Mini into a VM for you.)

# Setup using Docker

1. install Docker - https://docs.docker.com/engine/installation/
2. `cd [this project]`
3. `docker build -t eqc_elixir .`

If tests or libraries are added/modified, then re-run the `docker build..` command.

## Running

1. `docker run eqc_elixir`

This runs `mix tests` for this project.