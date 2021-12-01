# cc-sort-with-rev
A project based on cyancore software framework

To run this example, follow the below commands
```
$ git clone https://github.com/VisorFolks/cyancore.git               # Clone cyancore repo
$ vi mk/tc_get.mk       # Updated toolchain
$ cd src/projects
$ git clone https://github.com/akashkollipara/cc-sort-with-rev.git   # Clone this repo
$ cd ../../
$ make get_avr_tc       # Use correct command for fetching toolchain, this is just for illustration purpose
$ make cc-sort-with-rev # build will be locate at out/cc-sort-with-rev
```

Flash the binary on target using respective programmer.

Below is the demo running on atmega328p (Arduino Uno)

![image](./img/cc-sort-with-rev.png)
