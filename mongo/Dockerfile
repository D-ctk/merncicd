# Use the official MongoDB image as base
FROM mongo:latest

# Set up a volume for persistent data (optional)
VOLUME /data/db

# Expose MongoDB's default port
EXPOSE 27017

# Start MongoDB as the container entry point
CMD ["mongod", "--bind_ip", "0.0.0.0"]
