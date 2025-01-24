# pure-tf-from-toolkit
Testing of using modules individually without cluster toolkit

 In this repo, we use the GCP Cluster-toolkit repo terraform modeules to create a simple Slurm cluster. 

 source of the Cluster toolkit code / modules: 
 
 https://github.com/GoogleCloudPlatform/cluster-toolkit

 Method: Just copy all the modeules in use from the main.tf

filestore                
schedmd-slurm-gcp-v6-controller  
schedmd-slurm-gcp-v6-nodeset-dynamic
schedmd-slurm-gcp-v6-login       
pre-existing-vpc         
schedmd-slurm-gcp-v6-nodeset     
schedmd-slurm-gcp-v6-partition

Then do the normal terraform init and terraform with the terraform.tfvars 
