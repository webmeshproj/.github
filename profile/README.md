# What is Webmesh?

Webmesh is a simple, distributed, and zero-configuration WireGuard™ mesh solution for Linux, FreeBSD, macOS, and Windows. It allows for easily creating a mesh network between multiple hosts, and provides a simple API for managing the network. It is designed to be easy to use, and to work well with existing network infrastructure.

Webmesh is not a VPN, but rather a mesh network. It is designed to be used in conjunction with existing network infrastructure, and not as a replacement for it. It is also not a replacement for WireGuard™, but rather a way to manage a WireGuard™ mesh network. Connections are made into the network via direct links or over ICE (WebRTC) connections. It differs from other WireGuard™ management solutions in that:

- It is designed to be distributed and extensible, relying on no single controller or database.
- A plugin API is provided for adding additional functionality, such as a distributed database for storing the mesh state or additional authentication mechanisms.
- An application API is also provided for interacting with the mesh network, and is used by the CLI and GUI applications.

The main code can be found in the [webmesh](https://github.com/webmeshproj/webmesh) repository.

More information and documentation is available at the project website: https://webmeshproj.github.io.

**This project is not yet ready for production use, but I hope to rapidly get there**
