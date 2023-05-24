# Sample ELK stack

Sample ELK stack setup based on the tutorial at https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose

## Querying Elasticsearch

1. Retrieve elasticsearch cert by running `./get-cert.sh`
2. Run `curl --cacert /tmp/ca.crt -u elastic:changeme https://localhost:9200`