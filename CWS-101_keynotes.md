# Certified Wireless Specialist

## Chapter 1 - Radio Frequency (RF)

- Radio frequency (RF) waves are used to transmit and receive data on WLANs.
- The wavelength of a wave is related to its frequency: higher frequencies correspond with shorter wavelengths, and lower frequencies correspond with longer wavelengths.
- The amplitude of a wave is the power or strength of the wave.
- The phase of a wave is a comparative attribute that relates one wave to another.
- Waves may be *in phase*  with other waves or, to some degree, out of phase with other waves.
- Modulation uses phase shifts (PSK) and amplitude shifts (ASK) in WLANs.
- RF waves are reflected off obstacles that are large in relation to their wavelengths and that have reflective properties.
- Many materials absorb some of the RF energy of the waves as the waves pass through them.
- RF transmission power is often referenced in watts (W) or milliwatts (mW), but received signal strength is tipically referenced in dBm.
- 802.11 devices use a modulation and coding scheme (MCS) to achieve the data rate in the link.
- In addition to the modulation and coding, the channel width and the number of spatial streams impact the achievable data rate.

## Chapter 2 - RF Hardware

- Antennas radiate electromagnetic waves in the RF range in WLANs.
- Omnidirectional antennas uniformly radiate energy around the antenna element in a circular pattern.
- Omnidirectional antennas are usually placed in the center of the target coverage area.
- Semi-directional antennas radiate energy in a typical range between 50 and 180 degrees.
- Highly directional antennas radiate energy in very narrow propagation patterns and are useful for long distance-links.
- Highly directional antennas are usually placed at both ends of a bi-directional link.
- The azimuth (horizontal) chart shows the top-down view of an antenna's radiation pattern and indicates outward propagation.
- The elevation (vertical) chart shows the side view of an antenna's radiation pattern and indicates 'up and down' propagation.
- Internal AP antennas are most commonly used for indoor office deployments.
- External antennas are used to provide specific coverage patterns in deployments and for bridge links and other special cases.

## Chapter 3 - Wireless Standards

- IEEE standards are developed by working groups and go through draft phases before they become an standard.
- The original 802.11 standard was released in 1997, and the only PHY remaining in production from that initial standard is DSSS.
- The DSSS PHY supports a maximum data rate of 2 Mbps; it also has one lower data rate (1 Mbps) and operates in 2.4 GHz band.
- The HR/DSSS PHY introduced the addition data rates of 5.5 and 11 Mbps and operated in the 2.4 GHz band.
- Both DSSS and HR/DSSS use 22-MHz channels, but ERP and OFDM use 20-MHz channels.
- HT supports both 20 and 40 MHz channels and VHT supports 20, 40, 80 and 160 MHz channels.
- The VHT-PHY operates in the 5 GHz band and supports a maximum data rate of 6933.3 Mbps.
- 802.11i introduced security enhancements to the 802.11 standard.
- 802.11e introduce QoS enhancements to the 802.11 standard.
- 802.11u introduced interworking with external networks to the 802.11 standard.

## Chapter 4 - Channel Plan and Performance Factors

- Coverage is important in WLAN deployments and is usually specified as some minimum signal strength requirement.
- Signal strength requirements are typically stated in dB, such as -65 dBm to -70 dBm.
- Capacity is the ability of the WLAN to service the needed number of clientsand the applications they use.
- Capacity can be increased by adding more APs with reduced output power settings.
- The 2.4 GHz band should only be used with 20 MHz (802.11g [ERP] and 802.11n [HT]) or 22 MHz (802.11 [DSSS] and 802.11b [HR/DSSS]) channels.
- 40 MHz channels should not be used at 2.4 GHz.
- 80 MHz chanels should be used with great care at 5 GHz.
- 25 20 MHz channels are potentially available in the 5 GHz band.
- Some channels may require monitoring for radar in the 5 GHz band, and these are called DFS channel.
- VoIP requires low latency and reliability for proper operations.
- Removing WLAN congestion problems can improve the performance of VoWLAN communications.

## Chapter 5 - Wireless Security Fundamentals

- Common WLAN vulnerabilities include eavesdropping, DoS, management interface exploits, encryption cracking, authentication cracking, MAC spoofing, peer to peer attacks and social engineering.
- Confidentiality is the concept of keeping private information.
- RBAC implements authorization using groups or roles.
- Key management is the process of provisioning and replacing encryption keys used for confidentiality.
- WPA is based on TKIP/RC4 and WPA2 is based on CCMP/AES.
- WPA and WPA2-Enterprise use 802.11X/EAP authentication.
- WPA and WPA2-Personal use a pre-shared key (PSK), usually based on a passhphrase, to authenticate devices and provision encryption keys.
- WEP, Share Key Authentication, and TKIP are all.
- When WPA is used in an 802.11n/ac deployment, it effectively causes the STAs to function as 802.11a or 802.11g STAs, which greatly diminishes performance.
- BYOD is a reference to the users that utilize their personal devices for business work on the organization's WLAN.
- MDM can be used to manage BYOD and enterprise devices.
- Guest networks may be separated from enterprise networks with VLANs or tunnels.
- SSIDs can be mapped to different VLANs to constrain the connecting device's network access.

## Chapter 6 - Wireless Network Performance Factors

- An MBSS is a mesh BSS and does not include a standard infrastructure BSS, but it may connect to one through a mesh gate.
- An MBSS is different from an IBSS (ad-hoc) because mesh STAs may be able to communicate with other mesh STAs to which they are not directly connected.
- MIMO systems use multiple antennas to send multiple spatial streams.
- The nomenclature for MIMO radio chains is `Tx radio chain x Rx radio chain : spatial streams`. An example is that 3x3:2 supports `3 Tx and Rx radio chains but only 2 spatial streams`.
- When two 802.11 devices communicate, the lowest common denominator related to spatial streams, channel widths and supported PHYs will determine the communications method.
- QoS is implemented in 802.11 networks within each STA and gives probabilistic priority to important packets, such as voice and video communications.
- DRS decreases or increases the data rate in a wireless link based on the signal quality of the link.
- Backward compatibility is achieved by supporting older PHYs that operate in the same band as the device and implementing RTS/CTS or CTS-to-self.
- OKC is propietary standard for FSR, and FT is the 802.11 standard method of FSR.
