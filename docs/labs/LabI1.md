---
icon: lucide/flask-conical
---

# Lab I-1: The QUIC Transport Protocol

## Overview

In this lab, you need to use QUIC packets and frames to create a connection and transfer data
between two endpoints in a lossless network. As our first step, we **skip** almost everything, including cryptographic key generation, transport parameter exchange, connection ID negotiation, and
so on in the QUIC handshake. Our handshake is as simple as both endpoints exchanging an Ini-
tial packet. Though your implementation is still not the standard QUIC, we still call it QUIC for
convenience in this and all lab handouts.

Your QUIC implementation needs to support a ping-pong program. The ping-pong client cre-
ates a connection and sends a ”PING” message and replies a ”PING” message when it receives
a ”PONG” message. It closes the connection after receiving ”PONG” for 10 times. The ping-pong
server sends a ”PONG” message whenever it receives a ”PING” message. We have provided the
ping-pong program for you, and you need to implement all interfaces described in §3 to make it
work.
