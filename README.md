# MbedOs RBDC librairy package

This is a librairy package to get RBDC working through MbedOS. It will import the following required libraries:

* RBDC

* 6tron_pid

* 6tron_odometry

* 6tron_motor-base

Additionally, this package add the following non-required libraries, for better application integration:

* 6tron_motor
* 6tron_motor-sensor

To add the RBDC to yout MbedOs project, simply type the following in the root folder of your project, using Mbed CLI 1:

```shell
mbed add https://github.com/catie-aq/mbed_rbdc-package rbdc-package
```



