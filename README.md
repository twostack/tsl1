
# TSL1: A Peer-to-Peer Token Protocol for Bitcoin (draft v0.1)

A purely peer-to-peer token protocol on bitcoin would allow for the creation of novel tokenisation use-cases. The main benefits of such a token protocol would be lost if a trusted third-party is still required to provide double-spend protection of the tokens. I propose a solution to the double-spend problem for non-native tokens which benefit from the same double-spend protections as bitcoin’s native accounting units. Wallets establish direct connections to one another by participating in a peer-to-peer overlay network separate from that of the bitcoin nodes. Tokens are transmitted in an [SPV manner](cite)(Simplified Payment Verification) between wallet peers. Wallets are recommended to simultaneously act as both headers-only SPV nodes within the bitcoin P2P network, and full peering nodes within a P2P overlay network. The P2P overlay network will facilitate direct wallet-to-wallet communications, and the bitcoin network will provide settlement and finality of the token transfers.

# Overview

This repository is currently in early alpha. All source code is meant for technical review, and should not be used in production. 
The source code under contracts folder is Apache V2.0 licensed. 

The author retains and reserves all rights in the draft PDF whitepaper titled "TSL1: A Peer-to-Peer Token Protocol for Bitcoin (draft v0.1)".

The protocol described in this repository is to the best of the author's knowledge not patent-encumbered, and the author has no intention to ever patent any of this work. Please refer to the details of the Apache License V2.0 for appropriate licensing and use-rights.  
