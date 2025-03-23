# SolidWorks Downtown Add-in  

## Overview  
SolidWorks Downtown is a customizable add-in that allows users to manage macros, links, documents, external tools, and notifications—all controlled via an Excel database.  

## Installation  

1. **Download** all files from GitHub.  
2. **Register** the `.dll` file.  Example script for register: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\RegAsm.exe /codebase "%~dp0\bin\Debug\Downtown Add-in.dll`
3. **Open SolidWorks** and navigate to:  
   - `Tools → Downtown Add-in → Import/Upload Database`  
4. **Restart SolidWorks**.  

## Usage  

- Use the **Excel database** to manage:  
  - **Documents** (file paths)  
  - **Links**  
  - **Executable files (.exe)**  
  - **Images** (must be **32×32 PNG**—provide file paths)  

- Store the **Excel database** in a **shared folder** to ensure all users access the same content.  

## Compatibility  
✅ **Supports all SolidWorks versions**.  

## Licensing  

- All built-in utilities in the add-in are **free**.  
- The free version allows users to define:  
  - **2 macros**  
  - **2 documents & links**  
  - **2 external apps & tools**  
  - **2 notifications**  

- A licensing system will be introduced in the **full release**, enabling **unlimited** items per category.  
- Interested in testing? Request a **free license key** for feedback purposes!  

## Contributing  
Feel free to submit issues, feature requests, or contribute to the project!  

## License  
[Specify your license here]  

---

Let me know if you need any refinements! 🚀  
