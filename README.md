# Bachelor project work
In progress. Building a small lab safety system. Sensor nodes (Raspberry Pi Pico W) send JSON over TCP to a Python server on my Linux VM. The server checks simple rules and sends commands back (flash LED, fan/beacon, safe power-off via contactor + E-STOP). Messages are newline-JSON for easy parsing.

📁 Bachelor project work
│
├── 📁 PCB Design
│   ├── 📁 PCB-A2-WaterLeak_buuzzer-projectwork
|   ├── 📁 PCB-A1-smoke_Fan-projectwork
|   ├── 📁 PCB-S2-WaterLeak-projectwork
|   ├── 📁 PCB-S1-smoke-projectwork
│      ├── PCB-S1-smoke-projectwork.kicad_pro
│      ├── PCB-S1-smoke-projectwork.kicad_sch
│      ├── PCB-S1-smoke-projectwork.kicad_pcb
│      ├── schematic.pdf 
|      ├── PCB Layout.pdf 
│      └──  3D_render.png                                         
│
├── 📁 firmware
│   ├── main.py                         
│                                                 
├── 📁 docs
│   ├── description.txt                  
│   ├── report.pdf                                    
│
├──📁 media
   ├── board_3D_view.png
   └──  test_setup.jpg
   

                         
