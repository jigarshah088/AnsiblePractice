export AWS_ACCESS_KEY_ID='AKIAT4IWU5QCT75QLDHO'
root@ip-172-31-18-78:/home/ubuntu/ansible# export AWS_SECRET_ACCESS_KEY='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'
root@ip-172-31-18-78:/home/ubuntu/ansible# 


oot@ip-172-31-18-78:/home/ubuntu/ansible# ansible-inventory -i demo.aws_ec2.yml  --graph
@all:
  |--@aws_ec2:
  |  |--ec2-16-171-234-242.eu-north-1.compute.amazonaws.com
  |  |--ec2-51-20-122-204.eu-north-1.compute.amazonaws.com
  |  |--ec2-51-21-127-118.eu-north-1.compute.amazonaws.com
  |--@ungrouped:
root@ip-172-31-18-78:/home/ubuntu/ansible# 
