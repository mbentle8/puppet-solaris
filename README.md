# Puppet Solaris 11 Enhancements

[![Build Status](https://travis-ci.org/nanliu/puppet-solaris.png?branch=master)](https://travis-ci.org/nanliu/puppet-solaris)

Forked from:  https://github.com/nanliu/puppet-solaris

Facter facts removed, as they are now core facts in Puppet 3.8 / Facter 2.4

## Overview
This project is intended have a Puppet module to resolve outstanding bugs and add new features for Solaris.

Currently existing types provider seems to lack self.instances [#10978](http://projects.puppetlabs.com/issues/10978)

## Usage

Since there are subtle difference in the command output across Solaris versions, it would be benificial to test the code here in as Solaris 9/10/11 and OpenIndiana.  Please update the tickets above with any issues discovered when testing this module.

## Contribution

The code here have been based on contributions from:

* Martin England
* Stefan Schulte
