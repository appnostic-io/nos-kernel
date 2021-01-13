# nosticOS Linux Kernel

This repository houses the build system for the nosticOS Linux kernel.  

## Build System

The build system is based on [Dapper](https://github.com/rancher/dapper) from the folks over at Rancher which is an excellent tool to wrap Docker into the widely used Linux 'make' environment. 

## Building the Kernel

Building the kernel is fairly straightforward if this repository is used *as is*.  If you love to tinker and try new things and you feel that those would be beneficial to nosticOS please consider a pull request :)

To build the kernel you will need Docker at your disposal as the entire process is run inside containers.

To kick off the build process run:

```shell
make
```

After the build is complete you will find some .deb packages in the build/ directory and some .tar.xz files in the dist/artifacts directory.  These files are what we use for releases and in further build steps when building the completed OS image.

## Contributions

We welcome any contributions that make nosticOS better.  If you would like your ideas to be incorporated in to nosticOS feel free to raise it in the correct category on the issues board so that we can discuss it.

## Credits

Shoutouts and kudos to the folks over at Canonical and Ubuntu who work tirelessly on their own kernel modifications and additions only seen years later mainstream.  Your efforts are not unrecognized here.



