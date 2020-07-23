# Launch Cassandra DB
Install Cassandra. [**Apache Cassandra**](https://cassandra.apache.org/)  is an open source, distributed NoSQL database that began internally at Facebook and was released as an open-source project in July 2008. 
## Requirements
Use only on Ubuntu 18

## Configuration
First steps, you need to configure the hosts file, located in the root folder. In this file, you have to configure  **public IPs** for each cassandra host (We used one hosts)
Second step configure the IPs for the seed nodes ./roles/cassandra/vars/main.yml 
Last step configure the IPs for the NO seed machines ./roles/cassandra/vars/main.yml 
## Run the playbook
Just execute: ansible-playbook cassandra-db.yml, and wait for the results.

## License
MIT

