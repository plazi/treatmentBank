# Insights into editing annotations
## Treatments
### Splitting treatments
Treatments that are already in BLR and include two ore more treatments can be split. On splitting the treatment (or any other annotation), all the attributes except for the UUID are copied. If the treatment you split is already on Zenodo (as indicated by the presence of the `ID-Zenodo-Dep` attribute), you need to set it to `-2` to have the original deposition replaced/deprecated. (see [25](https://github.com/plazi/treatmentBank/issues/25#issuecomment-1020293795) 
