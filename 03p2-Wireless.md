---
layout: default
---

## Wireless Microphones
 - Allow a performer to move across the stage unimpeded by wires
 - Have many more possible points of breakage than a wired connection

## Frequency Coordination
 - One Transmitter to One Receiver
 - One Frequency to each Transmitter and Receiver
 ... The more microphones you add the more you have to worry about _intermodulation_

## Interference
- We are Part 15 users of the UHF spectrum
- We must not generate any interference, a- We are Part 15 users of the UHF spectrum
nd must accept interference from everyone else
- Other users of the spectrum can include:
 + Intercom Equipment
 + Other wireless microphone users
 + TV Broadcasts
 + White Space Devices

## TV Broadcasts
 - Primary users of the spectrum
 - We cannot cause interference
 - By the time we would cause interference, our microphone would be useless anyways
 - Large High Power Towers high above the ground that can reach for miles

## White Space Devices
 - Newcomers to the field
 - Also part 15 equipment
 - Required to 'listen before broadcast'
 - Can easily miss wireless microphones in the listen stage
  + Microphone may not be turned on
  + Microphones transmit at much lower power levels
    - 1/10 to 1/100 or more difference
    - Fixed White space devices can encompass the entire broadcast area of the microphone without being in the broadcast area of the Microphone

## FCC
 - The FCC Database is the single most important tool in your arsenal to predict frequencies in use.

## Intermod
 - Two or more frequencies combine to create 'phantom' frequencies
 - Can be predicted by MATH!
 - Get exponentially more complex with each additional microphone
 - We are only really concerned about:
   + Subtractive Intermodulation
   + Odd-Order Intermodulation

## Third Order Intermodulation
 - 2A-B
 - 2B-A

## Fifth Order Intermodulation
 - 3A-2B
 - 3B-2A

## Example 3rd Order Intermod Calculations:
 Microphones at (554.000, 554.600, 556.300, 559.300)
 1. (2*554.000) - 554.600
 2. (2*554.600) - 554.000
 3. (2*554.000) - 556.300
 4. (2*556.300) - 554.000
 5. (2*554.000) - 559.300
 6. .....

## Software
 - Due to complexity of larger systems, software is often used
 - Masque IAS
 - Shure Wireless Workbench (*FREE*)
 - Sennheiser WSM
