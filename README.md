# Banking CRM

A banking customer and account management system built using
Microsoft Power Platform, Dataverse, Dynamics 365 Model-driven Apps,
and C# Plugins.

## Technologies

- Microsoft Dataverse
- Dynamics 365 / Power Apps
- Model-driven App
- C# / .NET
- Dataverse Plugins
- Plugin Registration Tool
- Power Automate

## Main Features

- Customer management
- Bank account management
- Deposit transactions
- Withdrawal transactions
- Account balance validation
- Account-to-account transfers
- Business logic implemented using C# Dataverse Plugins

## Plugin Architecture

### DepositPlugin
Updates the bank account balance when a deposit transaction is created.

### ValidateWithdrawalPlugin
Validates the available balance before processing a withdrawal.

### TransferPlugin
Transfers money between two bank accounts while validating the source
balance and updating both accounts.

## Demo

[Watch the CRM Demo](PUT-YOUR-VIDEO-LINK-HERE)
