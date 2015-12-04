# Internet Storage Sync ( ISS )

**Internet Storage Sync - Mechanisms to synchronize client file systems with Internet-based data storage services**

This repository contains supporting documents for [ISS](https://tools.ietf.org/html/draft-cui-iss-problem-03) discussion topics that are not suitable to be tracked in the mailing list.


[Internet Storage Sync](https://tools.ietf.org/html/draft-cui-iss-problem-03) is an IETF working draft with the following objective:

```
Internet storage services have become more and more popular.  They
attract a huge number of users and produce a significant share of
Internet traffic.  Most existing Internet storage services make use
of proprietary sync protocols with different capabilities to achieve
the data sync.  However, a single Internet storage service using its
proprietary sync protocols has intrinsic limitations on service
usability and network performance.  This document outlines the
related problems caused by using proprietary sync protocols and
missing key capabilities.  It also shows a demand for designing a
standard sync protocol to achieve better usability and sync
performance.
```

## Topics of interest

```
1.The design targets of WebDAV, rsync and other existing approaches?
2.The potential use cases of ISS, such as client/server, git-like pattern, svn, etc.
3.The efficiency improvements might be the second goal for standardizing ISS protocol
4.CORS headers on storage sync APIs
5.What is needed for the ISS: a sync protocol or a generalized API
6.remoteStorage draft discussion
	a)relationship vs WebDAV
	b)MOVE action should be added or not
	c)synchronization should be considered or not
	d)comics of new standard
7.GitHub instead of email messages
	a)What is the topic? 
		i.Whether it is suitable to build on WebDAV
		ii.WebDAV vs remoteStorage
		iii.Advantages vs disadvantages of WebDAV
```


## Supporting documents
To contribute to these documents, please read [How To Contribute](#how-to-contribute).

* [Applicability of WebDAV (RFC 4918) for synchronisation purposes ?](./applicability-of-webdav.md).


## Related projects and organisations
This is a list of projects and organisations which activities are highly "in sync" with the topics covered in the ISS group.

*List is alphabetically sorted*

* [ClawIO](http://clawio.github.io) [Project]
* [CrossCloud.me](https://crosscloud.me/) [Product]
* [CrossCloud.org](http://crosscloud.org/jobs/) [Project]
* [CS3: Cloud Services for Synchronisation and Sharing ](http://cs3.ethz.ch/program.html) [Conference]
* [GEANT Community](http://www.geant.org/) [Community]
* [OpenCloudMesh](http://oc.owncloud.com/opencloudmesh.html) [Project]
* [ownCloud](http://owncloud.org) [Product]
* [remoteStorage](https://remotestorage.io/) [Protocol]



## How To Contribute
New contributions to these documents have to be previously discussed using the [ISS mailing list](https://www.ietf.org/mailman/listinfo/storagesync).

The contribution flow is the following:

1. Open a discussion in the [ISS mailing list](https://www.ietf.org/mailman/listinfo/storagesync).
2. Other members of the [ISS mailing list](https://www.ietf.org/mailman/listinfo/storagesync) will give their opinion and review the topic presented.
3. When there is a general agreement on the topic anyone can contribute to these documents using one of the mechanisms outlined below in order to have the information pressented in a more efficient way.

Contributions to these documents can be made using the following ways:

* Pull Request (Recommended) 
* Issue
