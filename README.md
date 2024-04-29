![Logo](frame_002.jpg)

# Welcome to Hello Skyy

The purpose of **Hello Skyy** is To provide a central hub, on decentralized infrastructure, in order to educate, document, and assemble the information, tools, and collaborative development space needed, as we explore an alternative to the control over people that big tech companies employ as a lucrative business model. We want to offer an alternative to big tech, and teach people how to choose freedom and privacy over convenience by exploring web3, blockchain, decentralization, and open source technologies.

- [Learn more about us](https://web.helloskyy.io)
- [Join our Discord](https://discord.io/techdufus)

# Skyy-Net

**Skyy-Net** is a community driven, open source, non profit project, that provides distributed AI designed to run on decentralized infrastructure. We are currently using computer vision models to interpret medical imaging as part of the Skyy-Med project/application. This is the AI or model portion of the project. The web application that utilizes the models trained here is called Skyy-Med and is another public repository under Hello Skyy. [HelloSkyy Skyy-Med](https://github.com/helloskyy-io/Skyy-Med).

## Features

- **tosses bricks** Placeholder for specific feature details.
- **fill me out later** Placeholder for specific feature details.
- **dont be a dufus** Placeholder for specific feature details.
- **straight up awesomness**, Placeholder for specific feature details.

## Community and Contributions

These tools and trained models are available for both private and public use. We encourage you to collaborate with us to enhance both the model and the web application, and to utilize these resources in your own projects. Our goal is to benefit the community and humanity at large.

## Getting Started

This project is configured for easy deployment on a FluxEdge server, part of Flux's new decentralized, distributed, GPU-intensive compute resource. The powerful yet affordable FluxCore service will soon be available here: [FluxCore Service](https://web.helloskyy.io) (this is not yet released to the general public).

You can also deploy the working environment, the project, and even the data sets automatically using the HelloSkyy FluxCore AI Toolbox application found here: [HelloSkyy FluxCore AI Toolbox](https://github.com/helloskyy-io/FluxEdge-AI-Toolbox).


Ensure you've met the following prerequisites: 

1. Created a project at FluxEdge.
2. Are working in the GUI Terminal in the FluxEdge app.
3. Have chosen the Ubuntu Custom option from the AI menu.

### Initial Setup/Installation

Copy and paste the following commands into the FluxEdge GUI terminal and follow the prompts to configure the environment on your blank container:

```bash
apt install curl -y
bash <(curl -s https://raw.githubusercontent.com/helloskyy-io/FluxEdge-AI-Toolbox/main/bash/AI_toolbox.sh)
```

### Relaunching the AI Toolbox (Ansible)

After the initial installation of FluxEdge AI Toolbox, rerun the FluxEdge AI Toolbox and configure the project and dataset on your server, use the following command:

```bash
ANSIBLE_CONFIG=/FluxEdge_AI_Toolbox/ansible/ansible.cfg ansible-playbook -i localhost, -c local /FluxEdge_AI_Toolbox/ansible/playbooks/AI_Toolbox.yml

```
