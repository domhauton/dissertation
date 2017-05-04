# Membrane - A Peer-To-Peer Backup System

Abstract
--------

Membrane is an amalgam of distributed storage and backup software, designed to operate on a very large scale: terabytes of data backed up across thousands of users across the world. A Membrane user is able to trade storage space with peers across the network, allowing them to securely store their backups world wide providing the user with data resilience with high availability at no monetary cost to the peer.

The applications vary from users who require a secure backup tool with file versioning for their important documents, to corporations that need to provide data resilience to their employees without investing in infrastructure, instead making use of redundant storage space on employee terminals.

In this report we follow the design and construction of Membrane, drawing on knowledge from distributed storage, intelligent agent technology and existing backup tools, finishing by providing a sound analysis of the completed solution. The software created succeeds in all test scenarios providing an easy install that requires no domain knowledge, capable of reconstructing backed up files directly from the peer swarm.

Dissertation
-----------

PDF available [here](https://github.com/domhauton/dissertation/blob/master/dissertation/dissertation.pdf).

Code
----

[Daemon](https://github.com/domhauton/membraned) | [GUI](https://github.com/domhauton/membrane-gui) | [CLI](https://github.com/domhauton/membrane-cli)
