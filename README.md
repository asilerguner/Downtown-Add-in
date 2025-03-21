![Uploading image.png…]()
# Downtown Add-in for SOLIDWORKS

## Overview
The **Downtown Add-in** is a fully customizable framework designed to enhance **SOLIDWORKS** by centralizing macros, links, documents, and external tools. Unlike traditional add-ins that require hardcoded configurations, Downtown allows real-time customization via an **Excel database**.

## Features
- **Centralized Hub**: Manage macros, links, documents, and external applications in one place.
- **Excel-Based Configuration**: Update settings, commands, and tools dynamically without modifying code.
- **Push Notifications**: Display critical messages to users before SOLIDWORKS launches.
- **Seamless Integration**: Launch external applications like **analysis tools** or **PDM integrations** effortlessly.
- **Customizable UI**: Supports **32x32 images** for a visually enhanced user experience.
- **Easy Import**: Use **Tools > Import Database** to quickly configure the add-in.

## Installation
1. **Download the Downtown Add-in** and place the files in your SOLIDWORKS add-ins directory.
2. **Launch SOLIDWORKS** and enable the add-in via `Tools > Add-Ins`.
3. **Configure your database** by modifying the provided Excel file.
4. **Import database** via `Tools > Import Database`.

## How to Use
### Managing Macros & Links
- Open the Excel database and navigate to the relevant sheet.
- Add or update macros, file paths, or links.
- Save the Excel file and restart SOLIDWORKS to apply changes.

### Using Push Notifications
- Admins can define messages in the database.
- Notifications appear when SOLIDWORKS starts, ensuring critical updates reach users.

### Customizing UI
- Assign **32x32 images** to commands for a professional interface.
- Icons must be stored in the specified directory and referenced in the Excel database.

## Support
For issues, feature requests, or further customization, contact **downtown.addin@gmail.com**.
