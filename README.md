### Command 1
ansible -i hosts all -m ping
ansible -i hosts all -m copy -a "dest=/home/ec2-user/toto.txt content='Hello xander'"

### Command 2
ansible -i hosts.ini all -m ping
ansible -i hosts.ini all -m copy -a "dest=/home/ec2-user/toto.txt content='Hello xander {{ env }}'"