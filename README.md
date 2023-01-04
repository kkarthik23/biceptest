# bicepsamples

bicep files for Azure resource deployments

```
Get-AzSubscription
$context = Get-AzSubscription -SubscriptionId {Your subscription ID}
Set-AzContext $context
New-AzResourceGroupDeployment -TemplateFile main.bicep
```
