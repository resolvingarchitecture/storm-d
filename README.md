# Storm-D
Decentralized Storm written in Rust!

Using Storm's [GitHub](https://github.com/apache/storm) as guidance.

Storm-D is a decentralized realtime computation system. Similar to how Hadoop provides a set of general primitives for doing batch processing, 
and how Apache Storm provides a means for doing realtime computation in a distributed means, Storm-D provides a set of general primitives for doing realtime computation
using decentralized peers. Peers offer some level of processing at configured times within a d-cluster.

A d-cluster is a group of peers that have agreed to share a processing load. 
They, together as a whole, get compensated by end users in BTC/XMR.

## Background

Storm-D is the middle of evaluating how best to decentralize Apache Storm. Apache Storm is an amazing vehicle
for real-time processing but mainly focused on using within a data-center like Amazon's AWS. Decentralized networks
today are largely focused on P2P communications like messengers as the infrastructure is not yet in place to support
large-scale Big Data type projects on decentralized networks. Storm-D aims to change this. And Rust is the perfect
language to ensure performance while maintaining memory safety.

## Requirements

* Rust 1.42