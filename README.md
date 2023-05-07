# volatility-profiles
My blog post *Building a Linux profile for Volatility 2 and 3*:

https://forensenellanebbia.blogspot.com/2021/02/building-profile-for-volatility-2-and-3.html

Copy the profile files to:

- Volatility 2: ~/volatility/volatility/plugins/overlays/**linux**/
- Volatility 3: ~/volatility3/volatility3/symbols/**linux**/

## Useful resources

**Red Hat Enterprise Linux (RHEL)**

* /pub/redhat/linux/enterprise: http://ftp.redhat.com/pub/redhat/linux/enterprise/
* Download Red Hat Enterprise Linux: https://access.redhat.com/downloads
* Red Hat Packages: https://access.redhat.com/downloads/content/package-browser
* Activation Keys: https://console.redhat.com/settings/connector/activation-keys
* How to register a system to Red Hat Subscription Management using an activation key?: https://access.redhat.com/solutions/3341191

Register your installation to install packages from redhat repo:

>subscription-manager register --org=ORG ID --activationkey=Key Name

Install these packages:

>dnf install gcc make elfutils-libelf-devel

**CentOS**

* http://mirror.centos.org/centos/7/updates/x86_64/Packages/
* http://debuginfo.centos.org/7/x86_64/

**Fedora**

* https://kojipkgs.fedoraproject.org/packages/kernel/

**SUSE Linux Enterprise Server (SLE)**

* Download trial ISO: https://www.suse.com/download/sles/
* Request trial code: https://scc.suse.com/products/2140

**libdwarf/dwarfdump**

* https://www.prevanders.net/dwarf.html#releases
