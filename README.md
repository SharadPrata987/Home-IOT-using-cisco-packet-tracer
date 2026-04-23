# Home-IOT-using-cisco-packet-tracer
# Smart Home IoT Simulation

## 📌 Overview
This project is a Cisco Packet Tracer simulation of a Smart Home IoT (Internet of Things) network. It demonstrates how various everyday household devices can be wirelessly connected, monitored, and controlled centrally through a dedicated IoT registration server using a web-based smartphone interface.

## 🏠 Network Topology
The simulation maps out a floor plan and consists of:
* **IoT Server:** Hosts the central web interface and registration server for device management (IP: `10.1.2.2`).
* **Home Gateway/Router:** Provides the wireless network for all smart end-devices to connect to.
* **Core Networking:** A combination of a router and a switch bridging the home network to the server across different subnets (`10.1.1.0/24` and `10.1.2.0/24`).

## 🔌 Connected Smart Devices
The following IoT devices are configured in the simulation and can be controlled via the central web interface:
* 🚪 **Smart Door & Garage Door:** Remotely lock/unlock and open/close.
* 💡 **Smart Lamp:** Toggleable lighting with dimming capabilities.
* 🌬️ **Ceiling Fan:** Adjustable speed control (Off, Low, High).
* 🌡️ **Temperature Monitor:** Real-time environmental temperature tracking.
* 🍹 **Smart Appliance (Juicer):** Remote On/Off toggle.

## 🚀 How to Run the Simulation
1. Download and install **Cisco Packet Tracer**.
2. Clone or download this repository to your local machine.
3. Open the `HomeIOT.pkt` file in Cisco Packet Tracer.
4. In the logical workspace, click on the **Smartphone** device.
5. Go to the **Desktop** tab and open the **Web Browser**.
6. Enter the IoT Server URL/IP: `http://10.1.2.2/home.html`.
7. Use the interface to interact with and toggle the smart devices in real-time.

## 🛠️ Prerequisites
* Cisco Packet Tracer 
