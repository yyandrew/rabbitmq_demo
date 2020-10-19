### What's it

A simple demo of rabbitmq

### How to use
1. Install bunny

```
gem install bunny
```

2. Produce message to **hello** queue

```
ruby sender.rb
```

3.  Consume the message of **hello** queue

```
ruby received.rb
```

Use `rabbitmqctl list_queues` to check the queue
