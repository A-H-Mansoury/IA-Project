## Design and Simulation of a Discrete Manufacturing Automation System
This project involved the comprehensive simulation and design of a fully automated discrete manufacturing plant using Factory IO. The system integrates robotics, sensor networks, and hardware interfaces. An advanced Human-Machine Interface (HMI) was developed in Ignition, with control logic implemented using Structured Control Language (SCL) in TIA Portal. OPC communication protocols were utilized for seamless system integration and real-time data exchange between components.

Here is a brief evaluation video of the system:

https://github.com/user-attachments/assets/83960f3a-f627-4672-894e-36fccc1c1b1b

A higher-quality version of the evaluation video is available [here](https://drive.google.com/file/d/1GPjAA34HsQMB4Q2VU7w9dvWRUbjKnnnz/view?usp=sharing).

  ## Scenario
  In this system, raw and processed goods in blue, green, and metallic colors enter a production line. Unprocessed items are separated for machining and returned to the line. A sorting station categorizes products into three lines, followed by a packaging area. Orders are placed via hardware and software HMIs, queued, and processed sequentially. Packaged orders are then sent to storage. A PID-controlled tank manages flow, with setpoints and disturbances applied through HMIs.
  
  ## License
  This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
