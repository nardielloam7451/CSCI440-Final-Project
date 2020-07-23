# CSCI 440 - Database Systems

This is the base upstream repository for CSCI 440.  It contains homeworks as well as the class project 
information.

## Getting Your Copy

Please use the following steps to create a *private* version of this repo for your work:

- Clone this repository to your local system with `git clone https://github.com/msu/csci-440-fall2020.git`
- Create a *private* repository in your own account by
    - Going to <https://github.com/new>
    - Enter the name `csci-440-fall2020`
    - Select `Private`
- Now run the following git commands, substituting your Github user name and email where required:
```bash
$ git clone https://github.com/msu/csci-440-fall2020.git
$ cd csci-440-fall2020
$ git remote set-url origin git@github.com:<your user name>/csci-440-fall2020.git
$ git remote add upstream https://github.com/msu/csci-440-fall2020.git
$ git checkout -b <your email address>@montana.edu
$ git push --set-upstream origin <your email address>@montana.edu
```
Whew!  You now have a private copy of the repository on github and are working in your own branch.  You can push and pull to this repository with the standard `git pull` and `git push` commands.

When you want to get an update from the public class repository you can run this command:
```
$ git pull upstream master
```

## Homeworks

Each homework has it's own directory (`/hwk0`, `/hwk1`, etc.).  Please do your work in the homework directory

## Project: TBD

You will be implementing a web application against a SQL store, found in `/db/chinook.db`

Details coming soon.

### Project Resources

* [Spark Java Docs](http://sparkjava.com/documentation)
* [Velocity Templates Docs](https://velocity.apache.org/engine/2.2/user-guide.html#loops)
* [Active JDBC Docs](https://javalite.io/activejdbc)
