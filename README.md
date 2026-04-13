# ventilator-aligner-ac

VentilatorAligner-AC is a mobile application developed in **.NET MAUI 8.0**, designed to streamline and accelerate the balancing process for radial oil coolers fans used in **Atlas Copco** compressor . 

The primary goal of the app is to **minimize the overall time** required for fan balancing.

## Installation Guide
1. **Download:** Navigate to the [Releases](../../releases) section and download the latest `.apk` file.
2. **Transfer:** If you downloaded it on a PC, transfer the file to your Android device.
3. **Install:** - Open the `.apk` file on your phone.
   - If prompted, allow "Installation from unknown sources" in your security settings.
  

 ## Balancing Procedure

**IMPORTANT:** Always follow all safety protocols when working with rotating machinery.

1. **Preparation:** Mark 3 points on the fan, spaced exactly **120° apart** (as shown in the app's diagram).
2. **Initial Measurement (V0):** Run the fan and measure the initial vibration level. Enter this value into the **V0** field.
3. **Trial Weight (MT):** Weigh a small test weight in grams and enter it into the **MT** field.
4.  - It is recommended to start with a weight between **10g and 15g**.
    - The lower the initial vibrations, the heavier the trial weight should be (and vice-versa) to achieve accurate results.
5. **Sequential Testing (V1, V2, V3):**
   - Attach the trial weight to **Point 1**, run the fan,measure the vibration. Record the vibration in **V1**.
   - Move the same weight to **Point 2**, run the fan,measure the vibration. Record the vibration in **V2**.
   - Move the same weight to **Point 3**, run the fan,measure the vibration. Record the vibration in **V3**.
6. **Calculation:** Press the **Výpočet** (Calculate) button.
7. **Result:** The app will display the **Final Weight** (Hmotnosť) and the **Angle** (Uhol) where the permanent counterweight should be mounted.
8. **Verification:** Apply the calculated weight, remove the trial weight, and run the fan to verify the balance.
9. **Reset:** Use the reset button to clear all fields for a new measurement.
10.**Fine-tuning:**  If the vibrations are still above the desired limit, repeat the process as many times as needed to achieve perfect balance.

<p align="center">
  <img src="https://github.com/user-attachments/assets/53910bef-de3a-4ed0-a021-412dcaa726f5" width="300">
</p>
*Main screen in light mode.*

<p align="center">
  <img src="https://github.com/user-attachments/assets/96f4936a-4c8b-42e9-8c34-92368c044dab" width="300">
</p>
 *Main screen in dark mode.*
