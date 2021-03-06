# Core.SelfService.Component.Capability RFC
## 1 Abstract
This document proposes a backstage component for provisioning DFDS capabilities. The component provides a fully functional control plane for DFDS capabilities.

## 2 Status
Accepted

## 3 Component purpose
Provides a overview of DFDS capabilities containing helpful meta data about location, availability, ownership, cloud dependencies and more. Consumes and produces events related to capability life-cycle management for other components to consume.

## 4 Capability
### 4.1 Level 1
Core.SelfService.Component.Capability

## 5 API
### 5.1 REST
#### 5.1.1 API description
TODO

#### 5.1.2 Contract
TODO

### 5.2 Event
#### 5.2.1 Events published by the component
- *Capability Registered* - Raised when a new capability has been registered in the UI.

#### 5.2.2 Events subscribed to by the component
- *Capability Created* - Raised by the CapabilityService when a new capability is created.

- *Capability Updated* - Raised by the CapabilityService when a new capability is updated.
  
- *Capability Deleted* - Raised by the CapabilityService when a new capability is deleted.

### 5.3 DOM
#### 5.3.1 Custom Element
dfds-capability-plugin

#### 5.3.2 Custom attributes
TODO


## 7 Hosting
Hosted in Hellman as a "managed capability" and integrated in Backstage as a "plugin".

## 8 Inner architecture
TODO