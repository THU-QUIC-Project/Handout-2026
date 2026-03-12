---
icon: lucide/circle-check-big
---



# Evaluation

Your code should generate 2 executable files: `server` and `client`.
They should be able to handle all the following CLI arguments:

```bash
# Run file transfer server and client:
./server --file-lock ./xxx.lock   0.0.0.0:7722 file-transfer --path ./original.bin
./client --file-lock ./xxx.lock 127.0.0.1:7722 file-transfer --path ./output.bin

# Run ping pong server and client:
./server --file-lock ./xxx.lock   0.0.0.0:7722 ping-pong
./client --file-lock ./xxx.lock 127.0.0.1:7722 ping-pong

# Run stream echo server and client:
./server --file-lock ./xxx.lock   0.0.0.0:7722 stream-echo
./client --file-lock ./xxx.lock 127.0.0.1:7722 stream-echo
```

!!! warning

    TODO
