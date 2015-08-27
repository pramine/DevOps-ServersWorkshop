ServersWorkshop
===============

You must get into pairs.  And there is a *twist*.

### Setup

1. Make sure you have [git](http://git-scm.com/) installed, as well as [node.js](http://nodejs.org/)
2. Start with **forking** this repository.
3. Clone local copy 

`git clone https://github.ncsu.edu/YOUR REPO`

##### Using package manager, install dev dependencies

`npm install`

##### Run the node program

`node main.js`

You will see, output:
`Calls remaining 4995`

**Bonus**: The first 3 pairs to finish workshop will receive +5 points on their final workshop grade. *But*,
if the rate-limit hits 0, everyone will loose 5 points on their workshop final grade. 
![saw](https://cloud.githubusercontent.com/assets/742934/9525410/ff96de96-4cb1-11e5-84af-19b70cbae957.png)

### Workshop

Complete the remaining 7 steps specified in the code comments of [`main.js`](https://github.ncsu.edu/CSC-DevOps-Spring2015/ServersWorkshop/blob/master/main.js).

You will be experimenting with code for provisioning a new server in a particular data center, that is initialized with a specified virtual machine image, using the [digitalocean api v2](https://developers.digitalocean.com/v2/).

The code makes use of the [needle api](https://github.com/tomas/needle#needle) for making http requests.

##### Final Step

Create a new branch, remove api token from `main.js`, and push to your REPO.
