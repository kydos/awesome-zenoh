# Awesome Zenoh [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome projects, libraries, tools, and resources built with or for [Zenoh](https://zenoh.io) – the protocol unifying data in motion, data at rest, and computations.

Zenoh is designed to provide a unified abstraction for pub/sub, query/reply, and distributed storage, scalable from microcontrollers to the cloud.

---

## Contents

- [Official Resources](#official-resources)
- [Protocol Implementations](#protocol-implementations)
- [Official API](#official-api)
- [Community API](#community-api)
- [Tools](#tools)
- [Connectors](#connectors)
- [ROS 2](#ros-2)
- [Robotics](#robotics)
- [AI](#ai)
- [Command Line Tool](#command-line-tool)
- [Data Flow Programming](#data-flow-programming)
- [Autoware](#autoware)
- [Eclipse SDV](#eclipse-sdv)
- [Tutorials & Examples](#tutorials-and-examples)
- [Talks & Articles](#talks-and-articles)
- [Community Projects](#community-projects)
- [Contributing](#contributing)

---

## Official Resources

- 🌐 [Zenoh Website](https://zenoh.io)
- 🧬 [Zenoh GitHub Organization](https://github.com/eclipse-zenoh)
- 📘 [Zenoh Documentation](https://zenoh.io/docs/getting-started/first-app/)
- 🎓 [Zenoh Tutorial](https://speakerdeck.com/kydos/collections/zenoh-tutorial)

---

## Protocol Implementations

- [`zenoh`](https://github.com/eclipse-zenoh/zenoh) – Official Rust implementation of Zenoh.
- [`zenoh-pico`](https://github.com/eclipse-zenoh/zenoh-pico) – Lightweight implementation in C for MCUs and embedded platforms.

---

## Official API

- [`zenoh-rs`](https://github.com/eclipse-zenoh/zenoh) – API for the Rust implementation of Zenoh
- [`zenoh-python`](https://github.com/eclipse-zenoh/zenoh-python) – Python bindings for Zenoh Rust.
- [`zenoh-kotlin`](https://github.com/eclipse-zenoh/zenoh-kotlin) - Kotlin bindings for Zenoh Rust
- [`zenoh-c`](https://github.com/eclipse-zenoh/zenoh-c) – C-bindings for Zenoh Rust.
- [`zenoh-cpp`](https://github.com/eclipse-zenoh/zenoh-cpp) – C-bindings for Zenoh Rust and Zenoh-Pico.
- [`zenoh-ts`](https://github.com/eclipse-zenoh/zenoh-ts) – TypeScript implementation of remote Zenoh API
- [`zenoh-java`](https://github.com/eclipse-zenoh/zenoh-java) – Java/Kotlin bindings for Zenoh Rust.

---

## Community API

- [`zenoh-jl`](https://github.com/BenChung/Zenoh.jl) - Julia binding for Zenoh Rust.
- [`zenoh-csharp`](https://github.com/sanri/zenoh-csharp) - Zenoh-CS provides the common interface of Zenoh-C.
- [`zenohex`](https://github.com/biyooon-ex/zenohex) - Elixir binding for Zenoh Rust.

---

## Tools

- [`wireshark`](https://github.com/eclipse-zenoh/zenoh-dissector) - Zenoh protocol dissector for Wireshark.
- [`zenoh-hammer`](https://github.com/sanri/zenoh-hammer) - Zenoh ui tool. Convenient for simple zenoh network communication testing.

---

## Connectors

- [`zenoh-plugin-ros2dds`](https://github.com/eclipse-zenoh/zenoh-plugin-ros2dds) – Bridge between Zenoh and DDS-based ROS2.
- [`zenoh-plugin-dds`](https://github.com/eclipse-zenoh/zenoh-plugin-dds) – Bridge between Zenoh and DDS.
- [`zenoh-plugin-rest`](https://github.com/eclipse-zenoh/zenoh-plugin-rest) – RESTful API plugin for Zenoh.
- [`zenoh-bridge-mqtt`](https://github.com/eclipse-zenoh/zenoh-bridge-mqtt) – Bridge between MQTT and Zenoh.
- [`liason`](https://github.com/RISE-Maritime/liaison) - Simplify the sharing of Functional Mock-up Units (FMUs) both within and between organizations.
- [`gatorcat`](https://github.com/kj4tmp/gatorcat) - EtherCAT maindevice written in Zig with Zenoh connectivity.

---

## ROS 2

- [`rmw_zenoh`](http://github.com/ros2/rmw_zenoh) – Zenoh-based middleware implementation for ROS 2.
- [`ros-z`](http://github.com/zettaScaleLabs/ros-z) - Zenoh-native ROS 2 implementation.
- [`pico-ros`](https://github.com/pico-ros) - Lightweight ROS 2 implementation designed for resource-constrained devices, Built on top of [zenoh-pico](https://github.com/eclipse-zenoh/zenoh-pico)
- [`zenoh-ros-type`](https://github.com/evshary/zenoh-ros-type) - Common ROS 2 message types for Zenoh in Rust.
- [`zenoh-ros-type-python`](https://github.com/evshary/zenoh-ros-type-python) - Common ROS 2 message types for Zenoh in Python.

---

## Robotics

- [`keelson`](https://github.com/RISE-Maritime/keelson) - Maritime best practices API specification designed for building distributed maritime robotics applications on top of the Zenoh communication protocol.

---

## AI

- [`om1`](https://github.com/OpenmindAGI/OM1) - Openmind's OM1 is a modular AI runtime that empowers developers to create and deploy multimodal AI agents seamlessly across both digital environments and physical robots.
---

## Command Line Tool

- [`zenoh-cli`](https://github.com/RISE-Maritime/zenoh-cli) – A Python-based commandline tool to interact with a Zenoh Session.
- [`zsak`](http://github.com/kydos/zsak) - Zenoh Swiss Army Knife, a Rust-based commandline tool that can be used to learn Zenoh.

---

## Data Flow Programming

- [`zenoh-flow`](https://github.com/eclipse-zenoh/zenoh-flow) – A data-flow orchestration engine powered by Zenoh.
- [`dora-rs`](https://github.com/dora-rs/dora) – dora-rs is a framework to run realtime multi-AI and multi-hardware applications.

---

## Autoware

- [`autoware_rmw_zenoh`](https://github.com/evshary/autoware_rmw_zenoh) - Tutorial for running Autoware with [rmw_zenoh](http://github.com/ros2/rmw_zenoh).
- [`zenoh_carla_bridge`](https://github.com/evshary/zenoh_carla_bridge) - Bridge Autoware and Carla with Zenoh.
- [`zenoh_autoware_fms`](https://github.com/evshary/zenoh_autoware_fms) - Project to showcase an Autoware fleet management system with Zenoh.
- [`zenoh_autoware_v2x`](https://github.com/evshary/zenoh_autoware_v2x) - Project to showcase an Autoware V2X scenario with Zenoh.

---

## Eclipse SDV

- [`uprotocol`](https://github.com/eclipse-uprotocol) - Project to enable connecting automotive applications and services anywhere.
  - [`up-transport-zenoh-rust`](https://github.com/eclipse-uprotocol/up-transport-zenoh-rust) - Rust implementation.
  - [`up-transport-zenoh-cpp`](https://github.com/eclipse-uprotocol/up-transport-zenoh-cpp) - C++ implementation.
- [`fleet-management`](https://github.com/eclipse-sdv-blueprints/fleet-management) - A close to real-life showcase for truck fleet management where trucks run an SDV software stack so that logistics fleet operators can manage apps, data and services for a diverse set of vehicles.
- [`service-to-signal`](https://github.com/eclipse-sdv-blueprints/service-to-signal) - The blueprint showcases how to use the Eclipse uProtocol to make a vehicle service available in a vehicle network and connect the service implementation with potential physical hardware

---

## Tutorials and Examples

- [Zenoh Examples (Official)](https://github.com/eclipse-zenoh/zenoh/tree/main/examples)
- [Zenoh Webinar Slides](https://speakerdeck.com/kydos/collections/zenoh-webinar-ad-2025)
- [Zenoh Programming Book (WIP)](https://github.com/kydos/zenoh-book)

---

## Talks and Articles

- [Zenoh Paper](https://bit.ly/3P0DJ3N)
- [Zenoh Tier-1 ROS 2 Announcement](https://discourse.ros.org/t/ros-2-kilted-kaiju-release/43902)
- [RMW Alternate Report](https://discourse.ros.org/t/ros-2-alternative-middleware-report/33771)

---

## Community Projects

> Help us grow this list! Submit your project via PR or issue.

---

## Contributing

Want to contribute? Just follow these steps:

1. Fork this repo
2. Add your entry in the appropriate section
3. Open a Pull Request!

Please follow the [Awesome List Guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md) when submitting.

---

## License

[Creative Commons Zero v1.0](LICENSE)

---
