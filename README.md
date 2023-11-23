# Exercise for the smart-contract engineer role
## Introduction
Welcome! This exercise is part of the application process of the smart-contract engineer role. We hope to provide an exercise similar to the challenges one would encounter whilst developing Tranched. Through assessing your solution, we hope to get a better picture of how you solve problems and whether you'd be a good fit.
Here's my suggestion for the programming exercise

## Technical summary
In this exercises you'll be expected to create 2 tokens. One of them being the underlying asset(eg. USD), and the other one being the pool.
The following functionality is expected of the vault:  
1. Any user should be able to convert their USD tokens into Vault tokens.  
2. Any user should be able to deposit proceeds into the vault, which can be dispersed or withdrawn later by the token holders.  
3. Vault token holders should be able to withdraw their corresponding proceeds from the vault.

### Additional requirements:  
1. When a user deposits proceeds, the pool's token holders should only be entitled to their share of the pool at the time of the deposit. So if a user were to convert their USD tokens after the deposit, they wouldn't be able entitled to any proceeds of any deposit from before their ownership of the token.

## Instructions upon finalization
Create a repository on GitHub with your solution, and add read-access for @hellowodl
