# airflow-dags-container

Add Airflow DAGS, DAG requirements (outside of regular Airflow requirements), and DAG tests to your [Ansible Container](https://github.com/ansible/ansible-container) project.

Note: this role does not install Airflow or any Airflow dependencies.  This role is designed to be used with [this image](https://github.com/puckel/docker-airflow).

```
# Set the working directory to your Ansible Container project root
$ cd myproject

# Install the service
$ ansible-container install ansible.airflow-dags-container
```

