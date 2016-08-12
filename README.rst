Make willemt/raft async and batch handle request.
In 3 node raft cluster, max qps is 3.3w/s(msg size is 1KB) in common SATA disk with ext3 fs(4K block size).
