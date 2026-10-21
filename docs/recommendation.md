# Context Information: Network Simulation System Recommendations
## The following features were kept in mind to enhance the features, usability, and architecture of SecuSim 2.0:

# Implemented Patches
## Patch 2.1: Custom Scenarios 
- Users must have the freedom to create custom simulation scenarios.

## Patch 2.2: IP Address Classes and Ethernet Cabling
Enhanced IP Address Assignment
- Upgrade the IP assignment mechanism to organize devices systematically into IP classes (e.g., Class A, B, C), creating a more realistic networking simulation.
Physical Network Wiring Options
- Implement configurable network cabling options, allowing users to select between straight-through and crossover Ethernet cables based on specific scenario requirements and device types.

## Patch 2.3: Packet Sending
Network Sandbox Packet Sending
- Inside the sandbox module, the users must be able to send packets once they finished designing their desired network structure.


# Upcoming Patches
## Enhanced Results Modal:
- The results modal will not only display the list of completed conditions during the simulation but also the snapshot of the user's network design.

## Enhanced Packet Sending:
- A ping that arrives counts as “Answered” where the endpoint device will "respond" to the "request".
- Firewall Policies must apply not only at the two endpoint devices, but also at devices in the middle.


# Future Patches (To be added later)
## User Authentication & Accounts: 
- Introduce user accounts with secure database storage to allow authentication, persistent session management, and the ability for users to save progress and custom configurations.

## Subscription Model & Access Control: 
- Establish a tiered subscription plan. Subscribed users gain full access to detailed simulation results and advanced features, while free/non-subscribed users operate under limited access.
