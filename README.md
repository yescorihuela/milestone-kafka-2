# milestone-kafka-2

Clone the project from milestone 1 => https://github.com/yescorihuela/microservices-kafka-milestone-1

Then:

make kafka/docker/up
make kafka/topic/create topic_name=OrderReceived

Clone and run this project with `go run main.go`

Check endpoint `localhost:3000/order-received` with http verb POST and payload `{"content": "what-ever-you-want"}`
