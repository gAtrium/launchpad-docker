# launchpad-docker

## INSTALLING

Head over to evm-base. This will install debian bullseye along with required nodejs versions 
Run:
`docker build -t evm-base .`
The installation will take around 625~ MB

Next, prepare the node app container. This will be relatively fast. cd into launchpad-docker
`docker build -t launchpad-docker .`

## RUNNING
Clone your project and remember it's location. For example: /home/emre/Documents/launchpad
`docker run -it -v /home/emre/Documents/launchpad:/app -p 3000:3000 launchpad-docker`

This will run `yarn` and `yarn start` on your cloned folder. Check if you can access your project from localhost:3000
