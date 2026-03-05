# The-Core-Streamer-A-Minimalist-Analog-to-Serial-EKG-Bridge

The Core-Streamer is a high-fidelity biometrics interface designed to turn the human heart into a live data source. Unlike consumer smartwatches that give you a simplified heart rate number, this project captures the raw electrical waveform (the EKG) and streams it directly to a computer via high-speed Serial communication. It’s a "black box" approach to medical DIY: no screens, no buttons, just pure signal integrity.

Once the project is fully assembled, simply attach the pads to your body as indicated and open up the Arduino serial plotter to view your EKG.
![Image 2](https://github.com/user-attachments/assets/a7ff064f-0d95-4b1f-a0f2-75a367d96beb)

I made this project to better understand electronics, and human anatomy. The EKG is cool for many ways, but it stands out to me in the way that it bridges, the electronics of our modern world to the electrical impulses of the human body.

Screenshot Of 3D Model:
<img width="2940" height="1912" alt="Image 3-5-26 at 12 27" src="https://github.com/user-attachments/assets/b47f9793-ffd9-48cf-8aac-6f32b0a8b15c" />
<img width="2940" height="1912" alt="Image 3-5-26 at 12 26" src="https://github.com/user-attachments/assets/6b49c013-28ab-4a2d-a8a1-4400b4580e60" />

Wiring Diagram:
<img width="1862" height="1018" alt="Image 3-5-26 at 12 56" src="https://github.com/user-attachments/assets/21aad6c4-70f2-45c9-b03f-e96121c6b957" />

[BOM.csv](https://github.com/user-attachments/files/25776720/BOM.csv)
| Item | Description | URL | Quantity | Unit Price |
| :--- | :--- | :--- | :--- | :--- |
| **Arduino Nano** | Microcontroller | [Link](https://a.co/d/0fQkU1aS) | 1 | $25.70 |
| **AD8232 Module** | ECG Analog Front-End | [Link](https://www.digikey.com/short/b8dpq74t) | 1 | $24.41 |
| **Electrode Leads** | 3.5mm Connector Leads | [Link](https://www.amazon.com/dp/B0CJ7FMSP4?ref_=cm_sw_r_cp_ud_dp_W29NXBJ8Z9SBM9XCGJ9G) | 1 | $31.32 |
| **PLA Basic** | 3D Printing Filament | [Link](https://us.store.bambulab.com/products/pla-basic-filament) | 1 | $5.00 |
| **Hardware/Misc** | Wire, Solder, etc. | N/A | 1 | $5.00 |
| **Total** | | | | **$91.43** |

SAFETY WARNING: This device is for educational and hobbyist purposes only. It is NOT a medical diagnostic tool. To prevent electrical shock, ONLY power this device via a battery or a laptop that is NOT plugged into a wall outlet while the electrodes are attached to a person.
