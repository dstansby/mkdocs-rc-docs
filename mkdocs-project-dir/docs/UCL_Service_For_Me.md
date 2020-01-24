---
title: UCL Service For Me
layout: docs
---

# Which service(s) at UCL are right for me?

Depending on the type of jobs you would like to run each cluster can have different requirements that your jobs must meet. When you submit your [user account application form](Account_Services/) you will be given access to the cluster depending on resources selected.

    Individual single core jobs
    Large numbers (>1000) of single core jobs
    Multithreaded jobs
    Extremely large quantities of RAM (>64GB)
    Small MPI jobs (<32 cores)
    Medium-sized MPI jobs (32-256 cores)
    Large-sized MPI jobs (>256 cores)
    At least one GPGPU
    At least ten GPGPUs
    
Each cluster has it's own specifications for the types of jobs that they run which is all dependable on list above. The cluster machines we have available are:

- Myriad

Myriad is designed to be most suitable for serial work, including large numbers of serial jobs, and multi-threaded jobs (using e.g. OpenMP). It also includes a small number of GPUs for development or testing work. 

- Grace

Grace is most suitable for multi-node jobs (using e.g. MPI). We recommend using Grace if you intend to use more than 36 cores per job.

- Legion

The Legion service is the older multipurpose cluster, including capability for serial jobs, multi-threaded jobs, and small multi-node jobs. It is currently being phased out, and we do not recommend Legion for new work.

- Thomas
- Michael