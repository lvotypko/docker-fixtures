#
# Container for running Java processes
#

# cf. SshdContainer/Dockerfile
FROM jenkins/sshd:5fed1a40e5de

RUN apt-get update && \
    apt-get install --no-install-recommends -y \
        software-properties-common \
        openjdk-8-jre-headless \
        openjdk-8-jdk-headless \
        curl \
        ant \
        maven
