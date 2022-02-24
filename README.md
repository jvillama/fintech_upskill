# fintech_upskill
FinTech Upskill

Tues, Feb 22 2022
7:15AM PST
- Work on Module 18: Blockchain with Python
    - Record-keeping system in a decentralized way.
    - Deploy the decentralized blockchain through a web application so that anyone can review and use it.
    - A blockchain is a technology that records and shares data over a network, such as the internet.
    - The system is designed so that the remaining blockchains—replicated on potentially thousands or millions more computers—will automatically identify the compromised blockchains as invalid. So, distributed blockchain technology has a built-in auditing system.
    - Streamlit web application server and webpage display functionality
    - Creating a Blockchain Block with a Python Data Class
    - Hashing is a cryptography technique that takes a piece of input data and then outputs a fixed-length, mathematical representation of that data—a hash.
    - Create a new block of data and display the hash for that block.
    - Build a Streamlit application that can both generate new blocks of user data and add them to a Python blockchain
    - Issue encountered 18.2.9 Activity: Blockchain Application
        - https://blog.streamlit.io/all-in-on-apache-arrow/
        ```
        [global]
        dataFrameSerialization = "legacy"
        ```
        must be added to `~/.streamlit/config.toml`
    - Consensus mechanisms use protocols and algorithms to achieve a consensus about the state of the system. While many approaches exist for reaching a consensus.
        - Two of the most common consensus algorithms are proof of work and proof of stake.
    - Validating the Blockchain

- Work on Module 19: Blockchain Wallets
    - Overview of python modules and libraries:
        - Web3.py (Links to an external site.): A Python library for connecting to and performing operations on Ethereum-based blockchains.
        - ethereum-tester (Links to an external site.): A Python library that provides access to the tools we’ll use to test Ethereum-based applications.
        - mnemonic (Links to an external site.): A Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.
        - bip44 (Links to an external site.): A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.
        - Infura API: An API that provides instant access to the Ethereum network over HTTPS (i.e., the web). You will need to create an account with Infura.
    - An Ethereum node’s mem-pool is where all new transactions wait to be confirmed by the blockchain network, added to a block, and included in the chain.
    - Connect to an Ethereum blockchain using the Web3.py library.
    - Understand the basics of asymmetric cryptography and public-private key pairs.
    - Generate a digital wallet from a mnemonic seed phrase.
    - Sign a transaction by using a blockchain account’s private key.
    - Verify a transaction by using a blockchain account’s public key and account address.
    - Sign and execute a transaction on a test blockchain network by using Web3.py.
    - Analyze blockchain transactions by using a blockchain explorer.


12:15AM PST