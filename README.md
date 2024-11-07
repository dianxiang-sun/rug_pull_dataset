# Rug Pull Dataset for DeFi Security Research

This dataset contains 2,360 validated rug pull incidents from Ethereum and BSC chains, documented between 2020 and 2023. The dataset aims to support research in DeFi security, particularly in rug pull detection and prevention.

## Dataset Structure

The dataset is provided as a CSV file with the following columns:

- `No.`: Unique identifier for each incident
- `Chain`: Blockchain platform (ETH/BSC)
- `Address`: Contract address of the rug pull incident
- `Losses`: Documented financial losses in USD
- `Type`: Classified rug pull type based on our taxonomy
- `Root_Causes`: Technical analysis of attack mechanisms
- `Sources`: Security firms that reported/verified the incident
- `URL`: Reference links to security reports and analyses

## Data Collection & Validation

- Each incident is verified by established security firms
- Financial losses are documented with conservative estimates
- All data is collected from public sources and security reports
- Multiple source verification is required for inclusion

## Coverage

- Platform Coverage: Ethereum and Binance Smart Chain
- Time Period: 2020-2023
- Rug Pull Types: 19 distinct types identified
- Coverage Rate: 54% of known rug pull types

## Usage Notes

- URLs point to original sources
- Empty fields are marked as "N/A"
