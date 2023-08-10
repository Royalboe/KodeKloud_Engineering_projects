# Linux Resource Limit

## Description

On our Storage server in Stratos Datacenter we are having some issues where nfsuser user is holding hundred of processes, which is degrading the performance of the server. Therefore, we have a requirement to limit its maximum processes. Please set its maximum process limits as below:

### Steps

a. soft limit = 1025

b. hard_limit = 2024