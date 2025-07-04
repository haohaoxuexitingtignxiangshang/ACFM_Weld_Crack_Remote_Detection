# ACFM_Weld_Crack_Remote_Detection
基于STM32F407的智能焊缝裂纹远程检测系统 工业级解决方案，用于起重机伸缩臂/压力管道/航空航天结构的应力腐蚀与疲劳裂纹检测
├── Hardware/                  # PCB designs & schematics
│   ├── Probe_Design/          # U-core sensor assemblies
│   ├── Instrumentation/       # Signal processing circuits
│   └── STM32_Peripherals/     # MCU interface designs
├── Firmware/                  # STM32 embedded code
│   ├── Core/                  # ARM Cortex-M4 drivers
│   ├── Signal_Processing/     # Wavelet denoising algorithms
│   ├── Communication/         # SPI/UART/LoRa protocols
│   └── Data_Management/       # QFile storage system
├── Desktop_App/               # QT-based control software
│   ├── Instrument_Control/    # Device management
│   ├── Visualization/         # Real-time data display
│   └── Serial_Interface/      # Communication module
├── Cloud_Platform/            # AngularJS web application
│   ├── Server/                # Data processing backend
│   ├── Dashboard/             # Highcharts visualization
│   └── API/                   # RESTful interfaces
├── Documentation/             # Technical specifications
│   ├── Performance_Reports/   # Validation data
│   ├── User_Manual/           # Operation guidelines
│   └── Research_Papers/       # Algorithm references [17]
└── Tests/                     # Validation scripts
