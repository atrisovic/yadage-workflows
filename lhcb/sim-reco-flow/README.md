# LHCb simulation production workflow

This is an example of production of simulated data at LHCb, presented in a yadage workflow.

## Run with Yadage
```
cd workflow/
eval "$(cat yadagedocker.sh)"  
yadage-run <workdir> workflow.yml
```
