# RabbiTornado

## Introduction

**RabbiTornado** is a Python Tornado Framework based Web Server that implements multi-user chat (think IRC) via WebSockets. The message delivery backend is RabbitMQ... Hence the name RabbiTornado.

## Installation

### Prerequisites

* Python 2.7
* RabbitMQ (<http://www.rabbitmq.com>)
* Tornado Framework (use `sudo easy_install tornado`)
* Pika RabbitMQ module (use `sudo easy_install pika`)



### HOW TO RUN:
1. Ensure that RabbitMQ is running
2. Run the Server by typing `python main.py`
3. This will run the server on port 8888  (edit main.py if you want to change the port)
4. Open up a browser to <http://localhost:8888/>

### Trying to do:
* The Server listening port is in `main.py`
* The rabbit server connection uses an `amqp_url` variable in `main.py`
* The login database is currently hardcoded. So once you log in you remain logged in. 



