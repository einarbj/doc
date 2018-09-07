NAIS manifest
=============

The NAIS manifest contains the configuration of your NAIS application. It can either be uploaded to our [Nexus](/doc/dev-guide/nexus.md), or specify an [external manifest](dev-guide/naisd.md#external-or-non-default-manifest-address) with `manifesturl` in the [deploy](/doc/dev-guide/naisd.md#deploy)-payload, or `manifest-url` has an argument to the [Naisd CLI](https://github.com/nais/naisd#nais-cli).

The main documentation for the content of this file is found here: https://github.com/nais/naisd/blob/master/nais_example.yaml


## Documented manifest values

Below you will find documentation on some of the values you can set in the manifest.

* [Alerts](/doc/contracts/alerts.md) - Alerts sent to Slack based on Prometheus scraping

* [Fasit resources](/doc/contracts/fasit_resources.md) - Resources retrieved from Fasit

* [Leader Election](/doc/services/leader_election.md) - Leader election between pods in a replicat set

* [Prometheus](/doc/contracts/metrics.md) - Metrics scraping from end point

* [Redis](/doc/services/redis.md) - Non-persistant in-memory data structure store