# SoftLayer Driver

## Description

[IBM SoftLayer](http://www.softlayer.com/) offers an IaaS Public Cloud service in which cloud users can deploy their VMs.

Cloud bursting is a model in which the local resources of a Private Cloud are combined with resources from remote Cloud providers. This driver offers the possibility implement Cloud bursting by deploying Virtual Machines seamlessly on the IBM SoftLayer Cloud service.

## Authors

* [OpenNebula Core Team](https://github.com/OpenNebula)

## Features

* Cloud Bursting to IBM SoftLayer.
* Highly scalable hosting environments.

## Compatibility

This add-on is compatible with:

| OpenNebula Version |
| ------------------ |
| 5.0                |

## Installation

To install this add-on, clone it and run install.sh:

    sudo ./install.sh -u oneadmin -g oneadmin

You wil need to add the following to `/etc/one/oned.conf`: [oned.conf for SoftLayer](oned-sl.conf)

## Usage

The usage guide can be found here: [SoftLayer Driver](docs/slg.rst)

## Configuration

There are two configuration files:

* ``/etc/one/sl_driver.conf``: Configures access to SoftLayer: API keys and instance types.
* ``/etc/one/sl_driver.default``: Default values for templates deployed in SoftLayer.

## Development

To contribute bug patches or new features, you can use the github Pull Request model. It is assumed that code and documentation are contributed under the Apache License 2.0.
