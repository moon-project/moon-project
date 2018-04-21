## Moon-Project

An Ethereum Foundation project with the mission of building a platform for fully decentralized applications (from back to front-end), using insights from type theory and formal methods to prove and verify security properties of those apps. Think of Chrome, except with Agda instead of JavaScript, Ethereum instead of centralized APIs, and IPFS instead of static website servers.

It was initially designed as a browser for Ethereum, but, because of the incompatibility of the EVM with functional programs (even the simplest ones are prohibitively expensive to run there), I decided to temporarily make this project its own minimal chain. This allows us to design a specialized VM and enables faster development and experimentation cycles. Once the ideas of this project are validated, we can discuss how to integrate those with Ethereum (new opcodes? shards? multi-VMs?).

### Main Components

- [Howled](): an ever-growing decentralized acyclic graph of just data. 

- [AVM](): Abstract Virtual Machine, a virtual machine optimized for functional programs.

- [Formality](): a high-level language that runs on the AVM.

- [Cedille-Core](): the core type-theory behind Formality. 

- [Refl](): a platform (browser) for decentralized applications.

It also uses [IPFS]() as a decentralized store, and [Ethereum]() as a decentralized computer.

Note: all those names are possibly silly (because I needed to chose something) and accepting suggestions.
