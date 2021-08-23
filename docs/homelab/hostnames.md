---
tags: homelab hostnames
---

* I will want to have a standard naming convention for my machines as I create new machines in my network.
* From my experience a name can be derived using things that describe the machine
* Things to consider including:
  * Home or Cloud:  [h, c]
  * cloud provider? Right now only DO, but could expand [h, d, a, g, l, m]
  * Bare metal or Virtualized [b, v]
  * main functionality of the server. e.g. [[hypervisor]] [h, w, a, d]
  * main application running on the server. e.g. [[kvm]] 
  * [[os]] [lu, mw] (linux ubuntu, microsoft windows....in case)
  * unique identifier, auto incremented 2 character field
* Probably not going to use all the above fields, because it grows unruly pretty fast.
  * Going to go with what seems most important
    * first letter, location [h, c]
    * second letter, baremetal or virtualized [b, v]
    * third letter, main functionality [h, w, a, d]
    * unique identifier
* examples, 
  * a baremetal hypervisor in my home running proxmox
    * hbh01
  * a cloud provided droplet on digital ocean running a caddy server
    * cvw01
  * A kubernetes worker node running as a vm in proxmox
    * hva01