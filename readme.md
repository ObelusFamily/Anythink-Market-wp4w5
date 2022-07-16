# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Install Docker | Initial Build
1. Install Docker onto your OS of choice: https://docs.docker.com/get-docker/.
2. Following the instructions will direct you to turn on certain windows features (Virtual Machine Platform, Windows Hypervisor Platform, Windows subsystem for Linux ).
3. You may be required to turn on Hyper-V in your BIOS - refer to your specific Motherboard manual for instructions.
4. You may need to manually download the WSL2 Linux Kernel Package - following the instructions here: https://docs.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package.
5. From your terminal, run docker -v to confirm docker is ready. Then run docker-compose up from the root directory of the project.
6. Navigate to http://localhost:3000/api/ping in a browser to confirm it is up and running.

