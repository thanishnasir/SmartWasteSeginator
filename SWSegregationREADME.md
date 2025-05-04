# Smart Waste Segregation using Arduino Nano BLE

## 📌 Project Overview
An Edge AI system that automatically classifies and sorts waste into categories (cardboard, plastic, wet waste) using Arduino Nano 33 BLE Sense, improving recycling efficiency through machine learning.

## 👥 Team Members & Contributions
| Member | Role | Key Contributions |
|--------|------|------------------|
| **Thanish Nasir** (24502) | Data & Implementation | - Data collection <br>- Data cleaning <br>- System implementation |
| **Sathvik** (24626) | Hardware Specialist | - Model deployment on NanoBLE 33 <br>- Hardware integration <br>- Power optimization |
| **Sindhura** (22706) | ML Engineer | - Model building using Edge Impulse <br>- Research & development <br>- Performance tuning |

## ✨ Key Features
| Feature | Specification |
|---------|--------------|
| Accuracy | 92.86% (100% validation) |
| Model Type | Quantized (int8) |
| Latency | ~570ms |
| Resource Saving | 18% less RAM, 15% less ROM |
| Operation | Offline with low power |

## 💻 Software Requirements
```plaintext
- Edge Impulse Studio
- Arduino IDE (v2.0+ recommended)
- Required Libraries:
  • ArduinoBLE
  • Edge Impulse Arduino
  • OV7675 Camera Library
  • Servo (for actuation)