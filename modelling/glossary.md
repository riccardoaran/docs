# Glossary

Following the **Ubiquitous Language** approach of Domain-Driven Design (DDD), this glossary is organized by subdomains and contains simplified definitions gathered from domain experts. Its purpose is to establish a clear and consistent vocabulary, essential for effective communication and development of the application.

## ⚡ Energy Production

**Inverter**: A machine that produces energy using solar panels. It may have one or multiple MPPTs and can be either on-grid or off-grid.

**Solar panel**: A hardware component that produces energy from sunlight.

**Battery**: A hardware component that stores energy.

**Battery SoC**: *State of Charge* of the battery; it represents the total amount of energy stored in the battery.

**Battery Discharge**: The process by which energy exits the battery.

**Battery Charge**: The process by which energy enters the battery.

**Unused Energy**:
- In On-Grid systems, this is the energy not used by the loads and fed into the national electric grid.
- In Off-Grid systems, this is the energy not produced by the system because it is not required by the loads/batteries.

**Loads**: Devices that consume energy.

## ⛏️ Mining

**Miner**: A machine that uses electrical energy to solve mathematical calculations and produce heat.

**Hashboard**: The part of the miner that contains the chips responsible for calculating hashes.

**Control board**: The main controller in a miner that manages communication, power distribution, and operational logic.

**Fan**: A cooling component that regulates the miner's internal temperature by moving air across heated parts.

**Smart plug**: A remotely controllable power outlet that can be used to power on/off a miner automatically or based on conditions.

**Hashrate**: A measurement of the computing power of a miner.

**Energy consumption**: The electrical energy used by the miner.

**Core temperature**: The temperature of the main chips.

**Efficiency**: The power consumption in relation to the produced hashrate. Can be measured in W/TH or J/TH.

**Mining pool**: A group of miners who combine their computational resources to increase the probability of mining a block and share the reward proportionally.

**Stock Firmware**: The original firmware pre-installed by the miner's manufacturer. It governs low-level operations such as startup sequences, thermal management, fan control, hashrate adjustment, and network communication. Typically more stable but less customizable than third-party firmware.

**Third-Party Firmware**: Custom firmware developed by independent developers or communities that replaces the stock firmware on a miner. It often provides enhanced functionality, greater configurability, performance tuning options, and additional features such as API access, advanced monitoring, or custom fan curves. It may, however, require more technical knowledge and can void warranties.
