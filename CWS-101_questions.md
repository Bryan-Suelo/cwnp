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

# Chapter 2 - RF Hardware

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