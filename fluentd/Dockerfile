FROM fluent/fluentd:v1.12.1-debian-1.0
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--version", "5.0.2"] 
USER fluent
# "--no-rdoc", "--no-ri",