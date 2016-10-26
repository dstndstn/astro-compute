What should astro grad students know about computing?

* giving a talk
  * making figures that look good on projectors
  * tools for creating slide decks; math
  * (versioning, sharing, traceability/reproducibility)

* writing a paper / thesis
  * working with latex and templates
  * creating figures
  * working with / sharing work with others (github)
  * (versioning, sharing, traceability/reproducibility)

* performing an analysis / doing work
  * getting data from others
     * formats: CSV, VOtable?, FITS, HDF5?, tgz
     * transfer tools: rsync, scp, ftp, http/wget/curl
     * SQL?
  * managing data (organizing directory trees; versioning)
     * databases?
  * sharing data with others (formats, technologies)
  * developing code
     * emacs/vim/?, ipython, jupyter notebooks
     * scripting analyses; tracking provenance; checksums
     * making beautiful plots!
     * debugging (pdb)
     * git(hub) for single user, single machine (versioning, tags)
     * standard github flows:
        * collaborator: branch, push, pull request
        * external project: issue, fork, checkout, branch, push, pull request
     * test-driven development
     * continuous integration (travis-ci)
     * coverage tracking (coveralls)
     * profiling; python/C options (cython, swig, python/numpy?)
     * pair-coding
  * python infrastructure:
     * numpy, scipy, matplotlib
     * json, pickle
     * astropy, fitsio, ...
  * package management
     * (homebrew?  conda?  pip?  virtualenv?  docker?)
  * keeping backups & recovery plans
  * using stand-alone linux servers
     * ssh (keys, ssh-config, authorized_keys; tricks: port-forwarding, etc)
     * screen, disown
     * embarrassing parallelism FTW
     * python multiprocessing
     * filesystems; permissions (chmod, chgrp, etc)
     * visualization: X11, other options
     * moving files: git, rsync, sshfs/FUSE/NFS/Samba?
  * using clusters / supercomputers
     * batch systems: slurm? PBS?
     * MPI?
     * scratch filesystems
  * infrastructure:
     * shell -- variables, loops, globs, aliases, printf, grep, sed, awk?
       PATH, PYTHONPATH, +?
     * tar, rsync, ssh
     * filesystem management

* web development stuff
   * ~/public_html
   * github pages
   * python web scripting setup (apache + wsgi, uwsgi, ...)
   * python web scripting frameworks (flask, django, ...)
   * database integration (sqlalchemy?  django?)
   * html, javascript

* getting a job outside academia
   * "big data" vs "HPC" technologies
   * machine learning (pandas; scikit-learn; skepticism)



