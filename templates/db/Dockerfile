# Use official MySQL image
FROM mysql:8.0

# Copy initialization script
COPY init.sql /docker-entrypoint-initdb.d/

# Expose MySQL port
EXPOSE 3306
