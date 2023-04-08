## Guanaco: Open-Source AI Chatbot

A Guanaco is a wild LLaMA.  It's an open-source AI chatbot powered by the BLOOM GPT model. It runs locally and is designed to offer private, accessible AI solutions without the restrictions imposed by the GPT-3 model. Guanaco is inspired by Stanford's Alpaca but focuses on providing more freedom for developers and users.
Features:

* Powered by the BLOOM-176B model
* Unrestricted usage compared to GPT-3
* Emphasis on privacy and data security
* Local implementation for better control
* Apache 2.0 licensed

# License

Guanaco is licensed under the Apache License 2.0. This license allows you to freely use, modify, and distribute the software, subject to the terms and conditions outlined in the license.

# BLOOM-176B and Training Data

OpenAI's terms of service say you can't "use output from the Services to develop models that compete with OpenAI".

Unlike Alpaca, Guanaco uses the BLOOM-176B model to generate training data, avoiding thes restrictions.

# Self-Instruct Package

The training data generation process for Guanaco follows the same Apache 2.0 licensed instructions used in the self-instruct package. This ensures that the project adheres to the open-source ethos and maintains compliance with the Apache 2.0 license.

# Getting Started

To start using Guanaco, please follow these steps:

Clone the repository:
```
git clone https://github.com/nbanks/guanaco.git
```

Set up your environment and install dependencies:
```
cd guanaco
pip install -r requirements.txt
```

Run Guanaco locally:
```
python guanaco.py
```

For more information on how to use and contribute to Guanaco, please refer to the documentation.

# Contributing

We welcome contributions from the community! If you're interested in improving Guanaco, please read our contributing guidelines to learn more about submitting pull requests and reporting issues.

# Acknowledgments

We would like to thank the creators of the BLOOM GPT model and the self-instruct package for providing the foundation for Guanaco. We also acknowledge Stanford's Alpaca project for inspiring the creation of Guanaco and its focus on accessible, open-source AI solutions.
