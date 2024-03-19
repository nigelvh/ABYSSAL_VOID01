# ABYSSAL.NETWORK VOID01 Hardware
This is a custom routing and switching learning platform based on the Raspberry Pi Compute Module 4 and the Microchip KSZ9477 gigabit ethernet switch.

The RPi provides for a standard linux platform to enable easy development, with simple scripting to configure the KSZ9477, and linux routing functions. This provides a lower barrier to entry learning platform, as compared to an embedded processor of some sort.

A CM4 Lite module is chosen, utilizing SD card based storage to simplify installation of the RPi OS.

A USB serial interface is provided to allow access to the RPi Serial Console, allowing for non-network based access/recovery.

The KSZ9477 switch is an inexpensive off-the-shelf switching chip, with a relatively rich feature set. Providing 5 PHY interfaces (4 ethernet jacks, and 1 connected to the onboard RPi), 1 RGMII interface (not used), and 1 SGMII interface (SFP Port).

A standard center-positive barrel jack accepts nominal 12V DC power. The input range should be roughly 8-26V. Onboard regulation generates 5V, 3.3V, 2.5V, and 1.2V rails necessary for the RPi and KSZ9477.

## REV A 202403
The first revision of the board. Designed in March 2024.
