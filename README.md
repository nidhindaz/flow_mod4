

# Cadence Smart Contract Assignment

## Description

This repository contains a Cadence smart contract implemented in the Flow blockchain's scripting language. The contract, named `SomeContract`, defines variables and functions within different areas of the contract, demonstrating the access control mechanisms provided by Cadence.

## Contract Structure

The `SomeContract` is organized as follows:

- **Area 1 (`structFunc`):** A function demonstrating access to variables within the same contract.

- **Area 2 (`resourceFunc`):** A function operating within a resource's scope, showcasing access to resource variables.

- **Area 3 (`questsAreFun`):** A function within the contract's scope, highlighting access to both variables and functions within the contract.


## Areas and Accessibility

1. **Area 1:**
    - Accessible Variables: a (read/write), b (read/write), c (read/write), d (read/write)
    - Accessible Functions: None

2. **Area 2:**
    - Accessible Variables: e (read/write)
    - Accessible Functions: None

3. **Area 3:**
    - Accessible Variables: a (read/write), b (read/write), c (read/write), d (read/write)
    - Accessible Functions: publicFunc, contractFunc, privateFunc

4. **Area 4 (`main` function):**
    - Accessible Functions from SomeContract: createSomeResource, questsAreFun
