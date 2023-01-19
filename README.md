# SIEM
Built a basic SIEM using Docker Compose and the Elastic Stack, Nginx web proxy, and a test web application.

Steps:

1. Create a new directory for your project and navigate to it in the terminal.

2. Create a new file named "docker-compose.yml" in the project directory.

3. In the "docker-compose.yml" file, define the services for Elasticsearch, Logstash, Kibana, Nginx, and the test web application.

4. Create a new file named "logstash.conf" in the project directory.

5. In the "logstash.conf" file, define the configuration for Logstash to parse the logs from the test web application and send them to Elasticsearch.

6. Use Docker Compose to start the services.

    "docker-compose up"
