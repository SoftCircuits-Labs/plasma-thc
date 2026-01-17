# plasma-thc
A fully isolated Plasma THC which an be used with any CNC control system which accepts torch Up and Down signals, eg. MACH 3, LinuxCNC, CNConv, Planet CNC etc

The Plasma THC has 2 parts - PTHC-Driver (controller unit) and the PTHC-Probe (for voltage sensing), which are connected via an optical cable.
- PTHC-Probe is installed close to the plasma source. It connects to plasma voltage and runs from a 12VDC supply (provided with the device).
- PTHC-Driver unit is installed closer to the CNC controller. It gives signal to the CNC controller for torch UP, DOWN and ARC OK. It operates via a 12VDC supply (provided with the device)
- These 2 modules are connected via an optical cable which suppresses any high voltage electrical interference, EMI, spikes etc, which are very common in plasma CNC and can damage the
plasma CNC.
