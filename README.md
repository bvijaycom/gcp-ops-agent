# install Ops Agent  in Google Cloud
# gcp-ops-agent

# each tasks create separate terrform scripts

Task 1 :

- 1. Create new windows VM in GCP
- 2. Login to newly created Vwindows VM
- 3. Install OPS Agent 
- 4. Copy the windows config file [find the windows ops agent config file in this repo]
- 5. Restart the OPS Agent service

Task 2 :

- 1. Create new Linux VM in GCP
- 2. Login to newly created Linux VM
- 3. Install OPS Agent 
- 4. Copy the Linux config file [find the linux ops agent  file in this repo]
- 5. Restart the OPS Agent service


Task 3 :

- 1. Login to all exisating windows servers using admin service account
- 3. Install OPS Agent in that project all windows servers
- 4. Copy the windows config file [find the windows ops agent config file in this repo] in all windows servers
- 5. Restart the OPS Agent service

Note : in this tasks : you need to have a file where you can mention all the windows server name or project name

Task 4 :

- 1. Login to all exisating linux servers using admin service account
- 3. Install OPS Agent in that project all linux servers
- 4. Copy the linux config file [find the windows ops agent config file in this repo] in all windows servers
- 5. Restart the OPS Agent service

Note : in this tasks : you need to have a file where you can mention all the linux  server name or project name

# sample ops agent repo terraform

- https://github.com/terraform-google-modules/terraform-google-cloud-operations/tree/master/examples
- https://registry.terraform.io/modules/terraform-google-modules/cloud-operations/google/latest/submodules/agent-policy

# for your better understanding - Installing OPS Agent via CLI

- https://cloud.google.com/stackdriver/docs/solutions/agents/ops-agent/installation
