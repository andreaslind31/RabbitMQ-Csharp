# RabbitMQ with Csharp
Followed the tutorials with RabbitMQ at the address below with Csharp code
[RabbitMQ tutorials](https://www.rabbitmq.com/getstarted.html)

![This is an image](https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/RabbitMQ_logo.svg/258px-RabbitMQ_logo.svg.png)

## How to :

Open two terminals.
Run the consumer first so that the topology (primarily the queue) is in place:
```
cd Hello-World/Recieve
dotnet run
```
Then run the producer:
```
cd Hello-World/Send
dotnet run
```

This will create 
in Send:
```csharp
Console.WriteLine($" [x] Sent {message}");
Console.WriteLine("Press [enter] to exit.");
```
in Recieve:
```csharp
Console.WriteLine(" [*] Waiting for messages.");
Console.WriteLine($" [x] Received {message}");
Console.WriteLine(" Press [enter] to exit.");
```

