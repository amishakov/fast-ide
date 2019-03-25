### Example of restore to new machine:

```Shell
$ cd ode
$ vagrant up
$ vagrant snapshot save default installed_devenv
```

### Example of restore to existed machine

```Shell
$ cd ode
$ sudo ./install.sh
$ ./bootstrap.sh
```
