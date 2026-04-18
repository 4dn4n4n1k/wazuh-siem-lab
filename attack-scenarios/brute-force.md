# Brute Force Attack Simulation

## Tool Used
Hydra

## Command
hydra -l root -P rockyou.txt ssh://<target-ip>

## Expected Result
Multiple failed login attempts detected

## Wazuh Detection
- Rule ID: xxxx
- Level: High
- Description: SSH brute force attempt