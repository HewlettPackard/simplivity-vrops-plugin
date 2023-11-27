# VMware vRealize Operations Manager for HPE SimpliVity

VMware vRealize Operations for HPE SimpliVity provides integrated and highly automated performance, capacity, configuration compliance, and cost management tools to the vRealize Operations custom GUI. The software uses the VMware®’s analytics engine that analyzes what is normal and then applies that baseline to a dynamic server environment. For information on vRealize Operations, see VMware vRealize Operations Enterprise documentation at docs.vmware.com/en/vRealize-Operations-Manager/index.html. When the VMware vRealize Operations for HPE SimpliVity is installed, the Custom HPE SimpliVity Dashboards is added to the vRealize Operations custom GUI. The HPE SimpliVity Dashboard allows you to monitor resources which are HPE SimpliVity specific and not part of the stock vROps suite. The attributes that can be monitored include the performance and capacity related data like compression ratios etc. which are specific to HPE SimpliVity. The analytics engine allows for proactive monitoring of the HPE SimpliVity resource environment and indicates the state of the resources. The analytics engine also provides for proactive prediction which can determine the point in the future when a resource will reach a predefined critical level.

## Management pack versions
### v1.5.0
  - This version supports vROps 8.12.0 and below, and Omnistack versions 4.1.0 and below.
  - Added additional fields to Host Metrics.
  - Please check out the [Release Notes](https://github.com/HewlettPackard/simplivity-vrops-plugin/releases/tag/v1.5.0) here.
  
### v1.4.0
  - This version supports vROps 8.3.0 and below, and Omnistack versions 4.1.0 and below.
  - New feature to choose to avoid data collection of virtual machines and backups from configuration page.
  - Fixes the limit issue showing more than 500 virtual machines and backups.
  - Please check out the [Release Notes](https://github.com/HewlettPackard/simplivity-vrops-plugin/releases/tag/v1.4.0) here.

#### Update as of July'23
  - This version of MP is tested on VMware vROps 8.10 and HPE SimplVity 4.3.0, and is found to be compatible without any issues. Hence, the support of this version of the MP is extended to VMware vROps 8.10 and below, and HPE SimpliVity 4.3.0 and below.

### v1.3.0
  - This release adds support for vROps 8.1. The management pack supports vROps 8.1 and omnistack versions 4.0.1 and below.
  - Updated the User Guide and Demo video for the management pack.
  - Please check out the [Release Notes](https://github.com/HewlettPackard/simplivity-vrops-plugin/releases/tag/v1.3.0) here.

### v1.2.0
  - This release adds support for SimpliVity MVA. The management pack supports vROps 8.0 and omnistack versions 4.0.1 and below.
  - Please check out the [Release Notes](https://github.com/HewlettPackard/simplivity-vrops-plugin/releases/tag/v1.2.0) here.

### v1.1.0
  - This release adds support for vROps 8.0. The management pack supports vROps 8.0 and omnistack versions 4.0.0 and below.
  - Please check out the [Release Notes](https://github.com/HewlettPackard/simplivity-vrops-plugin/releases/tag/v1.1.0) here.

### v1.0.0
  - This release adds support for vROps 7.5. The management pack supports vROps 7.5 and omnistack versions 3.7.5 and below.
  - Please check out the [Release Notes](https://github.com/HewlettPackard/simplivity-vrops-plugin/releases/tag/v1.0.0) here.
  
  **Please note that the certification of the management pack is still under process, but users can use the MP as of now and can update it accordingly in the future.

## Installation

Please refer the [Video Demo](https://www.youtube.com/watch?v=wIppCt_ay6Y) or the [User Guide](https://github.com/HewlettPackard/simplivity-vrops-plugin/blob/master/vROps%20For%20HPE%20Simplivity%20-%20User%20Guide.pdf) for detailed steps on how to install the MP.

## Metrics supported and Default Dashboards

The list of common metrics supported for all the HPE SimpliVity objects are:
  ### Capacity
  - Allocated Capacity
  - Capacity Savings
  - Compression Ratio
  - Deduplication Ratio
  - Efficiency Ratio
  - Free Space
  - Local Backup Capacity
  - Remote Backup Capacity
  - Used Capacity
  - Used Logical Capacity
  - Stored Compressed Data
  - Stored Uncompressed Data
  - Stored Virtual Machine Data

  ### Performance
  - Throughput Write
  - Throughput Read
  - Latency Read
  - Latency Write
  - Iops Read
  - Iops Write

A more detailed list of all the metrics and the default dashbaords which come as part of the management pack can be found in [User Guide](https://github.com/HewlettPackard/simplivity-vrops-plugin/blob/master/vROps%20For%20HPE%20Simplivity%20-%20User%20Guide.pdf).

## Updates
Subsequent updates to the MP for newer versions of VMware vROps would be released in the public GitHub site itself and the release information can be found in the release notes.

## Feedback & Feature Requests

If you have needs not being met by the current implementation, please let us know (via a new issue). This feedback is crucial for us to deliver a useful product. Do not assume we have already thought of everything, because we assure you that is not the case.
