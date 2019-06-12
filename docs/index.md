# Introduction

The term _storage_ can mean different things to different people depending on one's perspective. An application developer who needs some storage could mean _object storage_ aka a database in which they can store some data.

That same application developer who needs to store same raw data on a disk could mean that the need _file storage_.  This is just a filesystem where random files can be stored.

When an operations person talks about storage, they typically mean _block storage_.  That would be a chunck of raw storage which could be formatted with any kind of operating system depending the need.

That same operations person could mean _virtual storage_ which is essentially a file which represents the hard disk of a virtual machine.

When speaking with a storage engineer one could be talking about _physical storage_ - a Direct Access Storage Device (DASD) such is a mechanical disk, or SSD/NVMe/flash drive. That same engineer could be talking about a SAN based storage array such as an IBM Elastic Storage Server or XIV.

In reality all of these things are _storage_ and all are important when considering how to provide some space where an application can store some data which is the ultimate goal.

This document will describe all aspects of providing storage for cloud based applications including recommendations for low level infrastructure all the way up to object storage databases.

**Part I** will talk about all of the various concepts associated with providing cloud storage.

**Part II** will provide specific recipes describing how to implement various cloud storage technologies.

**Appendix A** will provide performance benchmarks for various types of storage.  These benchmarks will carry out the exact same operations on various storage technologies and provide key performance indicators which can be compared to determine the best solution for your storage requirements.
