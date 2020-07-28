#Multi-variant machine

Welcome to Sohaib's repository which initialises multi-variant machine - This is known as a "multi-machine" environment.

# How to get the multi-machines running:

Please make sure you have all the following installed:

- Vagrant
- VirtualBox
- Ruby 
- Bundler

To run the multi-variant machine:

Download/clone this repo 

From the root of the directory, open terminal and run the following command:

```
vagrant up
```

```
vagrant status
```

Once the commands are inputted, you should see two machines running.


To see the project running successfully and to make sure you don't have any failures, run the following commands:

1. cd vagrant_multiple_machines_exercise/tests

2. rake spec

Once this is running, you should see 9 examples and 0 failures. This shows that the machines are running successfully with the
following packages: 

1. Nginx

2. Node

3. PM2

4. Git

5. Mongod


