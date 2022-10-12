# Sample Ansible 
# install ansible
# in terminal type (pip3 install ansible)
# put your servers ip(s) in inventory.txt file
# in terminal type ( ansible-playbook -i inventory.txt main.yml --private-key=./any.pem -> any.pem is your ssh key )


# to get your instance ip from aws type (aws ec2 describe-instances    --query 'Reservations[*].Instances[*].PublicIpAddress'    --output text >> inventory )

