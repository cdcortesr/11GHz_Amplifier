# RF Power Amplifier PCB Design for Satellite Transmitter (11 GHz)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cdcortesr/RF-Power-Amplifier-11GHz-/refs/heads/main/3Dview.JPG">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/cdcortesr/RF-Power-Amplifier-11GHz-/refs/heads/main/3Dview.JPG">
  <img alt="a." src="https://raw.githubusercontent.com/cdcortesr/RF-Power-Amplifier-11GHz-/refs/heads/main/3Dview.JPG">
</picture>

• Designed a high-power RF amplifier PCB module that is intended for use in a satellite communication transmitter at 11 GHz.

• Specifications: The module is capable of delivering up to 44 dBm output power, Power Added Efficiency (PAE) in the range of 15 to 25 percent and a P1DB of 23dBm.

• Utilized a high-performance Wolfspeed GaN-on-SiC MMIC (CMPA601C025F), selected for its ability to operate efficiently at Ku-band frequencies with high output power and linearity.

• Designed on RT/duroid® 6010 high-frequency laminate (Dk=10.2) to ensure characteristic impedance of the input and output microstrip transmission line, low dielectric loss and stable performance at 11 GHz.

• Included instructions for the PCB manufacturer to drill a PCB cavity beneath the IC footprint to meet physical dimensions and thermal management requirements of the GaN device, ensuring efficient heat transfer and mechanical stability.

• With a module like this is possible to achieve a received power of -82.26 dBm in a receiver station that is at 1000 km assuming the following link:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cdcortesr/RF-Power-Amplifier-11GHz-/refs/heads/main/LinkCalculation.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/cdcortesr/RF-Power-Amplifier-11GHz-/refs/heads/main/LinkCalculation.png">
  <img alt="a." src="https://raw.githubusercontent.com/cdcortesr/RF-Power-Amplifier-11GHz-/refs/heads/main/LinkCalculation.png">
</picture>

• An Energy per bit to noise power spectral density ratio of 8.70 dB allows for a BER of 10^-4 using a modulation scheme like QPSK. Furhter BER reduction can be obtained by using Forward Error Correction such as Reed Solomon Codes.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/PSK_BER_curves.svg/800px-PSK_BER_curves.svg.png">
  <source media="(prefers-color-scheme: light)" srcset="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/PSK_BER_curves.svg/800px-PSK_BER_curves.svg.png">
  <img alt="a." src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/PSK_BER_curves.svg/800px-PSK_BER_curves.svg.png">
</picture>


