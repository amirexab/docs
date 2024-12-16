
# Herz - Customer Support

### [Amir Mohammed](https://www.linkedin.com/in/amir-mohammed-7b1306128/)

## Usecases

 - Connect with web socket
 - Listen to incoming messages
 - Send message
 - Jump to down FAB

## Demo

![demo](https://imgur.com/7NynZ6s.gif)


## Diagrams

 - Connect with web socket

![connect](https://imgur.com/gQ3PT7F.png)


 - Listen to incoming messages
 
 ![lisen](https://imgur.com/YU28q0n.png)
 
 - Send message
 
![send](https://imgur.com/0Mg6T0I.png)
 
 - Jump to down fab

![jump](https://imgur.com/8kYnvpd.png)

## API Reference

#### Get all messages

```http
  GET /v1/chats
```

#### Send message

```http
  GET /v1/chats
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `message` | `string` | **Required**. text of message |


## Web Socket Reference

#### Connect

```http
  wss://amirmohammed.com/app/key?protocol=7&client=js&version=8.4.0-rc2&flash=false
```

#### Subscribe to channel

```http
{
    "event": "pusher:subscribe",
    "data": {"channel": "chat-$userID"}
}
```

## Used By

This Feture is used by the following projects:

- Herz
- Post

