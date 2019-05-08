# vagrant_d

### Purpose of the repository 
- The repository uses Ubuntu-xenial64 box and sets the CPU to 2 cores and the RAM to 2GB.

#### List of files in the repository

File name                            | File description 
------------------------------------ | --------------------------------------------------------------
`Vagrantfile` | file with sript that defines machine and configuration requirements.


### How to use this repository. 
- Install `virtualbox` by following this [instructions](https://www.virtualbox.org/wiki/Downloads).
- Install `vagrant` by following this [instructions](https://www.vagrantup.com/docs/installation/).
- Clone the repository to your local computer: `git clone https://github.com/nikcbg/vagrant_d`.
- Go to the cloned repo on your computer: `cd vagrant_d`.
- After that execute the commands in the table below.

Command execution                    | Command outcome
------------------------------------ | --------------------------------------------------------------
`vagrant up` | to power up the Ubuntu-xenial64 box.
`vagrant ssh` | to log in to the Ubuntu-xenial64 box.
`lscpu` | to list the CPU cores
`free -m` | to list RAM memory

### TO DO:
- Check if all works as expected. 
