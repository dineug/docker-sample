FROM jenkins/jenkins:lts
USER root
RUN curl -fsSL https://get.docker.com/ | sh
RUN usermod -aG docker jenkins
RUN curl -L "https://github.com/docker/compose/releases/download/1.25.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
RUN chmod +x /usr/local/bin/docker-compose
USER jenkins
