# Class-17

## The Transmission Control Protocol (TCP)

**The Transmission Control Protocol (TCP)**
 - Is widely used by application layer protocols in the Internet Protocol Suite. TCP creates a two way communication between two hosts and provides reliable, ordered, and error checked byte streams between the applications. TCP data transfers manage network congestion and use flow control to limit the rate a sender transfers data to guarantee reliable delivery. Each IP packet between the hosts carries a single TCP Segment. A TCP segment is made up of header and data sections.

**Connection Establishment**
 - The client sends a SYN packet with an random initial sequence number. The server sends a SYN-ACK packet with the acknowledgment number set to one more than the initial sequence number. The client responds with an ACK and an acknowledgment number incremented by one.

**Connection Termination**
 - One end sends a FIN Segment and the other sends an ACK segment followed by a FIN segment. The termination initiation will then respond with an ACK segment.