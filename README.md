### Overview

**Note 2: Simian now supports the recently released Munki2 client!**

Simian is an enterprise-class Mac OS X software deployment solution hosted on Google App Engine (why [App Engine](../../wiki/AppEngineAtAGlance)?). It scales to any enterprise fleet size automatically, and offers a future proof client extended from the active [Munki open-source project](https://github.com/munki/munki).

Because the Simian server is live code, not a static file server, it offers unique benefits over a typical Munki+Apache deployment:
  * Simian can generate software manifests dynamically, on the fly, based on client properties.
  * The administration overhead of static manifest management is removed.
  * Any possible customizations to client software offerings are possible by modifying the server.

In summary, Simian's feature set allows it to:
  * Deploy new or updated software by targeting a single Mac or tens of thousands.
  * Deploy updates whether the Mac is on an internal network/VPN or not.
  * Force unattended/background installation of some packages, while allowing others to be optional.
  * Forcefully deploy security patches and reboot Macs after a given date, with varying levels of warning notifications.
  * Tightly manage Apple Software Update catalogs and update release, or let updates auto-promote automatically.
  * Dynamically target clients based on user, hostname, os version, group (tag), and more.
  * Obtain reports on all of this and the fleet overall.

Much of this and more is due to the outstanding work of Greg Neagle and the Munki community.  To read more about the other features Munki offers please visit the [Munki on GitHub](https://github.com/munki/munki).

### Getting Started

Please refer to the [Wiki documentation](../../wiki/AdminSetup) for instructions on how to download, configure, build, and deploy Simian.

For screenshots and an overview of Simian features, please see the [SimianAtAGlance wiki](../../wiki/SimianAtAGlance).

### Contact

If you have an issue or question which isn't covered in the Wiki documentation, we recommend you search and then post to the [simian-discuss@googlegroups.com Google Group](https://groups.google.com/forum/#!forum/simian-discuss).

If your question is sensitive in nature, feel free to reach direct to the engineering team at simian-eng@googlegroups.com.

Finally, if you'd like to stay aware of future Simian news, please subscribe to [simian-announce@googlegroups.com Google Group](https://groups.google.com/forum/#!forum/simian-announce)
