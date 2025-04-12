⚠️ *Disclaimer: This project is in a preliminary state and under active development. Features and functionality may change significantly.*

➡️ *Development Note: The core of Edge Mining will be developed in the [core repository](https://github.com/edge-mining/core), which is intended to serve as the main engine of the system. This repository is specifically dedicated to the Home Assistant add-on.*

📚 *This is the repository for the Home Assistant [add-on](https://github.com/edge-mining/addon), which is still in development.*


# ⚡ Bitcoin Mining for Energy Efficiency

Bitcoin mining represents a unique opportunity to improve efficiency in both the production and use of energy, whether on an industrial scale or for smaller setups. This project aims to make mining accessible and easy to implement, providing tools to integrate mining into energy systems and maximize the use of the energy produced.

## 🌞 The Challenge: Managing Excess Energy

In energy production plants, especially those relying on renewable sources like solar and wind, there's often a surplus of energy generated during peak hours (for example, when there is a lot of sun or wind) that doesn't align with peak demand times. Today, the main options for managing this excess energy include:

- **Selling the energy to the national grid**: This is possible only if the grid accepts the surplus, and often at unfavorable economic conditions.
- **Purchasing additional storage systems**: Such as batteries, which can be expensive and not always scalable, limiting this option for many small producers.
- **Using the energy for various purposes**: For instance, producing hydrogen through electrolysis, charging electric vehicles, or pumping water for hydroelectric storage. However, these solutions are often challenging and costly to implement, especially for small- and medium-sized plants.
- **Using energy for marginal purposes**: Such as resistive heating, which generally doesn’t add significant economic value.
- **Wasting the energy**: Which is a loss that reduces the overall efficiency of the plant.

## 🔌 The Solution: Bitcoin Mining

Bitcoin mining is a computational process that verifies and validates transactions on the Bitcoin network. This process ensures network security, using electrical energy to power specialized devices called miners. In return for this activity, miners receive a reward in Bitcoin, making mining not only useful for the network but also economically beneficial for participants.

This process has a unique feature that makes it particularly suitable for integration with renewable energy production plants: it is extremely flexible, able to be activated to consume energy during times of surplus and stopped immediately when energy is needed for other purposes.

Moreover, mining produces heat as a byproduct. 100% of the electrical energy used by a miner is converted into heat, making it similar to an electric heater that, in addition to providing warmth, also generates a constant economic reward.

These characteristics make mining an ideal solution for managing excess energy, particularly in small- and medium-sized plants.

## 🏡 Edge Mining: A Practical Approach for Everyone

Aside from electrical power, mining only requires a miner and a low-speed internet connection. It virtually needs nothing else, making it a very simple activity to implement anywhere.

You could say that the hardware implementation of a mining system is not particularly complex from a technical standpoint. In trying to implement it ourselves, we realized that the only missing element for a fully functional system was a management and automation solution for the mining process, specifically software that connects the energy production plant to the miners, regulating power on/off and energy consumption.

Our project aims to develop a mining management system that:

- Connects the power generation plant with one or more ASIC devices for mining.
- Allows users, even non-experts, to automate the mining process based on specific energy requirements.
- Helps users manage and make the most of the heat generated by the ASICs for space heating, thereby maximizing the energy surplus of the plant.

## 📍​ Development

This is the very first phase of development and how the application takes shape.

Following some resources:
- 📒​ A glossary of terms for a better understanding -> [Glossary](./modelling/glossary.md)
- 🧑‍💻​ Building the project:
  - 🧠​ Defining main domain, sub-domains and concerns -> [Step 1](./modelling/steps/step_1.md)
  - 🧩​ Defining entities and relations between sub-domains -> [Step 2](./modelling/steps/step_2.md)

---

## ✏️ Conclusion

Edge Mining proposes an innovative solution to optimize the use of excess energy produced by small power plants, particularly renewable ones. Integrating Bitcoin mining is a flexible, economically advantageous, and easy-to-implement choice. With our mining management system, users can maximize the efficiency of their plant, utilize the heat produced, and contribute positively to the Bitcoin network. This approach turns a potential inefficiency into a concrete opportunity for profit and sustainable energy use.

## 🤝 Contributions and Feedback

We welcome contributions and feedback to make this project even better. Feel free to open issues or submit pull requests.

Let’s mine smarter, together.
