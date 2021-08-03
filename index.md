
# About Your Allowlist on SnapLogic
To facilitate seamless and reliable inbound/outbound communication between your applications/systems and the SnapLogic Platform comprising Cloudplex, Groundplex, Control Plane, FeedMaster, SnapLogic UI/API, and Ultra Tasks, we need you to add the given IP addresses in your network.

_Note: SnapLogic Platform uses a High Availability (HA) configuration with support for Disaster Recovery (DR) failover. 
This requires you to add multiple IP addresses to your allowlist._

Additionally, consider the following guidelines:
* Ensure that your AWS (Amazon Web Services) S3 instance is accessible for SnapLogic SLFS (SnapLogic File System) files and enables you to download the SnapLogic WAR files. To allow access to S3, the IP address range is 52.216.0.0/15 per the official [AWS documentation.](https://ip-ranges.amazonaws.com/ip-ranges.json)
* We strongly recommend that you to enable S3 access on JCC (data processing) nodes and FeedMaster nodes.
* For Cloudplex IP addresses outside the US region, you can use either the [Snaplex Monitoring API request for REST clients](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/1438923/Snaplex+Monitoring+APIs#SnaplexMonitoringAPIs-UsingRESTClients) or the Health tab in SnapLogic Dashboard (see the following image) to retrieve the external IP address. 

snaplex_health![snaplex_health](https://user-images.githubusercontent.com/19984179/123368918-8c5dbf80-d531-11eb-8f01-618701df944f.png)
**<div align="center">Retrieve the external IP address for your Snaplex node</div>**

Update your IP allowlist to include all the IP addresses in the following tables per your requirement.

# Inbound traffic to SnapLogic Platform
You need to add the given IP addresses to your allowlist only if your network restricts outbound traffic.

SnapLogic Environment | Domain | Required IP Addresses to be on Your Allowlist (including HA) |
------------ | ------------- | ------------ |
Production | elastic.snaplogic.com </br> tcp.elastic.snaplogic.com </br> \*.snaplogic.io  | 52.11.8.103/32 </br> 34.208.181.167/32 </br> 52.10.35.99/32 </br> 52.36.97.11/32 </br> 52.25.90.203/32 </br> 34.210.197.128/32 </br> 52.12.92.65/32 </br> 3.220.248.243/32 </br> 3.220.248.158/32 </br> 54.92.192.251/32 </br> 54.157.253.74/32 </br> 18.235.232.49/32 </br> 50.16.206.60/32 |
UAT | uat.elastic.snaplogic.com </br> uat.tcp.elastic.snaplogic.com </br> \*.snaplogic.io | 52.39.163.113/32 </br> 52.32.143.155/32 </br> 35.163.6.133/32 </br> 44.232.154.15/32 </br> 54.245.88.186/32 </br> 34.210.102.144/32 </br> 3.225.35.150/32 </br> 52.87.92.31/32 </br> 34.226.102.107/32 </br> 54.146.10.130/32 </br> 52.206.133.85/32 </br> 52.205.203.252/32 |

## Your Cloudplex instances
_Note: Add the following IP addresses to your allowlist on the required endpoints to enable outbound requests from SnapLogic Cloudplex instances. Here is an [example](https://docs.aws.amazon.com/redshift/latest/mgmt/managing-security-groups-console.html#security-group-modify) of how you can add IP addresses on AWS Redshift._

SnapLogic Environment | Domain | Required IP Addresses to be on Your Allowlist (including HA) |
------------ | ------------- | ------------ |
Production | elastic.snaplogic.com | 34.209.24.34/32 </br> 34.208.230.181/32 </br> 3.218.75.185/32 </br> 3.218.106.208/32 |
UAT | uat.elastic.snaplogic.com | 35.161.252.12/32 </br> 34.212.109.28/32 |

_ _ _

#### See Also
* [Defining Network Settings](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/1439269/Defining+Network+Settings)

