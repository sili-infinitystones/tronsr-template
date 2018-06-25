The supernode will be hosted on a multi-cloud hybrid platform, which is developed in-house. It will allow us to seamlessly migrate the service any major cloud provider and scale along with the traffic growth. The largest instance available to date is:

Azure M series 
CPU: 128 Core 
RAM: 3.8 TB 
SSD: 4 TB 

In addition to the hardware expansion, the serving platform will have the following key features:

####Reliability: With a hybrid platform, we will set up multi-zone replication to achieve 99.995% availability. Monitoring and alerting systems (e.g. stackdriver) will be online for 7x24. The database will be backed up to a separate storage on a daily basis.

####Security: All internal data transfers will be encrypted. We will enable hardened JVM and OS image and also ensured the subscription of CVEs. All systems will be patched within 24 hours if there is any upstream fixes. We will enable secure boot or measured boot (when provided by the cloud provider).


