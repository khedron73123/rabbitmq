FROM rabbitmq:3-management
RUN rabbitmq-plugins enable rabbitmq_stomp
RUN rabbitmq-plugins enable rabbitmq_mqtt
RUN rabbitmq-plugins enable rabbitmq_web_mqtt
EXPOSE 4369 5671 5672 15691 15692 25672 1883 15671 15672 15675
CMD ["rabbitmq-server"]
