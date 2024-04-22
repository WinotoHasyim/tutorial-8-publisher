## How many data your publlsher program will send to the message broker in one run?

publisher program ini akan mengirimkan 5 messages ke message broker dalam satu run karena ada 5 kali pemanggilan p.publish_event dalam function main

## The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

Artinya publisher dan subscriber sama-sama terhubung dengan message broker yang sama. Publisher akan mengirimkan message ke message broker, dan Subcriber akan menerima message tersebut dari message broker. Ini memungkinkan message communication antara publisher dan subscriber

## Running RabbitMQ as message broker.

![Running RabbitMQ](https://i.imgur.com/8CWI5b5.png)

## Sending and processing event.

![Sending and processing event.](https://i.imgur.com/IXNgjpT.png)

Ketika menjalankan subscriber instance menggunakan command cargo run dan kemudian menjalankan publisher menggunakan command yang sama, maka publisher akan mengirimkan 5 message ke message broker dan semua message tersebut akan diterima oleh subscriber