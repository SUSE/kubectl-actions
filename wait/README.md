# Kubectl Wait

Waits for a resource to meet a condition.

## Inputs

| Name | Description | Required | Default |
| --- | --- | --- | --- |
| resource | The resource to wait for. It can include the resouce name. | true |  |
| namespace | The namespace of the resource. | false |  |
| selector | An optional selector to be used to filter the resources to watch.  | false |  |
| condition | The condition for the kubectl wait command. | false | ready |
| timeout | A timeout for the waiting. Optional suffixes 's', 'm' and 'h' can be used respectively for seconds, minutes and hours.  | false | 2m |

## Outputs

This action has no outputs.
