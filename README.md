# ApacheHadoop-ResourceManager using webscraping
Get details of yarn memory and vcores usage and other details from the YARN page using webscraping with Python

# Other way of getting resourses details by using offcial api of ApacheHadoop.
https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/ResourceManagerRest.html

API link - http://10.237.180.91:8088/ws/v1/cluster/metrics

o/p:
<clusterMetrics>
<appsSubmitted>26</appsSubmitted>
<appsCompleted>26</appsCompleted>
<appsPending>0</appsPending>
<appsRunning>0</appsRunning>
<appsFailed>0</appsFailed>
<appsKilled>0</appsKilled>
<reservedMB>0</reservedMB>
<availableMB>532480</availableMB>
<allocatedMB>0</allocatedMB>
<reservedVirtualCores>0</reservedVirtualCores>
<availableVirtualCores>288</availableVirtualCores>
<allocatedVirtualCores>0</allocatedVirtualCores>
<containersAllocated>0</containersAllocated>
<containersReserved>0</containersReserved>
<containersPending>0</containersPending>
<totalMB>532480</totalMB>
<totalVirtualCores>288</totalVirtualCores>
<totalNodes>7</totalNodes>
<lostNodes>0</lostNodes>
<unhealthyNodes>0</unhealthyNodes>
<decommissioningNodes>0</decommissioningNodes>
<decommissionedNodes>0</decommissionedNodes>
<rebootedNodes>0</rebootedNodes>
<activeNodes>7</activeNodes>
<shutdownNodes>0</shutdownNodes>
</clusterMetrics>
