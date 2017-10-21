What is an Ethereum message?
----------------------------

tl;dr
^^^^^

Contracts can call other contracts or send Ether to non-contract
accounts by the means of *message calls*. Message calls are similar to
transactions, in that they have a source, a target, data payload, Ether,
gas and return data. In fact, every transaction consists of a top-level
message call which in turn can create further message calls.
