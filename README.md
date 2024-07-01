# aks
aks cli
```
az aks show --resource-group rgmolmedo --name molmedo
az aks show --resource-group rgmolmedo --name molmedo -o table --query networkProfile
az aks show --resource-group rgmolmedo --name molmedo -o table --query privateFqdn
az aks list --query "[].{Name:name, Power:powerState.code}" -o table
```
