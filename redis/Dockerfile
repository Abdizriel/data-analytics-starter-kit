# Set redis base image
FROM redis

# File Author / Maintainer
MAINTAINER Marcin Mrotek

# Copy custom configuration file from the config directory
COPY config/redis.conf /etc/redis/redis.conf

# Start redis
CMD ["redis-server", "/etc/redis/redis.conf"]