# ACCESS-OM2 Experiments

This repository is central location to store the automatically generated payu run-logs from ACCESS-OM2 experiments. Please all experiments which are being shared.

To get write access, you need to create an issue and request access, please use [this issue template](https://github.com/ACCESS-Community-Hub/access-om2-experiments/issues/new?template=add-user-request-to--access-om2-experiments--repository-.md).

### Branch name conventions
Branches in this repository use the experiment name, as defined the `name:` field in `metadata.yaml` for the experiment 

This mayy require using a different branch name on the git `remote`:

e.g. a local experiment branch labelled `1deg_jra55_iaf-test1` could be pushed to a remote branch labelled `1deg_jra55_iaf-test1-y3e91b12`

``` bash
git remote add experiments https://github.com/ACCESS-Community-Hub/access-om2-experiments
git push -u experiments 1deg_jra55_iaf-test1:1deg_jra55_iaf-test1-y3e91b12
```

