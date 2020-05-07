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

## Justin Neece

Coming from a managed service provider (MSP), here are some of the benefits that ACI added for my previous position.

- Allowed for a more streamlined deployment, "cookie cutter method", of turning up services and resources for multiple customers.
- Making repeatable work much easier by using (reusing) APIs for tasks that happen frequently.
- We went from managing large number of switches manually, to having one platform to configure all of them.
- Managing segmentation, this was previously done by creating vlans, possibly through a large number of switches and tracking by spreadsheet.
- Alleviating the need for OTV by having one fabric stretching across multiple datacenters.
- Although I was not able to see most of the benefits of the automation piece. The automated processes associated with ACI, I am sure, saved a lot of time.
With the design of a new customer portal, the ability to offer "self-service" to customer's that wanted to manage their own infrastructure was on the radar.                     This would not have been able to be accomplished with the previous network setup.
- Many customers had separate production, UAT, and DEV environments which would require a maintenance window, and network support to make changes to shift resources from one "zone" to another when deploying upgrades to applications. Afterwards, this could be accomplished by moving entire environments seamlessly.

At OPPD, here are some benefits we have already seen.

- Using Postman, we were able to build scripts that supported 80+ percent of the deployment configuration. (Huge benefit!)
- Simplified the management of the legacy Nexus 7K, Nexus 5K, and FEX setup for each datacenter.
- Allows for multi-tenancy, in OPPD's case this means allowing segmentation. Being able to split datacenter resources without purchasing separate equipment.
- OPPD used to have to verify what resources were available (OTV, FEX connectivity, available Vlans) before being able to add things into the datacenter. Now we check one place.
-  In a nutshell, "any service, any port, any datacenter" is available now....
- Growing the datacenter in an ACI environment is also much easier and manageable, than growing it switch by switch.
