
# Herz - Customer Support

### [Amir Mohammed](https://www.linkedin.com/in/amir-mohammed-7b1306128/)

## Flows

 - Connect with web socket
 - Listen to incoming messages
 - Send message
 - Jumb to down FAB

## Demo

![demo](https://imgur.com/7NynZ6s.gif)


## Diagrams

 - Connect with web socket

![connect](https://imgur.com/gQ3PT7F.png)


 - Listen to incoming messages
 
 ![lisen](https://dgitsa-my.sharepoint.com/personal/a_mohammed_exab_sa/Documents/Diagrams/h-cs-listen.png)
 
 - Send message
 
![send](https://dgitsa-my.sharepoint.com/personal/a_mohammed_exab_sa/Documents/Diagrams/h-cs-send.png)
 
 - Jumb to down fab

![jump](https://dgitsa-my.sharepoint.com/personal/a_mohammed_exab_sa/Documents/Diagrams/h-cs-fab.png)

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


## Web Socket Referenc

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

