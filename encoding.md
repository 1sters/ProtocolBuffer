# Encoding

ref: https://developers.google.com/protocol-buffers/docs/encoding

This document describes the binary wire format for protocol buffer messages. You don't need to understand this to use protocol buffers in your applications, but it can be very useful to know how different protocol buffer formats affect the size of your encoded messages.

## A Simple Message

Let's say you have the following very simple message definition:

```
message Test1 {
  required int32 a = 1;
}
```