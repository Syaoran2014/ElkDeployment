##ToDo 
    - [ ] Make Pretty 


##h2 What I did/What I learned

Made New VNet in Azure to support Elk VM

Added Peer Connection between ElkVNet and RedTeamVNet

Deployed new B2s_v3 VM for Elk Server

Enabled SSH from JumpBox into the Newly Deployed VM

Made `ElkBook.yml` to Setup the Deployed Elk VM (Link file here)
Shown that Elk and Version is running

Refined The Network security group to allow traffic to the elk app from personal IP

Created and Ran `InstallFilebeat.yml` to install and configure filebeat for Elk Logdata.

Checked Elk Web GUI to ensure Files were being received.

Created and Ran `installMetricbeat.yml` to install and configure metricbeat for Elk Metrics

Checked Elk Web GUI to ensure Files were being received.