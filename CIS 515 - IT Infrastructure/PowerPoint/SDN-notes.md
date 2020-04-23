# Software-Defined networking notes

ACI

[VIDEO: What is software-defined networking (SDN)](https://www.youtube.com/watch?v=Z5Gi2Bpd82M)

- researchers from standards
- bringing the tenets of virtualization to networking
- virtualize the network by separating control plane from data plane

## Use Cases

- networks can be spun up dynamically
- policies can be placed on separate networks
- microsegmentation
- organization of Internet of Things devices (IoT)

[Introduction to SDN (Software Defined Networking)](https://www.youtube.com/watch?v=WEdDQsyXT6E)

Things you have to do on a network to isolate a VM from others (manual).

- Create a new vLAN
- Create a new gateway
- Create firewall rules
- Configure BGP on edge routers

An SDN controller would be responsible for managing all of those tasks, in software.

[SDN vs. Traditional Networking](https://www.ibm.com/services/network/sdn-versus-traditional-networking)

- Basis
  - **Traditional**: Defined by hardware, more rigid
  - **SDN**: Defined by software, allows for more flexibility
- Location
  - **Traditional**: Bound by the physical location of the control plane
  - **SDN**: virtualizes entire network, generates an abstract copy of physical network
    - lets you provision resources from centralized location
    - Ability to quickly process different network configuration from a centralized UI is beneficial for network segmentation

Advantages of SDN

- traffic programmability
- Greater agility
- Capacity to generate policy-driven network supervision
- ability to implement network automation
- Cloud abstraction
  - Use SDN to abstract cloud resources to help simply the process of unifying cloud resources
- Consistent and timely content delivery
  - Big for QoS VoIP and multimedia

Why are companies transitioning to SDN from traditional networks?

- Provide users untethered access to IT resources
- Bring-you-own-device in workplace requires dynamic and flexible networks.
  - Traditional networking adheres to cycles and proprietary interfaces.
- Ease of administration through software and automation
