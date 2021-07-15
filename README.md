# Adding the SnapLogic Platform to your Allowlist - SnapLogic Documentation

**In this article**

## About Your Allowlist on SnapLogic <a id="About-Your-Allowlist-on-SnapLogic"></a>

To facilitate seamless and reliable inbound/outbound communication between your applications/systems and the SnapLogic Platform comprising Cloudplex, Groundplex, Control Plane, FeedMaster, SnapLogic UI/API, and Ultra Tasks, we need you to add the said IP addresses in your network.

SnapLogic Platform uses a High Availability \(HA\) configuration with support for Disaster Recovery \(DR\) failover in case that's ever needed. This requires you to add multiple IP addresses to your allowlist.

Additionally, consider the following guidelines:

* Ensure that your AWS \(Amazon Web Services\) S3 instance is accessible for SnapLogic SLFS \(SnapLogic File System\) files and enables you to download the SnapLogic WAR files. To allow access to S3, the IP address range is 52.216.0.0/15 per the official [AWS documentation](https://ip-ranges.amazonaws.com/ip-ranges.json).
* We strongly recommend that you to enable S3 access on JCC \(data processing\) nodes and FeedMaster nodes.
* For Cloudplex IP addresses outside the US region, you can use either the [Snaplex Monitoring API request for REST clients](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/1438923#SnaplexMonitoringAPIs-UsingRESTClients) or the **Health** tab in SnapLogic **Dashboard** \(see the following image\) to retrieve the external IP address.

Update your IP allowlist to include all the IP addresses in the following tables per your requirement.

### Inbound traffic to SnapLogic Platform <a id="Inbound-traffic-to-SnapLogic-Platform"></a>

You need to add the given IP addresses to your allowlist only if your network restricts outbound traffic.

| **SnapLogic Environment** | **Domain** |  |
| :--- | :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>SnapLogic Environment</b>
      </th>
      <th style="text-align:left"><b>Domain</b>
      </th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Production Platform</td>
      <td style="text-align:left">
        <ul>
          <li><a href="http://uat.elastic.snaplogic.com/">elastic.snaplogic.com</a>
          </li>
          <li><a href="http://uat-tcp.elastic.snaplogic.com/">tcp.elastic.snaplogic.com</a>
          </li>
          <li>*.<a href="http://snaplogic.io/">snaplogic.io</a>
          </li>
        </ul>
      </td>
      <td style="text-align:left">
        <ul>
          <li>52.11.8.103/32</li>
          <li>34.208.181.167/32</li>
          <li>52.10.35.99/32</li>
          <li>52.36.97.11/32</li>
          <li>52.25.90.203/32</li>
          <li>34.210.197.128/32</li>
          <li>52.12.92.65/32</li>
          <li>3.220.248.243/32</li>
          <li>3.220.248.158/32</li>
          <li>54.92.192.251/32</li>
          <li>54.157.253.74/32</li>
          <li>18.235.232.49/32</li>
          <li>50.16.206.60/32</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">UAT Platform</td>
      <td style="text-align:left">
        <ul>
          <li><a href="http://uat.elastic.snaplogic.com/">uat.elastic.snaplogic.com</a>
          </li>
          <li><a href="http://uat-tcp.elastic.snaplogic.com/">uat.tcp.elastic.snaplogic.com</a>
          </li>
          <li>*.<a href="http://snaplogic.io/">snaplogic.io</a>
          </li>
        </ul>
      </td>
      <td style="text-align:left">
        <ul>
          <li>52.39.163.113/32</li>
          <li>52.32.143.155/32</li>
          <li>35.163.6.133/32</li>
          <li>44.232.154.15/32</li>
          <li>54.245.88.186/32</li>
          <li>34.210.102.144/32</li>
          <li>3.225.35.150/32</li>
          <li>52.87.92.31/32</li>
          <li>34.226.102.107/32</li>
          <li>54.146.10.130/32</li>
          <li>52.206.133.85/32</li>
          <li>52.205.203.252/32</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### Your Cloudplex instances <a id="Your-Cloudplex-instances"></a>

Add the following IP addresses to your allowlist on the required endpoints to enable outbound requests from SnapLogic Cloudplex instances. Here is an [example](https://docs.aws.amazon.com/redshift/latest/mgmt/managing-security-groups-console.html#security-group-modify) of how you can add IP addresses on AWS Redshift.

| **SnapLogic Environment** | **Domain** |  |
| :--- | :--- | :--- |


| **SnapLogic Environment** | **Domain** |  |
| :--- | :--- | :--- |
| Production Platform | [elastic.snaplogic.com](http://uat.elastic.snaplogic.com/) | 34.209.24.34/32 34.208.230.181/32 3.218.75.185/32 3.218.106.208/32  |
| UAT Platform | [uat.elastic.snaplogic.com](http://uat.elastic.snaplogic.com/) | 35.161.252.12/32 34.212.109.28/32 |

#### See Also <a id="See-Also"></a>

* [Defining Network Settings](https://docs-snaplogic.atlassian.net/wiki/spaces/SD/pages/1439269)

