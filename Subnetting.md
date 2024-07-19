# Subnetting

## Introduction
Subnetting involves dividing a larger network into smaller, manageable sub-networks.

## Subnet Mask
The subnet mask determines the network and host portions of an IP address.

- **Example**: `255.255.255.0` for a standard Class C network.

## Calculating Subnets
1. **Determine Subnet Requirements**: Number of required subnets.
2. **Calculate Subnet Mask**: Adjust the subnet mask to accommodate the number of subnets.
3. **Subnet Addressing**: Assign IP ranges to each subnet.

## Example Calculation
- **IP Address**: `192.168.1.0`
- **Subnet Mask**: `255.255.255.192`
- **Subnets**: `192.168.1.0/26`, `192.168.1.64/26`, etc.

## Conclusion
Subnetting helps in efficient IP address management and network segmentation.