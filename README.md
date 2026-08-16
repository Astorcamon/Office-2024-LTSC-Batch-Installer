<div align="center">
   
<!-- Badges - Replace projectName with the name of the project also, change or add the link-->

[![Visits](https://visitor-badge.laobi.icu/badge?page_id=Astorcamon.Office-2024-LTSC-Batch-Installer)](https://github.com/Astorcamon/Office-2024-LTSC-Batch-Installer)
[![Downloads](https://img.shields.io/github/downloads/Astorcamon/Office-2024-LTSC-Batch-Installer/total)](https://github.com/Astorcamon/Office-2024-LTSC-Batch-Installer/releases)
[![Latest Release](https://img.shields.io/github/v/release/Astorcamon/Office-2024-LTSC-Batch-Installer)](https://github.com/Astorcamon/Office-2024-LTSC-Batch-Installer/releases/latest)
[![Release Date](https://img.shields.io/github/release-date/Astorcamon/Office-2024-LTSC-Batch-Installer)](https://github.com/Astorcamon/Office-2024-LTSC-Batch-Installer/releases)

</div>

---

# Office 2024 LTSC - Batch Installer
This is a customizable, interactive, and user‑friendly batch‑based installer for [Microsoft Office 2024 LTSC](https://learn.microsoft.com/en-en/office/ltsc/2024/overview).<br/>
The script is released under the [MIT License](./LICENSE.md), while Microsoft Office is covered by its own [Microsoft license](https://learn.microsoft.com/en-en/office/volume-license-activation/plan-volume-activation-of-office).

---

## Features

- Selectable Office Apps to install
- Selectable language for Office Apps
- Download and installs only the Apps you want

#### Predefined Settings (Non modifiable)  
- Architecture: x64  
- Product: ProPlus2024Volume  
- Channel: PerpetualVL2024  
- Updates: Enabled  
- EULA: Accepted  

---

## How to install - Office 2024 LTSC

### Using Setup-Office2024-LTSC.bat Installer (The easiest way)

This method allows you to interactively select which Office applications and language to install.

**First steps:**

1. Download and extract the files from the latest release of [Setup-Office2024-LTSC.zip](https://github.com/Astorcamon/Office-2024-LTSC-Batch-Installer/releases/latest)
2. Download and run the official [Office Deployment Tool (ODT)](https://www.microsoft.com/en-us/download/details.aspx?id=49117)  
3. Copy `Setup.exe` to the same folder as `Setup-Office2024-LTSC.bat`

**Next steps:**

1. Run `Setup-Office2024-LTSC.bat` **as Administrator**.
2. Select the applications to install by entering their number and press Enter.
   - Each application shows its status as **=1 (Enabled)** or **=0 (Disabled)**.
3. Enter **I** to begin the installation.
4. Select the language to install by entering its number and press Enter.

---

## Alternative methods

<details>
<summary> Click here to expand</summary>

### Using ODT (The official method)

This method uses Microsoft’s official configuration and deployment workflow.

**First steps:**

1. Download and run the official [Office Deployment Tool (ODT)](https://www.microsoft.com/en-us/download/details.aspx?id=49117)

**Next steps:**

1. Generate a custom XML configuration using the online [Configuration Tool](https://config.office.com/deploymentsettings)
2. Save the generated XML file in the same folder as `setup.exe`.
3. Open **Command Prompt as Administrator** in that folder.
4. Download the Office installation files: `setup.exe /download configuration.xml`
5. Once the download completes, install Office: `setup.exe /configure configuration.xml`

Learn more: https://learn.microsoft.com/en-us/office/ltsc/2024/deploy

### Using OTP (The AIO Tool for Office)

The Office Tool Plus integrates Microsoft’s official deployment workflow into a third‑party tool with a full graphical UI and more features.

Learn more: https://www.officetool.plus/

</details>

---

## Screenshots

<img src="screenshots/Menu.png" width="300"> <img src="screenshots/Language.png" width="300" height="605">

---

## Contributions

<Table>
   <th>PayPal</th>
   <th>GitHub</th>
   <th>Ko-Fi</th>
  <tr>
    <td><a href="https://www.paypal.com/donate?hosted_button_id=P2C76DEXQEEFQ"><img src="https://img.shields.io/badge/Donate-blue?style=flat&logo=paypal" width="115"/></a></td>
    <td><a href="https://github.com/sponsors/Astorcamon"><img src="https://img.shields.io/badge/Sponsor-404040?style=flat&logo=GitHub-Sponsors" width="135"/></a></td>
    <td><a href="https://ko-fi.com/astorcamon"><img src="https://img.shields.io/badge/Donate-gray?style=flat&logo=kofi" width="128"/></a></td>
  </tr>
</table>
