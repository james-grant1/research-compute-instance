# Research Compute Instance

## Background

The archetypal research instance.  Set up an instance with budget controls and authentication, through AD.  The BluePrint(s) should be able to:
1. select an image from the Marketplace e.g. OpenFoam, NAMD
2. an institutional/community resource for large builds in accordance with any licensing conditions
3. or a standard disk clone a software repo, dependencies and install.

Have attached storage appropriate to the code(?)
Copy input data from Blob storage
Launch code
Monitor progress (is code running/stalled?)
If complete copy (necessary) output to blob storage
Else if stalled/exceeded walltime, persist attach storage/copy all files to blob
Update some DB logging tool
Which in turn updates user.


# Sprint objectives 
* Create Blueprints and learning path to ensure security of a single instance: data, access and cost

### Learning prerequisites
