# Subnet Mask Conversion Tool

This script is a simple Bash tool that converts between CIDR notation and subnet mask notation.

## Features

- Convert CIDR notation to subnet mask
- Convert subnet mask to CIDR notation

## Usage

1. Make the script executable:
   ```
   chmod +x subc
   ```

2. Run the script with either a CIDR notation or a subnet mask as an argument:
   ```
   ./subc <CIDR or subnet mask>
   ```

## Examples

- Convert CIDR to subnet mask:
  ```
  ./subc 24
  ```
  Output:
  ```
  CIDR: 24
  Subnet mask: 255.255.255.0
  ```

- Convert subnet mask to CIDR:
  ```
  ./subc 255.255.255.0
  ```
  Output:
  ```
  Subnet mask: 255.255.255.0
  CIDR: 24
  ```
