# LEO CubeSat - LEO CUBEX
This is an open-source Low Earth Orbit (LEO) CubeSat design, entirely developed as an initiative of Orbit, the rocketry club of NIT Tiruchirappalli.

## Standardisation
In 2017, a standardization effort led to the publication of ISO 17770:2017. This standard defines specifications for CubeSats, including their physical, mechanical, electrical, and operational requirements. It also provides a specification for the interface between the CubeSat and its launch vehicle, detailing the capabilities required to survive the environmental conditions during and after launch. The standard describes the deployment interface used to release the satellites. The development of shared standards has significantly reduced the development time and cost of CubeSat missions.

## Technical Standards  

- **Size:** A 1U CubeSat measures **10 cm × 10 cm × 11.35 cm**, providing a usable volume of **10 cm × 10 cm × 10 cm**. The most common form factor is **3U**.  
- **Protrusions:** Protrusions beyond the maximum dimensions are allowed by the standard specification, up to a maximum of **6.5 mm** (0.26 in) beyond each side. These are typically occupied by antennas and solar panels but must not interfere with deployment rails.  
- **Electronics:** No specific form factors or communication protocols are mandated by the CubeSat Design Specification. However, **commercial off-the-shelf (COTS)** hardware frequently uses certain de facto standards.  
    - **Form Factor:** Most COTS and custom-designed electronics fit the **PC/104** form factor, which has a profile of **90 mm × 96 mm** (3.5 in × 3.8 in), leaving most of the CubeSat's volume for other components.  
- **Deployment:** CubeSats are launched and deployed using a standardized deployment system, the **Poly-PicoSatellite Orbital Deployer (P-POD)**, developed by Cal Poly.  
- **Radiation Considerations:**  
  - For very low Earth orbits (LEO), where atmospheric reentry occurs in days or weeks, radiation effects can largely be ignored, allowing the use of consumer-grade electronics.  
  - For sustained LEO missions lasting months or years, hardware must be designed for and tested against radiation exposure to prevent failures like **single event upsets (SEUs)**.  
- **Computing Systems:** CubeSats typically include multiple computers to handle various tasks in parallel:  
  - **Attitude control** (orientation)  
  - **Power management**  
  - **Payload operation**  
  - **Primary control**  
  - Many **COTS** attitude control and power management systems have their own embedded computers. Payloads interface with the primary computer and may sometimes require their own small computer.  
- **Power:**  
  - CubeSats use **solar cells** to convert sunlight into electricity, stored in rechargeable **lithium-ion batteries** for use during eclipses and peak load times.  
  - Some CubeSats explore **solar sails** for propulsion, using radiation pressure from sunlight to push large, ultra-thin mirrors to high speeds, eliminating the need for propellant.  
- **Propulsion:** CubeSat electric propulsion uses electricity to accelerate propellant at high speeds, resulting in high **specific impulse**. Current technologies include:  
  - **Hall-effect thrusters**  
  - **Ion thrusters**  
  - **Pulsed plasma thrusters**  
  - **Electrospray thrusters**  
  - **Resistojets**  
- **Communication:**  
  - CubeSats commonly use **omnidirectional monopole** or **dipole antennas**, often constructed with commercial measuring tape.  
  - For communication in LEO, CubeSats frequently operate in the **UHF** and **S-band** frequency ranges.  


