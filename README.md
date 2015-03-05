# Requirements
* An environment with ansible installed
* An aws account with an IAM User with admin access policy and an ssh-key 

# Setup 
* Create the vars/aws-creds.yml with ansible-vault 
* Copy the file aws-creds.yml.example and replace the XXX with the access key and secret key of your IAM USER

# Run It

ansible-playbook provision.yml --vault-password-file=path_to_file or --ask-vault-pass
