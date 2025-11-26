# UsbSens3 (Futek USB-To-Serial analysis tool)
Tool for reading, recording and graphing data from **Futek** sensors over a serial-to-USB (Futek-USB220) connection. 

-----

##  Getting Started

### Prerequisites

1.  A compatible **Futek sensor** (tested with UDB220 and LLB400).
2.  A **serial-to-USB adapter** (I.e Futek usb220)
3. Python 3.10. (Needed in order to set the samplerate)
   
#### **1. Python**

  * **Requirement:** **Python 3.10** (or a compatible version).
  * **Notes:** This script is developed and tested against Python 3.10. While other Python 3 versions might work, this version is recommended for full compatibility.
* Can be installed directly via the windows store.
-----

#### **2. Python Packages**

The following third-party Python package must be installed:

  * **Package:** **pythonnet**
      * **Purpose:** This is the core package used to interact with the FUTEK_USB_DLL.dll dynamic library directly from Python. 
      * **Installation:**
        ```bash
        pip install pythonnet
        ```
### Usage

1.  **Download:** Navigate to the **[Releases](https://github.com/MrVasquez96/Futek-UsbSens3/releases)** page and download the latest binary package for your operating system (`.zip` for Windows, `.tar.gz` for Linux).
2.  **Extract:** Unzip or un-tar the downloaded file to a location on your computer.
3.  **Run:**
      * **Windows:** Double-click the `futek-serial-usb.exe` file.
      * **Linux:** Open a terminal, navigate to the extracted folder, and execute the binary with `./futek-serial-usb`.

> ⚠️ **Notice:** \
          - Depending on your operating system's security settings and how the serial port is managed, you **may need to run the application with administrative privileges** (`Run as administrator` on Windows, or using `sudo` on Linux). \
          - Changing samplerate is only to do possible via windows.
-----

## Tested Devices

This utility has been specifically developed and tested against the **USB220** (Universal Digital Display) with **LLB400** (Load Button Sensor)

While it may work with other Futek devices that use a similar serial protocol, **compatibility is not guaranteed**.


