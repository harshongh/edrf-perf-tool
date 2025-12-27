# edrf-perf-tool
EDRF Performance Analysis Tool
**Overview**

**EDRF Performance Tool (EdrfPerfTool.exe)** is a Windows diagnostic utility that helps EDRF Internal team to  understand how xclient.exe impacts system performance.

**The tool collects:**

  - CPU usage patterns
  - File read/write activity
  - Process interaction statistics

Based on this data, it provides visual insights and exclusion recommendations to help reduce performance impact safely.

⚠️ This tool provides recommendations only. No exclusions are applied automatically.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Key Features**

 - Live CPU and File I/O charts
 - Top processes, files, and extensions
 - Exclusion recommendations with confidence score
 - Dark / Warm / Normal UI modes
 - Export reports in JSON and CSV
 - GUI and CLI in the same executable
 - No kernel drivers, no file content collection

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Requirements**

 - Windows 7 / Server 2008 or later
 - Administrator privileges

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Installation**
**Option 1: MSI (Recommended)**

 1. Download EDRF_Performance_Tool.msi
 2. Double-click to install
 3. Tool installs under: C:\Program Files\EDRFPerfTool\

**Option 2: Standalone EXE**

 1. Download EdrfPerfTool.exe
 2. Run as Administrator

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Running the Tool (GUI)**

 1. Right-click EdrfPerfTool.exe
 2. Select Run as administrator
 3. The dashboard opens automatically

**UI Options**

 - Theme Selector: Normal / Dark / Warm
 - Live Charts: CPU & File I/O
 - Exclusion Panel: Suggested exclusions
 - Export Buttons: JSON / CSV

**Running the Tool (CLI)**
EdrfPerfTool.exe --duration 10

Options:
--duration <minutes> : Run duration (1–30)
--gui : Launch graphical interface

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Output Files**

By default, reports are saved to: C:\ProgramData\EDRF_Team\

**Files:**

 - Perf.json
 - TopProcesses.csv

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Security & Privacy**

 - No file contents collected
 - No registry modifications
 - No exclusions applied automatically
 - Uses Windows ETW (Event Tracing for Windows)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Uninstall**

 - Via Control Panel → Programs
 - silent uninstall (see below)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Support**

Internal EDRF teams only.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------


                                                © ⚡Created By 🤓 Harsh Gautam 🧠⚡


