* 20210921: Added requeue to rabbitmq. It's necessary to think about a better solution for resilience though.
* 20210921: Added parameter ResilienceOptions. 
    * The idea is to create give the consumer, that creates the queue, the options of retry quantity and time to retry.
    * Optional parameter
* 20210925: Added retry support for RabbitMQ