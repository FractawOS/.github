# FractawOS

FractawOS is an open-source modular system environment built on top of Windows.

Its goal is to provide a customizable operating experience without sacrificing compatibility with Windows applications, drivers, games, development tools, or hardware.

Instead of treating the system as a fixed environment, FractawOS is built around modules, groups, policies, and user-controlled automation.

## Core idea

FractawOS provides the base platform.

Modules extend the platform with specialized capabilities.

Groups allow users to decide when those capabilities should become active.

A group may contain applications, activate one or more modules, and override the policies exposed by those modules.

The system should remain usable even when no optional module is active.

## Official modules

The first official modules are:

- FractawDevModule
- FractawGameModule
- FractawAudioModule

Modules are independent projects and interact with FractawOS through public contracts defined by FractawModuleSDK.

## Community modules

FractawOS is designed to support community-created modules.

Developers may build modules outside the FractawOS organization using the public SDK and submit them to FractawModuleRegistry.

Modules may be classified as:

- Community
- Verified
- Official

Official status is not required for a module to exist or be useful.

## Main repositories

**FractawOS**  
Core platform, shell, system services, group management, module runtime, telemetry, device integration, and Windows integration.

**FractawModuleSDK**  
Public contracts, module lifecycle, capabilities, permissions, policies, events, and development tools.

**FractawModuleRegistry**  
Registry of modules compatible with FractawOS.

**FractawDevModule**  
Official development environment module.

**FractawGameModule**  
Official gaming integration module.

**FractawAudioModule**  
Official music and real-time audio processing module.

## Project principles

FractawOS should remain modular, explicit, recoverable, observable, extensible, and user-controlled.

Modules extend the platform through public APIs.

Modules must not depend on internal implementation details of the FractawOS Core.

The user remains in control of which applications belong to which groups, which modules are activated, and which policies are applied.

## Contributing

FractawOS is developed in public.

Contributions, discussions, issues, architectural proposals, documentation improvements, and community modules are welcome.

See the contribution and governance documentation before submitting major architectural changes.

## Microsoft and Windows

FractawOS is an independent open-source project and is not affiliated with, endorsed by, or sponsored by Microsoft Corporation.

Windows is a trademark of the Microsoft group of companies.
