# Water-tank-refill-automation

I made a simple project to add in my learning automation,
an Automated Water Tank Refilling System using Siemens S7-1500 PLC in TIA Portal v18 and WinCC RT Advanced for SCADA & HMI visualization! 🚀

🔹 Project Overview:

The system automatically maintains the water level using three sensors:
✅ Low-Level Sensor (<20%) → Activates the pump to start refilling.
✅ Medium-Level Sensor (20-90%) → Monitors normal operation.
✅ High-Level Sensor (>90%) → Stops the pump and opens the drainage valve to prevent overflow.

🔹 How It Works:

🔹 When the low-level sensor detects low water, the pump starts to fill the tank.
🔹 As the level reaches 90%, the high-level sensor activates, stopping the pump and opening the drainage valve to regulate water flow.
🔹 The process repeats automatically, ensuring efficient water management without manual intervention.
