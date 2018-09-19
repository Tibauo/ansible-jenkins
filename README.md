The goal of this project is:
- Install jenkins
- Create admin user


How to:
-------
ansible-playbook playbook.yml -K -e jenkins=true


GET config.xml:
curl http://localhost:8080/job/test/config.xml -u user:user-password 
