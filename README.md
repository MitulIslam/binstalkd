# beanstalkd
minimal beanstalkd image for alpine

## Usage

start container

`docker run -d -p 11300:11300 mitulislam/beanstalkd`

use additional [options](https://linux.die.net/man/1/beanstalkd)

`docker run -d -p 11300:11300 mitulislam/beanstalkd -VV`

or

`docker run -d -p 11300:11300 mitulislam/beanstalkd -b /some/directory`