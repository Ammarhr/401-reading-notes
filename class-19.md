### Message Queuing:
**Message queuing:** allows applications to communicate by sending messages to each other. The message queue provides temporary message storage when the destination program is busy or not connected.

**Message queue** provides an asynchronous communications protocol, which is a system that puts a message onto a message queue and does not require an immediate response to continuing processing

#### Message:
- **message** is the data transported between the sender and the receiver application; it's essentially a byte array with some headers at the top.
- **queue**is a line of things waiting to be handled, starting at the beginning of the line and processing it in sequential order.
- **event** is What event has happened during transportimg data (delete, add, update or connection lost ...etc)
- **Payload** is tha data that associated with the event.

