# FakeLA

This is a distribution of:

- Filebeat
- Apache
- Kibana
- Elasticsearch

On

- Linux

With 

- Ansible

Intended for Ubuntu 16.04 LTS targets.

FakeLA is a "Log Aggregation and Data Analytics In a Box" solution.

It currently props up all services but requires you to set the default index due to a bug in the api.

# Prework:
- Set up a DNS entry for Kibana. 
- Set up a DNS entry for Elasticsearch.

I use A records but if you are testing on a single local VM you can easily do this with your hosts file.

# Index Management

For index pruning, I'd recommend checking out my Langolier project:
https://github.com/cmpunches/Langolier
