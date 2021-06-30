
# About Your Allowlist on SnapLogic
To facilitate seamless and reliable inbound/outbound communication between your applications/systems and the SnapLogic Platform comprising Cloudplex, Groundplex, Control Plane, FeedMaster, SnapLogic UI/API, and Ultra Tasks, we need you to add the given IP addresses in your network.

_Note: SnapLogic Platform uses a High Availability (HA) configuration with support for Disaster Recovery (DR) failover. 
This requires you to add multiple IP addresses to your allowlist._

Additionally, consider the following guidelines:
* Ensure that your AWS (Amazon Web Services) S3 instance is accessible for SnapLogic SLFS (SnapLogic File System) files and enables you to download the SnapLogic WAR files. To allow access to S3, the IP address range is 52.216.0.0/15 per the official [AWS documentation.](https://ip-ranges.amazonaws.com/ip-ranges.json)
* We strongly recommend that you to enable S3 access on JCC (data processing) nodes and FeedMaster nodes.
* For Cloudplex IP addresses outside the US region, you can use either the [Snaplex Monitoring API request for REST clients](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/1438923/Snaplex+Monitoring+APIs#SnaplexMonitoringAPIs-UsingRESTClients) or the Health tab in SnapLogic Dashboard (see the following image) to retrieve the external IP address. 
