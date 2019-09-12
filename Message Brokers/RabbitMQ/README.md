```
curl -i -u username:password -H "content-type:application/json" -XPUT -d "{""durable"":true}" http://localhost:15672/api/queues/%2f/MyQueue
curl -i -u username:password -H "content-type:application/json" -XPUT -d"{""type"":""direct"",""durable"":true}" http://localhost:15672/api/exchanges/%2f/my-new-exchange
curl -i -u username:password -H "content-type:application/json" -XPOST -d"{""routing_key"":""routing_key"",""arguments"":{}}" http://localhost:15672/api/bindings/%2f/e/my-new-exchange/q/MyQueue
```
