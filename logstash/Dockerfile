# Set logstash base image
FROM logstash:latest

# File Author / Maintainer
MAINTAINER Marcin Mrotek

# Copy custom configuration file from the current directory
COPY /config/logstash.conf /etc/logstash/conf.d

# Start logstash
CMD ["logstash", "-f", "/etc/logstash/conf.d/logstash.conf"]