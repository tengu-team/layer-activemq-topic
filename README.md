# Overview

Apache ActiveMQ ™ is the most popular and powerful open source messaging and Integration Patterns server.

Apache ActiveMQ is fast, supports many Cross Language Clients and Protocols, comes with easy to use Enterprise Integration Patterns and many advanced features while fully supporting JMS 1.1 and J2EE 1.4. Apache ActiveMQ is released under the Apache 2.0 License

This charm will create a Topic on ActiveMQ. This topic will be named after the name of the charm.
The custom [interface](https://github.com/tengu-team/interface-activemq-topic) will then provide the topic name, IP and port.

# Usage

To deploy this charm:

    juju deploy activemq
    juju deploy activemq-topic <topic-name>
    juju add-relation activemq <topic-name>


# Contact Information

 - Sébastien Pattyn <sebastien.pattyn@tengu.io>
