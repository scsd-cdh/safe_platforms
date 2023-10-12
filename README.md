# SAFE Platforms

## Introduction

SAFE (Satellite Ada Flight Environment) is a platform designed to streamline and enhance the development of Flight Software for CubeSat missions. The project adheres to an Embedded Software Architecture that follows a modular, scalable, and vendor-flexible design, ensuring smooth operation across various hardware platforms. This repository houses vital components such as the Board Support Package (BSP), Hardware Abstraction Layer (HAL), SVD Bindings, and Configuration Packages pivotal to the SAFE project.

## Key Principles of the Embedded Software Architecture
- **Uniformity and Consistency**: Standardized methodologies for interfacing with hardware components to simplify the learning curve for developers and enhance maintainability.
- **Scalability**: Minimal disruption to the codebase with the integration of new hardware components or sensors.
- **Flexibility with Vendor Libraries**: Option to use vendor implementations or custom solutions, depending on project requirements.
- **Clear Segregation and Maintainability**: Distinct and separate layers for troubleshooting and maintaining different aspects of the hardware-software interaction.

## Components

### Board Support Package (BSP)
- **Sensor Drivers**: Facilitates communication with sensors through various communication protocols like UART, I2C, or SPI.
- **Middleware Integration**: Coordinates middleware components crucial for tasks like communication or data processing.
- **Platform-specific Configurations**: Addresses platform nuances and safeguards against potential hardware pitfalls.

### Hardware Abstraction Layer (HAL)
- **Uniform Interface**: Provides a consistent interface across varying hardware platforms.
- **Optimized Performance**: Interfaces with vendor-provided libraries or SVD bindings to ensure peak performance.
- **Scalability**: Allows for the easy integration of new hardware components or platforms.

### SVD Bindings
- **Direct Hardware Access**: Enables software components to interact directly with hardware registers.
- **Safety and Reliability**: Ensures safe and reliable hardware interaction by leveraging Ada’s strong typing and safety features.
