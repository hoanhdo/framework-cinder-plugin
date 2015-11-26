# Open vStorage OpenStack Cinder Plugin

Open vStorage is an open-source, scale-out, reliable, high performance, software based storage platform which offers a block & file interface on top of ethernet drives (Seagate Kinetic), object storage or a pool of traditional SATA drives. 

Open vStorage is licensed under the [Modified Apache License](http://www.openvstorage.org/OVS_NON_COMMERCIAL).

The Open vStorage Framework takes care of the communication between the different hosts in the Open vStorage cluster and the storage backends. The Framework allows to manage Open vStorage through an intuitive GUI and a complete REST API. It integrates with OpenStack (Cinder) and VMware vSphere.

This repo contains (the updated) versions of the Open vStorage OpenStack Cinder driver for Juno, Liberty, Kilo and Mitaka.
Some versions of OpenStack have this driver but it can no longer be updated because they no longer accept commits on those versions (Kilo).
Some versions of OpenStack don't have this driver because we weren't ready (Juno) or we no longer met the criteria to have a driver (Liberty).
On Mitaka, a review is pending and the driver will be readded in the main repo.

## Get started

On our community website you can find [more information](https://www.openvstorage.org) and [how to get started with an installation](https://www.openvstorage.org/doc/Installation).

## Support
* For community support, please visit our [community support forum](https://groups.google.com/forum/#!forum/open-vstorage)
* For commercial support, please [contact Open vStorage](https://www.openvstorage.com/contactus/) 

## Contribution & Packaging

We welcome contributions.
Packaging your own changes for testing can be done using the [packager module](packaging/generic/packager.py)

## File a bug
Open vStorage is quality checked to the highest level. Unfortunately we might have overlooked some tiny topics here or there. The Open vStorage Project maintains a [public issue tracker](https://github.com/openvstorage/openvstorage/issues) where you can report bugs and request features. This issue tracker is not a customer support forum but an error, flaw, failure, or fault in the Open vStorage software. 

## Nightly tests

A view on the different sets of Nightly test runs can be found [here](http://testrail.openvstorage.com/index.php?/runs/overview/10).
Email address ovs-guest@openvstorage.com with password 0vsgu3st should allow you to login and view the results
