## How many data your publlsher program will send to the message broker in one run?

publisher program ini akan mengirimkan 5 messages ke message broker dalam satu run karena ada 5 kali pemanggilan p.publish_event dalam function main

## The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

Artinya publisher dan subscriber sama-sama terhubung dengan message broker yang sama. Publisher akan mengirimkan message ke message broker, dan Subcriber akan menerima message tersebut dari message broker. Ini memungkinkan message communication antara publisher dan subscriber

## Running RabbitMQ as message broker.

![Running RabbitMQ](https://i.imgur.com/8CWI5b5.png)