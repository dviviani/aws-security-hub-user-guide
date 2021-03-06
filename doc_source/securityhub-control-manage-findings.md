# Viewing and taking action on control findings<a name="securityhub-control-manage-findings"></a>

The control details page contains a list of active findings for the control\. The list does not include archived findings\.

The list provides tools to filter and sort the findings, so that you can focus on more urgent findings first\. Each finding can include links to resource details in the related service console\. For controls that are based on AWS Config rules, you can view details about the rule and the configuration timeline\.

You can also use the AWS Security Hub API to retrieve a list of findings\. See [Retrieving finding details \(Security Hub API, AWS CLI\)](finding-retrieve-api-cli.md)\.

**Topics**
+ [Accommodating controls that have a high volume of findings](#control-finding-high-volume)
+ [Filtering and sorting the control finding list](control-finding-list.md)
+ [Viewing details about a control finding and finding resource](control-finding-resource-details.md)
+ [Taking action on control findings](control-finding-take-action.md)

## Accommodating controls that have a high volume of findings<a name="control-finding-high-volume"></a>

The finding list on the control details page can accommodate up to 100 findings\.

If a control has more than 100 active findings, then the finding list uses the same layout as the list that is on the **Findings** page\. The tabs are disabled\.

You can filter, view details for, and take action on findings in the same way that you would on the **Findings** page\.

See [Viewing findings in AWS Security Hub](securityhub-findings-viewing.md) and [Taking action on findings in AWS Security Hub](securityhub-findings-taking-action.md)\.