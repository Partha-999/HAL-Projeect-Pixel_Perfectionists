# PP-HAL-3.0
Office Seat Planner & Resource Optimization
Overview
The Office Seat Planner is a web-based tool that dynamically allocates seats to employees based on a First-Come-First-Serve (FCFS) system. It helps efficiently manage seating arrangements in an office, optimizing the usage of available office space. Additionally, the system integrates IoT sensors to monitor and manage power consumption and water usage in real time. This optimization reduces overall office resource consumption, leading to significant cost savings.

The project focuses on:

Efficient seating arrangement based on employee preferences.
IoT-based monitoring of energy and water usage.
Cost reduction through optimized space and resource usage.

Features
Dynamic Seat Allocation: Employees are assigned seats based on FCFS, ensuring efficient space usage and flexibility.
Shift-Based Resource Management: Energy and water consumption is tracked and optimized based on shifts and real-time employee presence.
IoT Integration: Power and water usage are monitored using IoT sensors, which only account for usage when employees are present, reducing wastage.
Cost Calculation: Real-time tracking of electricity and water consumption, with detailed cost reports showing savings.
Responsive Frontend: A user-friendly interface where employees can view available seats, book a seat, and see their shift timings.

Tech Stack
Frontend:

HTML
CSS
JavaScript (React.js)

Backend:

Node.js
Express.js
MongoDB (for dynamic storage of employee, seating, and resource data)

IoT Integration:

Python (for IoT sensor management and data collection)

IoT Sensor SimulatioN:
While simulating IoT sensor data, make sure you have a script to simulate power and water consumption based on employee occupancy. 

Usage:

Seat Allocation:
Employees can log into the web page and view available seats.
First-Come-First-Serve (FCFS) logic is used to allocate seats dynamically.
Once a seat is allocated, the system updates the seating arrangement.

Resource Management:
IoT sensors track real-time energy (kWh) and water consumption based on employee presence.
Shift-based allocation: Only employees on shift are considered for energy/water consumption, reducing wastage.

Cost Calculation:
The system provides a real-time breakdown of energy and water costs based on the number of employees present.
Detailed cost reports are generated, showing how much was saved by implementing the system with IoT-based monitoring.

How IoT Sensors Contribute to Cost Reduction:

Power Consumption: The system uses IoT sensors to detect the presence of employees. It tracks the energy consumed by the lights, fans, AC, and computers only when employees are in the office.
Water Consumption: IoT sensors monitor water usage based on the occupancy of the office, ensuring water is only consumed when employees are present (e.g., in toilets, kitchens, etc.).
By using real-time data, we are able to significantly reduce wastage and optimize the consumption of resources, leading to cost savings.

Conclusion:

The Office Seat Planner project leverages innovative technologies like IoT sensors and dynamic seat allocation to address some of the most pressing challenges faced by modern workplaces: space optimization and resource management. By implementing a First-Come-First-Serve (FCFS) seat allocation strategy, this tool maximizes the utilization of office space while reducing real estate costs.

Additionally, the integration of IoT sensors plays a crucial role in energy and water consumption optimization. By dynamically adjusting the usage of these resources based on employee occupancy, the system significantly reduces wastage, leading to considerable cost savings for the company.

The system is designed to be scalable, meaning it can easily accommodate growth, whether you're managing a small team or planning for a 3000-employee workforce. It also ensures that real-time data can be used for proactive decision-making, improving both operational efficiency and sustainability within the workplace.

In summary, this project not only addresses the immediate need for effective seat management but also extends its impact to resource optimization, enabling companies to save on costs, reduce their environmental footprint, and scale effectively in the long run. It is a perfect fit for companies looking to merge workplace efficiency with sustainability in an increasingly data-driven world.
