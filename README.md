# Enhanced-MAC-Protocol-for-Efficient-Collision-Resolution-in-IEEE-802.11-Networks

## Problem Statement
Implement the new MAC protocol which modifies the existing IEEE 802.11 protocol.The change required is in the sensing process:
The current algorithm uses both backoff period and DIFS period to wait when a collision occurs. The modification required is to check if the backoff period is greater than DIFS, use only backoff period to wait and avoid waiting for DIFS Period too.
To verify the working of modified protocol, simulate a wireless network consisting of 6 mobile nodes (n0 – n5). Use the modified protocol.
