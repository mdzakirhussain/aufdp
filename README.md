# AU-FDP
Faculty Development Programme on Design to Device: A 3-day Hands-on Journey in VLSI &amp; FPGA June 18 – 20, 2026 at Anurag University


- [Arty-A7-100-Master.xdc](https://github.com/Digilent/digilent-xdc/blob/master/Arty-A7-100-Master.xdc)
- Adding Board files

```
Windows
System Path (Manual Install): C:\Xilinx\Vivado\2025.2\data\boards\board_files
(Assuming the default installation directory. If you installed it on another drive, replace C:\ accordingly).

Board Store Downloads (GUI Install): %APPDATA%\Xilinx\Vivado\2025.2\xhub\board_store\
(This is where Vivado saves boards you download directly via the "Vivado Store" tab).

Linux
System Path (Manual Install): /opt/Xilinx/Vivado/2025.2/data/boards/board_files or /tools/Xilinx/Vivado/2025.2/data/boards/board_files
(Depending on where you set your root installation directory).

Board Store Downloads (GUI Install): ~/.Xilinx/Vivado/2025.2/xhub/board_store/

Tip for Adding Custom Boards (e.g., Digilent):
If you are manually adding third-party board files, navigate to the System Path mentioned above. If the board_files folder does not exist inside the boards directory, you can simply create it and drop your extracted board folders inside. Restart Vivado for the new boards to appear in the project creation wizard.

```
