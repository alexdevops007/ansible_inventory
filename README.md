### Command
ansible -i hosts all -m ping
ansible -i hosts all -m copy -a "dest=/home/ec2-user/toto.txt content='Hello xander'"