# Chapter 1 - Radio Frequency (RF)

1. **What denotes the strength of an RF wave or signal?**

   _Amplitude_
   > The amplitude is the strength or power of the RF wave.

2. **What is decreased as the frequency of a wave increases?**

   _Wavelength_
   > As the frequency increases, the wavelength decreases. Alternatively, as the wavelength increases, the frequency decreases.

3. **What RF behavior is similar to ligth waves as seen in a mirror?**

   _Reflection_
   > Reflection occursin RF waves as well as ligth waves and is analogous to ligth in a mirror.

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

---

# Chapter 2 - RF Hardware

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

---

# Chapter 3 - RF Hardware

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

---

# Chapter 4 - Channel Plans and Performance Factors

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
   >

8. **How many 20MHz channels are available in the 5GHz band based on the 802.11 standard without consideration for regulatory domains?**

   _25_

9. **What metric reveals the delay in transmission of a packet from a source to a destination on the network?**

   _Latency_

10. **Which one of the following is a common minimum signal strength recommended for VoWLAN deployments?**

   _-67dBm_
   > VoIP implementations often recommend signal strengths of -65, -67 or -70 dBm or greater.

---

# Chapter 5 - Wireless Security Fundamentals

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
   ---

# Chapter 6 - Wireless Network Performance Factors

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