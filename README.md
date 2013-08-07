# Logstash Package

Cribbed heavily from https://github.com/electrical/puppet-logstash

For building your own Debian Logstash package.

## Usage

```
$ ./build
```

## Issues

Many

* Fixed to use 1.1.13
* Blindly downloads a jar
* Dislikes spaces in dirnames
* Uses `sudo` to `chown` `root/` to `root`
* Assumes presence of `fpm`
