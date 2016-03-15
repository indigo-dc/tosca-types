# INDIGO TOSCA examples

These directory has some examples to specify features needed in the INDIGO project that uses the defined custom types: 

* web_mysql_tosca.yaml: TOSCA test for launching a typical example of a two tier application with an
  Apache web server and a MySQL DB
* cellar_webapp_mem.yaml: TOSCA test for launching the Wine Cellar Application (PHP Version) (https://github.com/ccoenraets/wine-cellar-php) using the simple in memory DB with a single web server node.
* cellar_webapp_mysql.yaml: TOSCA test for launching the Wine Cellar Application (PHP Version) (https://github.com/ccoenraets/wine-cellar-php) as an example of a two tier application with an Apache web server and a MySQL DB.
* elastic_cluster.yaml: TOSCA test for launching a Virtual Elastic Cluster. It will launch a single front-end that will be in change of managing the elasticity using the specified LRMS (torque, sge, slurm and condor) workload.
* galaxy_tosca.yaml: TOSCA test for launching a Galaxy Server also configuring the bowtie2 tool using Galaxy Tool Shed.
* galaxy_elastic_cluster.yaml: TOSCA test for launching a Galaxy Server over an Virtual Elastic Cluster.
* indigo_jobs.yaml: TOSCA examples for specifying Chronos and Marathon jobs to enable the   specification of applications and services in INDIGO.
* mesos_cluster.yaml: TOSCA example for specifying a Mesos Cluster.
* node_with_image.yaml: TOSCA example for launching compute node with a specified image and getting as an output the IP and SSH credentials to access.