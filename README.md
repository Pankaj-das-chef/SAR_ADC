# 4-bit 10 MS/s SAR ADC (Analog Design in Tanner EDA)

This project implements a **4-bit, 10 MS/s Successive Approximation Register (SAR) ADC** using **transistor-level circuit design in Tanner EDA**.  
The design uses a **monotonic capacitor switching procedure** for reduced switching energy and efficient conversion.



## Features
- **4-bit SAR ADC** designed at the **transistor level**.  
- **Monotonic capacitor switching** reduces power compared to conventional switching.  
- **Dynamic comparator** designed for high-speed and robust decision-making.  
- **Binary-weighted capacitor DAC array** for accurate charge redistribution.  
- **Control circuitry** to handle switching sequence, comparator triggering, and conversion timing.  
![WhatsApp Image 2025-09-09 at 6 40 01 PM](https://github.com/user-attachments/assets/891da566-64ab-4fbc-8f8d-4168f1ce8133)
![WhatsApp Image 2025-09-09 at 6 42 06 PM](https://github.com/user-attachments/assets/0cbf1dda-f1d6-4049-a861-460bdced4459)
![WhatsApp Image 2025-09-09 at 6 42 26 PM](https://github.com/user-attachments/assets/0bc7ce4e-b94f-4723-9bc0-24c13cc95aaa)
![WhatsApp Image 2025-09-09 at 6 44 09 PM](https://github.com/user-attachments/assets/00ebb331-f6b5-4abc-82b1-7c31bdd344a3)
![WhatsApp Image 2025-09-09 at 6 47 27 PM](https://github.com/user-attachments/assets/e647e02d-d623-4d4c-8365-5646ed9b91ee)
![WhatsApp Image 2025-09-09 at 6 47 58 PM](https://github.com/user-attachments/assets/b9b61272-066b-4608-87ed-8e8864d8ebe7)
![WhatsApp Image 2025-09-09 at 6 48 38 PM](https://github.com/user-attachments/assets/c3e432a6-9f79-46fa-8b2f-c59d6de1ce38)
![WhatsApp Image 2025-09-09 at 6 48 59 PM](https://github.com/user-attachments/assets/15e1f07d-fb02-4dbb-bd05-dcde8dca93c6)
![WhatsApp Image 2025-09-09 at 6 49 16 PM](https://github.com/user-attachments/assets/54f077d1-39ed-4885-8a18-25da9817ed2b)

---

## Simulation Results
- **Conversion Speed**: ~10 MS/s  
- **Switching Energy**: Lower due to monotonic capacitor switching procedure.  
- **Comparator Performance**: Robust decision accuracy across all 4-bit codes.  
- **DAC Linearity**: Verified through transient simulations in Tanner.  

---

## Tools Used
- **Design Tool**: Tanner EDA (S-Edit, T-Spice)  
- **Simulation**: T-Spice transient and AC analysis  
- **Visualization**: Tanner waveform viewer  

