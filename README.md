# FakeLA

This is my "ground zero" for some new tools I'm learning marked in **bold**.

- **Filebeat**
- Apache
- **Kibana**
- **Elasticsearch**
- Linux
- **Ansible**

FakeLA should serve as a "Log Aggregation and Data Analytics In a Box" when it's done.

It currently props up all services but requires you to set the default index due to a bug in the api that sometimes works and sometimes does not.

# Things you need to have done before you do this:
- Set up DNS name for Kibana
- Set up DNS name for Elasticsearch

If you are testing on a single local VM you can easily do this with your
hosts file.

Warning:  Due to a sysctl bug in Ubuntu 16.04 LTS caused by a change in procfs tree schema you will absolutely have to restart on a fresh install for production deployments.

This version works around numerous bugs in Ansible, Elasticsearch, sysctl, and kibana.
