# ansible-tutorial
 
Run
    ansible-playbook -i <inventory_filename> <playbook_filename>.yaml

Adhoc Task - one-off tasks across (parts of) the fleet
    ansible --help |less
    ansible-doc command
    i.e.  ansible -i webapp host1 -m command -a "uname -r"