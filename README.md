# Asus Vivobook M3500QC/M3500QA OLED ICC Profiles

This repository contains the default ICC profiles for the **Asus Vivobook M3500QC OLED** and **M3500QA OLED** laptops. These profiles are factory-calibrated and provided by Asus through the **MyASUS Splendid Version V2.0.0.145** utility on Windows.

## Why This Repository Exists

If you're using Linux, obtaining these profiles directly from Asus is not possible since they are distributed only via the Windows utility. This repository makes it easy for Linux users (and anyone else) to download and apply these ICC profiles to ensure accurate color calibration on their OLED displays.

## Source of the Profiles

The profiles were extracted from a Windows system after installing **MyASUS Splendid Version V2.0.0.145**. These are the same ICC profiles provided by Asus for the respective laptop models.

The original source can be found here:  
👉 [Asus Support - M3500QC](https://www.asus.com/supportonly/m3500qc/helpdesk_download/)  
Download **MyASUS Splendid** from the "Utilities" section.

## How to Apply the ICC Profiles

### On Windows

1. **Download the ICC profile**: Select and download the appropriate `.icc`/`.icm`  file from this repository.
2. **Open Color Management**:
   - Press `Win + R`, type `colorcpl`, and hit Enter.
3. **Add the ICC profile**:
   - Select your display from the list.
   - Check the box for **Use my settings for this device**.
   - Click **Add...**, navigate to the downloaded `.icc`/`.icm`  file, and click **Add**.
4. **Set as default**:
   - Select the newly added profile and click **Set as Default Profile**.

### On Ubuntu (or other Linux distributions)

1. **Open Color Management**:
   - Search for **Color** in your system settings.
2. **Add the ICC profile**:
   - Select your display.
   - Click **Add Profile** and after choose **Import Profile**, then navigate to the downloaded `.icc`/`.icm` file.
3. **Set as default**:
   - Choose the newly imported profile and set it as the default.

---

## Disclaimer

These ICC profiles are the factory defaults provided by Asus and may not be suitable for all displays or use cases. For professional color work, consider using hardware calibration tools.

---

### Contributions

Feel free to contribute if you have updated profiles, additional instructions, or improvements for Linux users.

---

### License

These ICC profiles are redistributed for personal and educational use. Original profiles are property of Asus.
