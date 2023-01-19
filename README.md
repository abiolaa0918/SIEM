# SIEM
Built a basic SIEM using Docker Compose and the Elastic Stack, Nginx web proxy, and a test web application.

Steps:

Create a new directory for your project and navigate to it in the terminal.

Create a new file named "docker-compose.yml" in the project directory.

In the "docker-compose.yml" file, define the services for Elasticsearch, Logstash, Kibana, Nginx, and the test web application.

Create a new file named "logstash.conf" in the project directory.

In the "logstash.conf" file, define the configuration for Logstash to parse the logs from the test web application and send them to Elasticsearch.

Use Docker Compose to start the services.

"docker-compose up"
