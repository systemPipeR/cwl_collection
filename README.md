# cwl_collection

[CWL](https://www.commonwl.org/) CommandLineTool and Workflow descriptions for a variety of applications

- CWL userGuide: https://www.commonwl.org/user_guide/

# How to update or create new files?

Any edition or new file added to this repository, will automatically trigger a
push to [*systemPipeRdata* (SPRdata)](https://github.com/tgirke/systemPipeRdata) 
and [*systemPipeR* (SPR)](https://github.com/tgirke/systemPipeR) repositories master branch. 

Please notice that modifications are not synced automatically with upstream/Bioc 
branch for the `SPR` and `SPRdata` packages. The latter needs to be done manually,
as follows:

```
git push upstream master # Push to Bioconductor 
```
