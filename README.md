ESP32 Mobile-Controlled LED

This project demonstrates how to control an onboard LED on the ESP32 using a mobile phone via Wi-Fi.

🔧 Project Overview

Using an ESP32 board connected to a mobile hotspot, we hosted a simple web server. Through this server, users can turn the built-in LED ON or OFF using their phone's browser.

📡 Features

ESP32 connects to a mobile hotspot.

Web interface hosted on the ESP32 itself.

LED control via browser buttons (ON/OFF).

🛠️ Hardware Used

ESP32 development board

Mobile phone (hotspot + browser)

Micro USB cable

🌐 How It Works

ESP32 connects to your mobile hotspot using predefined SSID and password.

It starts a web server with two buttons: Turn ON and Turn OFF.

When you press a button from your phone browser, the ESP32 receives the request and switches the LED accordingly.
