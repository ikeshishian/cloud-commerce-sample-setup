B2C and B2B Accelerator with OMS.
This contains CEP (Cloud Extension Pack) extensions as well.
For Kyma integration + ApiRegistry, event sending is turned off by default by apiregistryservices.events.exporting=false property. Optionally and before initialization, deployment.api.endpoint property should be set to a server url reachable by kyma instead of https://localhost:9002.
 Platform Setup:
   1. Setup platform using command ./install.sh -r b2c_b2b_acc_oms_cloud setup -A initAdminPassword=[password]
   2. Initialize platform using command ./install.sh -r b2c_b2b_acc_oms_cloud initialize -A initAdminPassword=[password]
   3. Start platform using command ./install.sh -r b2c_b2b_acc_oms_cloud start
