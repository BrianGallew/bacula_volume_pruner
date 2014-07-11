bacula_volume_pruner
====================

Tool for pruning volumes in Bacula

= Requirements

== clint 

Client provides a progress bar so we can track progress.

```pip install clint```

= Usage

```masterprune```

Iterates through all of your volume pools, attempting to prune all of your
volumes using the volume retention settings.

```masterprune Full```

Prune all of the pools with "Full" in the name.  Uses simple string finding.
