# library
Library to support the IEEE 2791-2020 standard.

### Proposed Library Features:

| Command | Description |
----------| ------------|
| bco.accepted | Returns `true` if all reviewers on a BCO have a value of `approved`; Returns false for all other conditions |
| bco.prov.pubs(contributor) | Returns PMIDs for a contributor |
| bco.envcheck | Returns `true` if all prerequisites listed in a BCO are installed in the local environment, throws warnings if version mismatch; error messages indicate specific prerequisites not present |
| bco.infiles | Returns array of all input files (full URIs) |
| bco.outfiles | Returns array of all output files (full URIs) |
| bco.tree | Finds instances where more than one step refer to the same input to describe branching (for visual representation of steps) |
