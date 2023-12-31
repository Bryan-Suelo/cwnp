# Certified Wireless Specialist 

## Chapter 1 - Radio Frequency (RF)

1. **What denotes the strength of an RF wave or signal?**

   _Amplitude_
   > The amplitude is the strength or power of the RF wave.

2. **What is decreased as the frequency of a wave increases?**

   _Wavelength_
   > As the frequency increases, the wavelength decreases. Alternatively, as the wavelength increases, the frequency decreases.

3. **What RF behavior is similar to ligth waves as seen in a mirror?**

   _Reflection_
   > Reflection occurs in RF waves as well as ligth waves and is analogous to ligth in a mirror.

4. **What kind of modulation is not used in WLANs?**

   _Frequency Shift Keying (FSK)_
   > FSK is not used in WLANs. Both ASK and PSK are used, and BPSK is a form of PSK modulation.

5. **What is the name of the scheme that determines data rates in WLANs?**

   _Modulation and Coding Scheme (MCS)_
   > The MCS determines the data rates that are available. It is a factor of modulation, coding, channel width and spatial streams, among other variables.

6. **What happens when RF energy is converted to heat when passing through some materials?**

   _Absorption_
   > Absorption occurs when RF energy is converted to heat, and the result is an attenuation of the RF signal as it exists the absorbing  medium.

7. **What modulation type uses _Phase Shift Keying_?**

   _BPSK_
   > All Quadrature Amplitude Modulation (QAM) types use both ASK and  PSK. BPSK and QPSK are the two modulation techniques that only use PSK.

8. **In addition to modulation and coding, what other two primary factors impact the data rate that is achievable in a WLAN link?**

   _Channel width and number of spatial streams_
   > The channel width impacts the data rate, and wider channel widths support higher data rates. The number of spatial streams also impacts the data rate. More spatial streams with the same or better signal quality results in higher data rates.

9. **What other comparative attribute relates an RF wave to another wave in the same channel?**

    _Phase_
    > The phase of an RF wave is an attribute that compares one wave with another wave. They can either be 'in phase' or, to some degree, out of phase.

10. **What metric is preferred by engineers and is used to represent received signal strength?**

    _dBm_
    > While RSSI is a common metric as well, engineers prefer dBm because it is an absolute power measurement, whereas RSSI is arbitrary and unique specified by WLAN vendors.

## Chapter 2 - RF Hardware

1. **What two fields make up an RF wave?**

   _Electric and magnetic_
   > The electric field forms the E-plane, and the magnetic field forms the H-plane.

2. **Where are omnidirectional antennas typically placed within a target coverage area?**

   _Central_
   > Omnidirectional antennas are usually placed near the center of the coverage area since they radiate out in all directions around the antenna.

3. **What kind of antenna is usually placed at the edge of the target coverage area?**

   _Patch_
   > Patch and panel antennas are considered semi-directional and are often placed at the edge of a coverage area, for example, on a wall.

4. **What unit is used to measure antenna gain?**

   _dBi_
   > dBi is preferred by engineers for the measurement of antenna gain. It is relative value since the actual power depends on the amplitude of the input signal power and the metric is defined based on a comparison with an ideal radiator.

5. **Which chart shows the top-down view of an antenna's propagation pattern?**

   _Azimuth_
   > The azimuth or horizontal chart shows the top-down view of the radiation pattern.

6. **When are external antennas used for indoor deployments?**

   _When specific coverage is needed_
   > Most internal office deployments used internal AP antennas. When specific coverage patterns are required, external antennas may be used.

7. **What type of antenna is typically internal to APs?**

   _Omnidirectional_

8. **Which one of the following antennas would be more likely used in a 4-kilometer bridge link?**

   _Grid_
   > Bridge links over greater distances usually use a parabolic dish or grid antenna.

9. **What kind of gain is created by antennas?**

    _Passive_
    > Antennas create passive gain because they do not increase the amplitude of the RF signal received, but instead they focus it.

10. **dBi compares a real antenna's gain to what theoretical antenna?**

    _Isotropic_
    > An isotropic radiator is an ideal theoretical antenna that radiates energy equally in all directions in a spherical pattern.

## Chapter 3 - RF Hardware

1. **What is the maximum data rate of an HR/DSSS PHY transmission?**

   _11_
   > HR/DSSS can support data rates of 1, 2, 5.5 or 11 Mbps.

2. **In what frequency band does the VHT PHY operate?**

   _5 GHz_
   > VHT (802.11ac) operates only in the 5GHz band.

3. **What PHY is designed to use available frequencies in the television space?**

   _TVHT_
   > TVHT implements 802.11 in TV white spaces, which are frequency ranges unused by local television broadcasts.

4. **What PHY is likely to be the most used by low output power, long-range devices that require long battery life?**

   _S1G_
   > S1G-based devices will support long-range communications because of the longer wavelengths used. They can also use lower output power settings and extend battery life.

5. **What amendment is designed optimally for use by IoT devices operating below 1 GHz?**

   _802.11ah_
   > 802.11ah is designed and optimized for use in IoT devices among other such devices.

6. **What is the maximum spatial streams supported by an 802.11n (HT) PHY?**

   _4_
   > HT (802.11n) supportsup to four spatial streams, though most devices in production support three or fewer.

7. **What is the maximum channel width supported by an 802.11ac (VHT) PHY?**

   _160MHz_
   > 802.11ac (VHT) can support up to a 160MHz channel, though they should not be used in any network at this time. A WLAN AP would only rarely need to be configured with channels wider than 40MHz.

8. **What amendment to the 802.11 standard provided for enhanced security to resolve the weakness in WEP?**

   _802.11i_
   > 802.11i introduces TKIP/RC4 (WPA) and CCMP/AES (WPA2).

9. **Why should only 20-MHz channels be used in 2.4GHz WLANs?**

   _The available frequencies in the 2.4GHz band are too few to support wider channels_
   > The 2.4GHz band lacks the frequency space to implement channels wider than 20MHz today effectively.

10. **What amendment to the 802.11 standard provided by QoS in WLANs?**

   _802.11e_
   > 802.11e introduces QoS for WLANs.

## Chapter 4 - Channel Plans and Performance Factors

1. **What metric is typically used to define coverage requirements?**

   _dBm_
   > Signal Strength in dBm is the typical metric used to define coverage requirements.

2. **Which of the following is a method used to increase capacity?**

   _Add more APs_
   > Adding more APs can increase capacity when it is done correctly.

3. **Which of the following is a 2.4GHz channel?**

   _11_
   > 2.4GHz channels are numbered 1 through 14.

4. **What 5GHz channels may require monitoring for radar signals?**

   _Dynamic Frequency Selection (DFS) channels_
   > DFS channels must be monitored for radio activity in many regulatory domains.

5. **What channel width should not be used in the 2.4GHz band?**

   _40MHz_
   > 40MHz channels should never be used in the 2.4GHz band because it provides insufficient frequency bandwidth.

6. **What channel width is tipycally used in high-density 5GHz WLANs?**

   _20MHz_
   > High-density deployments typically use 20MHz, even in the 5GHz band.

7. **What environment is most likely to use 4OMHz channels in the 5GHz bands?**

   _Standard office space_

8. **How many 20MHz channels are available in the 5GHz band based on the 802.11 standard without consideration for regulatory domains?**

   _25_

9. **What metric reveals the delay in transmission of a packet from a source to a destination on the network?**

   _Latency_

10. **Which one of the following is a common minimum signal strength recommended for VoWLAN deployments?**

   _-67dBm_
   > VoIP implementations often recommend signal strengths of -65, -67 or -70 dBm or greater.

## Chapter 5 - Wireless Security Fundamentals

1. **What security solution is used to protect against eavesdropping attacks?**

   _Encryption_
   > Provides confidentiality and is used to protect against eavesdropping.

2. **What authorization technique uses groups or roles to control actions of WLAN?**

   _RBAC_
   > Role-Based Access Control (RBAC) allows for restrictions of WLAN clients based on group membership or roles.

3. **What encryption solution is used with WPA?**

   _RC4_
   > WPA is roughly equivalent to TKIP/RC4, so the encryption used is RC4.

4. **What encryption solution is used with WPA2?**

   _AES_
   > WPA is roughly equivalent to CCMP/AES, so the encryption used is AES.

5. **TKIP/RC4 is the foundation for what Wi-Fi Alliance certification?**

   _WPA_
   > WPA certifies that devices implement TKIP and RC4 based on the 802.11 standard.

6. **Which one of the following is a deprecated security solution in the 802.11 WLAN standard?**

   _WEP_
   > Shared Key Authentication, and WPA are all deprecated in the 802.11-2020 standard.

7. **What is used to manage mobile devices in BYOD implementations?**

   _Mobile Device Management (MDM)_
   > MDM solutions provide for the management of BYOD and enterprise mobile devices.

8. **What WLAN vulnerability takes advantage of human manipulation to gain access to the network?**

   _Social Engineering_
   > Social Engineering uses manipulation tactics to obtain information that should not otherwise be provided.

9. **What is used by WPA2-Enterprise for authentication and key provisioning?**

   _802.1X/EAP_
   > WPA and WPA2-Enterprise use 802.11X/EAP for the authentication and key provisioning. The source materials from the 802.11X/EAP authentication are used in the four-way handshake to generate the encryption keys.

10. **What string is usually passed through a defined algorithm to generat the PSK used in WPA2-Personal deployments?**

   _Passphrase_
   > A passphrase is passed through a defined algorithm to generate the pre-shared key (PSK) in most implementations.

## Chapter 6 - Wireless Network Performance Factors

1. **What is a unique defining characteristic of an MBSS?**

   _It allows communications with nodes that are not directly connected_
   > An MBSS allows mesh nodes to communicate with other mesh nodes without being directly connected with them. IBSS network devices can only communicate directly with other IBSS devices. BSS devices can only communicate with the AP directly in most networks.

2. **Through what must an MBSS communicate to access an infrastructure BSS?**

   _Mesh gate_
   > A mesh gate is used to allow the MBSS to communicate with an infrastructure BSS. The communication may occur through a device that is both an AP to the BSS and a mesh gate and mesh node to the MBSS.

3. **What is a 1x1:1 radio system also known as?**

   _SISO_
   > A device with 1 Tx radio chain, 1 Rx radio chain and 1 spatial stream is a SISO device. 

4. **How many receive radio chains does a 4x3:3 device have?**

   _3_
   > The second part of the nomenclature defines the Rx radio chains; therefore , a 4x3:3 device supports 3 Rx radio chains.

5. **What is a defining characteristic of a MIMO 802.11 device?**

   _Support for multiple spatial streams_
   > Unlike SISO devices, MIMO devices support multiple spatial streams.

6. **What RF phenomenom does MIMO take advantage of to increase the data rate of the transmission?**

   _Multipath_
   > Multipath effects are detrimental to SISO communications and provide advantage in MIMO communications to allow for multiple spatial streams.

7. **QoS is guaranteed in 802.11 networks?**

   _False_
   > QoS is not guaranteed in 802.11 networks. It is a probabilistic QoS. You could argue that it is guaranteed within the device, but gaining access to the medium is still contention based.

8. **What kind of communication needs QoS in wireless networks?**

   _Voice_
   > Voice communications require QoS in wired and wireless networks.

9. **What functionality of the 802.11 standard decreases or increases the data rate in a WiFi link based on signal Quality?**

   _Dynamic Rate Switching (DRS)_
   > DRS decreases and increases the data rate in a link as the signal quality changes. It decreases or increases to the next available modulation and coding rate as specified in the standard.

10. **What kind of frame may be used to implement backward compatilibity in 802.11 networks?**

   _CTS to Self_
   > Backward compatilibity can be performed with RTS/CST frames or with a single CTS to Self frame.

## Chapter 7 - Wireless Access Points, Coordinators, Gateways and Controllers

1. **What document may be used to learn about the details of a specific AP model?**

   _Spec Sheet_
   > The specification sheet or data sheet may be used to gather details about the features and capabilities of an AP model.

2. **What external component of an AP may be documented in a spec sheet?**

   _LEDs_
   > External components such as LEDs, wired ports, reset buttons and mounting options are often defined.

3. **When an AP can simultaneously operate in the 2.4GHz and 5Ghz bands, what it is called?**

   _Dual-band concurrent_

4. **When are external antennas most likely to be used?**

   _Warehouse_
   > External antennas are likely to be used in warehouses, manufacturing plants, outdoor deployments and high density scenarios.

5. **What is the power provided to a powered device when 802.3af is used?**

   _12.95 watts_

6. **What is the power provided to a powered device when 802.3at is used?**

   _25.5 watts_

7. **What specific technology allows an AP to transmit more than one client at the same time?**

   _MU-MIMO_
   > MIMO is used, but the specific technology is multi user MIMO (MU-MIMO)

8. **What skill set is required to understand how the details in a spec sheet may apply to real world deployments?**

   _Translation to marketing language_

9. **What protocol should not be used to manage an AP?**

   _HTTP_
   > Protocols that send information as clear text (HTTP, Telnet, etc.) should not be used for AP management.

10. **What solution is used to allow controller based APs to send data directly to the destination on the wired network?**

   _Distributed forwarding_
   > Distributed data forwarding, or simply distributed forwarding, allows APs to send data directly to the destination on the network.

## Chapter 8 - Wireless Clients and IoT End Devices

1. **What kind of client devices should be purchased if at all possible?**

   _Multi-band_
   > Multi-band devices are the best choice. This allows for access to 5GHz APs.

2. **What kind of client device typically has replaceable wireless NIC?**

   _Laptop_
   > Laptop computers use mini-PCIe, half mini-PCIe, and NGFF (M.2) adapters, which are usually replaceable.

3. **What is the maximum number of spatial streams that are supported by mobiles phones?**

   _2_
   > Two spatial streams are the maximum number supported  by most mobile phones and tablets, and many still only support one spatial stream.

4. **Why is an internal wireless PCI NIC sometimes problematic for desktop computers?**

   _The antennas are often located under the user's desk_
   > Because the antennas protrude from the back of the desktop computer and the computer is often placed under the desk on the floor, the antennas are not optimally located.

5. **Why should you update to the latest drivers for a USB device?**

   _To enable all possible features_
   > When purchasing USB adapters, it is not uncommon for the shipping driver to lack support for some features. For example, several multi-band devices have been sold over the years that require driver updates to enable 5GHz operations.

6. **What PHY do most wireless door locks support as the highest data rate PHY?**

   _802.11g_
   > Support up to ERP.

7. **What three bands may be supported in modern multi-band devices?**

   _2.4, 5 and 60GHz_

8. **What is required to accomplish the highest speeds that are advertised for an AP?**

   _Client devices supporting matching capabilities_

9. **What channel is typically not supported by 802.11n and earlier PHYs?**

   _144_
   > Channel 144 was introduced in 802.11ac and is usually not supported by 802.11n and older devices.

10. **When documenting applications, what metric is important to calculate the number of APs and cell sizes that are required?**

   _Number of expected users_
   > Four factors are important when considering the number of APs and sizes for wireless cells: latency tolerance, throughput requirements, utilization and number of users.

## Chapter 9 - Wireless Solution Requirements

1. **What facility issue may impact RF behavior in hospitals around X-ray rooms?**

   _Metal-lined walls_
   > X-ray rooms may have metal-lined walls that prohibit RF communications and must be accounted for in hospital deployments.

2. **What factor impacts capacity in a conference center or arena when large events are held there that may not impact it when smaller events are held?**

   _Density of people_
   > Humans absorb RF energy, and when more people are in a space, it will impact the signal strenght and propagation, though a significant increase in people is required to have a negative impact.

3. **What should always be performed in a WLAN deployment even if it is just an expansion of an existing WLAN?**

   _Site survey_
   > A site survey should always be performed to gather important information like existing channels used, non-Wi-Fi interferers and RF propagation behaviors in the targeted coverage areas.

4. **What is a common problem related to DHCP when deploying WLANs?**

   _Pool depletion_
   > DHCP pools offer a limited number of IP addresses. When WLANs are added to existing networks, it is not uncommon for the pools to be depleted, resulting in an apparent connection problem for client devices that is actually a network problem, while the wireless link is functioning properly.

5. **What kind of device provides power across a PoE cable to a non-PoE device?**

   _PoE splitter_
   > A PoE splitter will split the power from a PoE source back into separate power and data cables and can be used to power a non-PoE device.

6. **Why would a PoE cable be limited to a shorter length than a typical Ehternet data-only cable?**

   _The PoE power can cause interferences on the ethernet data wires_
   > PoE cables sometimes require shorter cables than typical Ethernet cables because the PoE power can cause interference with the Ethernet data wires in the cable.

7. **What is often missing from a logical network diagram?**

   _Physical locations of devices_
   > In many cases, logical network diagrams provide no information about physical locations. This information is required to determine necessary cable lengths for the WLAN deployment.

8. **Which one of the following is not a factor considered when selecting an AP for capacity-based deplyments?**

   _Outdoor networks lack environmental components that attenuate the signal_
   > Because capacity-based deployments rarely use output power levels on APs that are close to the maximum available, the maximum output power available is not usually a factor.

9. **Why are outdoor networks often more challenging from a capacity perspective than indoor networks?**

   _Outdoor networks lack environmental environmental components that attenuate the signal_
   > In outdoor deployments, walls, windows, and doors are not available to attenuate signals, which makes the capacity design more challenging.

10. **What use case requires QoS and 100-200 Kbps of throughput with low latency?**

   _VoIP_
