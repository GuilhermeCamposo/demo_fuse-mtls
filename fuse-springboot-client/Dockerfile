FROM registry.redhat.io/openjdk/openjdk-11-rhel7:latest
COPY maven/target/*.jar /deployments/
COPY maven/scripts/start.sh /deployments/start.sh
CMD ["sh", "-x", "/deployments/start.sh"]

