# Inventory-Management
**Inventory Management System using FPGA**
**Introduction**
This repository contains the Verilog implementation of an Inventory Management System using FPGA Artix-7. The system aims to efficiently manage large-scale commercial warehouses with FPGA hardware interference for space management and classification. It offers low-cost, power-efficient storage organization as a competitive alternative to software-based systems.

**Features**
1. **Password Security:** The system employs an 8-bit long decimal number password verification mechanism to ensure unauthorized access is prevented. After three failed attempts, the system alerts the authorities, requiring a Master Password for access.
2. **Product ID Encoder:** Users can input a product's ID to obtain its designated location in the warehouse. The system allocates the product's location based on its priority, floor, section, sub-section, and shelf.
3. **Inventory Management:** Users can add or subtract items based on the number of orders. Priority items are managed first, ensuring efficient shelf utilization. The system updates and displays the current quantities, handling overflow and underflow cases.
4. **Warehouse Layout:** The warehouse consists of three floors, each with five sections, further divided into five sub-sections. Each sub-section contains five shelves, with each shelf capable of holding 75 units of a unique product. The system supports a total of 125 unique products and 9375 units.
**Hardware and Software**
- FPGA Hardware: Artix-7 4DDR (XC7A100TCSG324-1)
- EDA Tool: Vivado Xilinx 2014.2 Version/2021 Version
**Installation and Usage**
1. Clone the repository to your local machine.
2. Open the project in Vivado and synthesize the Verilog code for the FPGA.
3. Upload the synthesized bitstream to the FPGA.
4. Connect the appropriate input devices and a console for output.
5. Power on the FPGA and run the system.
6. Follow the on-screen instructions to access and manage the inventory.
Thank you for using our Inventory Management System using FPGA. We hope it simplifies and optimizes your warehouse administration. Happy managing!
