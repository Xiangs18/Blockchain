### Blockchain Introduction
In this article, I’ll make a simple blockchain in less than 50 lines of Python 3 code. It’ll be called SnakeCoin.
We’ll start by first defining what our blocks will look like. 

In blockchain, each block is stored with a timestamp and, optionally, an index. In SnakeCoin, we’re going to store both. And to help ensure integrity throughout the blockchain, each block will have a self-identifying hash. 

Like Bitcoin, each block’s hash will be a cryptographic hash of the block’s index, timestamp, data, and the hash of the previous block’s hash. Oh, and the data can be anything you want.

### Installing required packages

```
import hashlib as hasher
import datetime as date
```

### How to run
* Through Terminal
```
python snakecoin.py
```
