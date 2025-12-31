# Technical Glossary

## 6G & Wireless Communications

**6G (Sixth Generation Wireless)**  
The next evolution of mobile networks beyond 5G, operating in Terahertz (0.1-10 THz) frequencies with data rates of 1-100 Tbps, sub-millisecond latency, and AI-native architecture. Expected commercial deployment around 2030.

**THz (Terahertz)**  
Electromagnetic spectrum between 0.1-10 THz (100 GHz - 10,000 GHz). Also called "T-rays." Key advantage for space: near-zero atmospheric absorption in vacuum.

**ISAC (Integrated Sensing and Communication)**  
6G capability where the same electromagnetic waveform simultaneously transmits data AND senses the environment (radar, imaging, material sensing).

**IoB (Internet of Bodies)**  
Network of wearable, ingestible, and implantable biosensors communicating via 6G for real-time health monitoring. Critical for astronaut safety.

**MIMO (Multiple Input Multiple Output)**  
Antenna technology using many transmit/receive elements. 6G uses "Ultra-Massive MIMO" with 1024+ antennas for extreme beamforming precision.

**Beamforming**  
Technique to focus electromagnetic energy in narrow, directional beams rather than broadcasting omnidirectionally. Improves efficiency by 100-1000x.

**URLLC (Ultra-Reliable Low-Latency Communication)**  
6G service class achieving < 1ms latency with 99.9999% reliability. Essential for real-time astronaut monitoring and emergency response.

**Spectral Efficiency**  
Data throughput per unit bandwidth, measured in bits/sec/Hz. 6G targets 100 bps/Hz vs. 5G's 30 bps/Hz.

**Doppler Shift**  
Frequency change due to relative motion between transmitter and receiver. High-velocity satellites and centrifuges create significant Doppler effects that 6G compensates for.

## Space & Orbital Mechanics

**LEO (Low Earth Orbit)**  
Altitude: 340-2,000 km. Satellites orbit Earth in ~90-120 minutes. Examples: ISS (420 km), Starlink (550 km). Low latency (<10ms) but requires large constellations.

**MEO (Medium Earth Orbit)**  
Altitude: 2,000-35,000 km. GPS satellites orbit here (~20,000 km). Moderate latency, fewer satellites needed than LEO.

**GEO (Geostationary Earth Orbit)**  
Altitude: 35,786 km. Satellites orbit once per 24 hours, appearing stationary above Earth. High latency (~250ms one-way) but excellent for backbone relays.

**ISL (Inter-Satellite Link)**  
Direct communication between satellites without ground relay. 6G uses THz/optical hybrid ISLs at 100+ Gbps.

**EVA (Extravehicular Activity)**  
Spacewalk. Astronauts operate outside spacecraft, requiring robust 6G IoB monitoring of vitals and positioning.

**G-Force**  
Acceleration relative to Earth's gravity (1G = 9.8 m/s²). Astronauts experience 3-8G during launch/re-entry, up to 15G in emergencies.

**G-LOC (G-induced Loss Of Consciousness)**  
Blackout caused by blood draining from brain during high-G events. 6G IoB sensors predict this < 5 seconds before onset.

**Regolith**  
Loose rocky/dusty material on Moon/Mars surface. Lunar regolith affects THz propagation (research ongoing).

## Technical Acronyms

**AI (Artificial Intelligence)**  
Machine learning algorithms. 6G is "AI-native," meaning AI manages network optimization, beam tracking, and predictive maintenance autonomously.

**QKD (Quantum Key Distribution)**  
Encryption method using quantum entanglement for theoretically unhackable communication. Integrated into 6G satellite links.

**RF (Radio Frequency)**  
General term for electromagnetic waves used in wireless communication (3 kHz - 300 GHz, extending to THz for 6G).

**RSRP (Reference Signal Received Power)**  
Signal strength measurement. 6G sensors detect micro-changes (< 0.1 dB) to infer structural stress.

**SNR (Signal-to-Noise Ratio)**  
Ratio of desired signal to background noise. THz in space vacuum achieves very high SNR due to minimal interference.

**EIRP (Effective Isotropic Radiated Power)**  
Total radiated power accounting for antenna gain. Space regulations limit EIRP to prevent interference with astronomy.

## Biological & Safety Terms

**Non-Ionizing Radiation**  
EM waves with insufficient energy to remove electrons from atoms. THz is non-ionizing (safe), unlike X-rays or gamma rays (ionizing, dangerous).

**SAR (Specific Absorption Rate)**  
Measure of energy absorbed by biological tissue, in W/kg. 6G limits: < 2 W/kg (same as 5G).

**Green 6G**  
Energy-efficient and ecologically safe 6G design. Includes adaptive beamforming, power scaling, and wildlife protection protocols.

**Biodome**  
Enclosed ecosystem for growing plants/raising organisms in space. 6G networks include RF geo-fencing to protect biodome inhabitants.

**EMG (Electromyography)**  
Measures muscle electrical activity. 6G IoB uses wireless EMG to monitor astronaut muscle health during long-duration missions.

**EEG (Electroencephalography)**  
Measures brain electrical activity. 6G-enabled 256-channel EEG headbands monitor cognitive state during high-G training.

## Mathematical Symbols

**ε_r (Relative Permittivity)**  
How much a material slows down EM waves vs. vacuum. Stress changes density → changes ε_r → changes signal delay (basis of ISAC sensing).

**λ (Wavelength)**  
Distance between wave peaks. At 300 GHz: λ = 1 mm. Smaller wavelength enables higher spatial resolution for sensing.

**c (Speed of Light)**  
299,792,458 m/s in vacuum. THz waves travel at this speed in space (vs. slower in materials/atmosphere).

**Δφ (Phase Shift)**  
Change in wave phase due to propagation delay. ISAC measures phase shifts to detect stress: Δφ = (2πf/c) × L × Δε_r.

## Acronyms Index

- **3GPP**: 3rd Generation Partnership Project (standards body)
- **ESA**: European Space Agency
- **IEEE**: Institute of Electrical and Electronics Engineers
- **ISS**: International Space Station
- **ITU**: International Telecommunication Union
- **JPL**: Jet Propulsion Laboratory (NASA)
- **LST**: Lunar Surface Terminal
- **NASA**: National Aeronautics and Space Administration
- **RSRP**: Reference Signal Received Power
- **THz**: Terahertz
- **UE**: User Equipment (device connecting to network)

---

*For more detailed explanations, see the [Technical Deep-Dive](technical-deep-dive.md).*
