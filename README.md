# ZKEnsemble-3Members-EBSDatablocks

This code deploys 3 EC2 machines that form a zookeeper quorum in 3 different AZs. It also deploys EBS block devices in corresponding AZs.

Now, there are a lot more can be improved. Will add more in future.

    * User-script to install jvm, setup zookeeper, EBS block device formatting - to make them usable
    * Data lookup for availability zones to automatically deploy infra in all/required AZs
    * Endpoint registration
    * Metrics integration with AWS prometheus
    * Environment specific configs - In this example, only test environment is used, it can be refined to include QA/UAT/Pre-PROD/PROD environments 
