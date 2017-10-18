Okay, I commited almost of my work at once, since I did ran the test respectively on each VM.
So to start, I separated the inventories and the playbooks.
On inventories you can find the file used for hosts (hosts.yml)
On playbooks you can find a series of playbooks made for the practice test, every *.yml besides main.yml contain
the tasks needed to run for each point of the practice test. The main.yml only contains the respective includes
for each of the tasks.

For tests I have been using the command "ansible-playbook ~/ansible/playbooks/main.yml -i ~/ansible/inventory/hosts.yml -vvv".

