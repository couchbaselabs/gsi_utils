# GSI-Utils

GSI-Utils repo contains a bunch of scripts which will help in running GSI specific workloads on any couchbase test framework.


# List of scripts

Below is a bunch of scripts which run various GSI specific workloads

## Upgrade workflow

This script will help in running mutations and query workload in parallel before and after upgrade process and then compare key stats such as CPU and Memory usage before and after the upgrade. It also collects CPU pprof before and after upgrade.Based on an user defined threshold for the max difference between the stats, the data is written to a couchbase bucket where in logs files are also present for further analysis

## KV - Index doc comparison

This script will help in verifying whether is parity between documents between KV and GSI service.
