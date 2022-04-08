FROM docker.elastic.co/logstash/logstash:8.2.1

#Removes Sample Logstash Conf from Image.
RUN rm -f /usr/share/logstash/pipeline/logstash.conf

#Add will Copy files or Folders from [src] to [dest]
ADD pipeline/ /usr/share/logstash/pipeline/
ADD config/ /usr/share/logstash/config/