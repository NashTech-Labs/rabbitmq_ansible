### What will this role do ?

The above ansible role will install rabbitmq server on the redhat server or instance.

This role can be used to install rabbitmq server on as many machines as you want. Also this role will enable the rabbitmq on the machines.

This role will first download the rabbitmq package and then further install and enable it on the machines.

NOTE: This role will only work on Redhat based linux machines.

#### Variable used in the install_gpu.sh.

- rabbitmq_version=" pass the rabbitmq version you need "
- rabbitmq_rpm= " pass the rabbitmq rpm value "
- rabbitmq_rpm_url= " pass the rabbitmq rpm value "
- rabbitmq_deb= " pass the rabbitmq deb package  "
- rabbitmq_deb_url= " pass the rabbitmq deb url "


### How to run the playbook .

To run the playbook follow the below command:-

`ansible-playbook -i <your inventory file> playbook.yml`

**Note**:-  If you are running on your local system then you don't need to pass inventory file. Just use localhost in hosts of playbook. 