# Set kibana base image
FROM kibana:latest

# File Author / Maintainer
MAINTAINER Marcin Mrotek

# Get OS updates and install networking utility
RUN apt-get update && apt-get install -y netcat

# Cache container entrypoint and give it executable permission
COPY entrypoint.sh /tmp/entrypoint.sh
RUN chmod +x /tmp/entrypoint.sh

# Install Sense plugin for Kibana
RUN kibana plugin --install elastic/sense

# Start Kibana when ElasticSearch container is ready
CMD ["/tmp/entrypoint.sh"]