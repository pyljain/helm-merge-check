# STEPS

1. Update the Values manifest to set `coinEnabled` or `vaultEnabled` keys 
2. Run the following to see templates with updates applied based on the keys selected in the values manifest

```sh

helm template test .

```