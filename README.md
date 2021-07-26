# /r/openttd Official Server Network 2014-2021
## Config Files

This repository contains the configuration files used to instantiate Server 1 and Server 2 of the Official /r/openttd Server Network which ran from 2014-2021.

### (server1.cfg & server3.cfg)

These files have been pasted verbatim from their Kubernetes configmap counterparts. You can use them as is, but be sure to override any mentions of `redacted` (namely passwords and the network_id) with secure replacements, and also change the hostname. **Banned client IP addresses are not included for privacy reasons.**

### Kubernetes manifests

S1, S3, and `ttdredd.it` ran on my private Kubernetes cloud. I drew up some super basic manifests to get them working in-cluster, and I will add these to the `/kubernetes` folder of this repository once they've been tidied up a little bit.
