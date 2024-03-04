# Milestone 2

**Table of Contents**
1. [Work Breakdown Structure](#work-breakdown-structure)
2. [Gantt Chart and Network Diagram](#gantt-chart-and-network-diagram)
3. [Detailed Requirements Document](#detailed-requirements-document)
4. [Fully Dressed Use Cases](#fully-dressed-use-cases)
5. [System Research](#system-research)
6. [API Descriptions](#api-descriptions)

## Work Breakdown Structure 
| **Task ID** |  **Task Name** | **Duration (Hours)** | **Start Date** | **Finish Date** | **Predecessors** |
| :---:|     :---:                                 |:---:|  :---:     |  :---:     |  :---:       |
|1     | Project Initiation                        | 12  | 02/11/2024 | 02/12/2024 | -            |
|1.1   | Define Project Scope and Objectives       | 6   | 02/11/2024 | 02/11/2024 | 1            |
|1.2   | Identify Project Stakeholders             | 6   | 02/12/2024 | 02/12/2024 | 1            |
|2     | Requirements Gathering Phase              | 90  | 02/13/2024 | 02/28/2024 | 1.1, 1.2     |
|2.1   | Define Data Collection Methodologies      | 30  | 02/13/2024 | 02/18/2024 | 2            |
|2.1.1 | Conduct Interviews with Stakeholders      | 15  | 02/13/2024 | 02/15/2024 | 2.1          |
|2.1.2 | Collect Survey Responses                  | 15  | 02/16/2024 | 02/18/2024 | 2.1          |
|2.2   | Analyze Legal and Compliance Requirements | 24  | 02/19/2024 | 02/21/2024 | 2.1          |
|2.2.1 | Review Privacy Regulations                | 12  | 02/19/2024 | 02/20/2024 | 2.2          |
|2.2.2 | Review Security Standards                 | 12  | 02/20/2024 | 02/21/2024 | 2.2          |
|2.3   | Requirements Analysis and Documentation   | 36  | 02/22/2024 | 02/26/2024 | 2.2          |
|2.3.1 | Analyze Stakeholder Input                 | 12  | 02/22/2024 | 02/23/2024 | 2.3          |
|2.3.2 | Analyze Interview Data                    | 12  | 02/24/2024 | 02/25/2024 | 2.3.1        |
|2.3.3 | Analyze Survey Data                       | 12  | 02/26/2024 | 02/27/2024 | 2.3.1        |
|3     | Design Phase                              | 140 | 03/01/2024 | 03/16/2024 | 2.3.3        |
|3.1   | Drone System Design                       | 90  | 03/01/2024 | 03/08/2024 | 3            |
|3.1.1 | Aerodynamics and Payload Capacity         | 30  | 03/01/2024 | 03/03/2024 | 3.1          |
|3.1.2 | Navigation and Control Systems            | 60  | 03/04/2024 | 03/08/2024 | 3.1          |
|3.2   | User Interface Design                     | 20  | 03/09/2024 | 03/15/2024 | 3.1.1, 3.1.2 |
|3.2.1 | Wireframing and Mockups                   | 8   | 03/09/2024 | 03/10/2024 | 3.2          |
|3.2.2 | Feedback and Revisions                    | 12  | 03/11/2024 | 03/12/2024 | 3.2          |
|3.3   | Database Design                           | 30  | 03/13/2024 | 03/16/2024 | 3.2.1, 3.2.2 |
|4     | Development Phase                         | 260 | 03/17/2024 | 04/21/2024 | 3.3          |
|4.1   | Drone Prototype Development               | 140 | 03/17/2024 | 04/07/2024 | 4            |
|4.1.1 | Mechanical Design and Fabrication         | 80  | 03/17/2024 | 03/28/2024 | 4.1          |
|4.1.2 | Software Development for Drone Operation  | 60  | 03/29/2024 | 04/07/2024 | 4.1          | 
|4.2   | Backend Development                       | 70  | 04/08/2024 | 04/14/2024 | 4.1.2        |
|4.2.1 | Implement Core System Logic               | 30  | 04/08/2024 | 04/10/2024 | 4.2          |
|4.2.2 | Integrate Database Functionality          | 20  | 04/11/2024 | 04/14/2024 | 4.2          |
|4.3   | User Interface Development                | 50  | 04/15/2024 | 04/21/2024 | 4.2.1, 4.2.2 |
|5     | Testing and Quality Assurance             | 100 | 04/21/2024 | 05/05/2024 | 4.3          |
|5.1   | Drone Testing and Calibration             | 50  | 04/21/2024 | 04/28/2024 | 5            |
|5.2   | Software Testing                          | 30  | 04/29/2024 | 05/02/2024 | 5.1          |
|5.3   | User Acceptance Testing                   | 20  | 05/03/2024 | 05/05/2024 | 5.2          |
|6     | Pilot Project                             | 70  | 05/03/2024 | 05/14/2024 | 5.3          |
|6.1   | Identify Pilot Project Location           | 5   | 05/03/2024 | 05/04/2024 | 6            |
|6.2   | Develop Execution Plan                    | 10  | 05/05/2024 | 05/06/2024 | 6.1          |
|6.3   | Execute Pilot Project                     | 55  | 05/07/2024 | 05/14/2024 | 6.2          |
|7     | Deployment and Rollout                    | 60  | 05/14/2024 | 05/27/2024 | 6.3          |
|7.1   | Training and Onboarding                   | 40  | 05/14/2024 | 05/23/2024 | 7            |
|7.2   | System Launch                             | 20  | 05/24/2024 | 05/27/2024 | 7.1          |
|8     | Documentation                             | 20  | 05/28/2024 | 05/30/2024 | 7.2          |
|9     | Project Closure and Reporting             | 20  | 05/31/2024 | 06/04/2024 | 8            |
|9.1   | Finalize Documentation                    | 10  | 05/31/2024 | 06/02/2024 | 9            |
|9.2   | Generate Project Report                   | 10  | 06/03/2024 | 06/04/2024 | 9.1          |

## Gantt Chart and Network Diagram


## Detailed Requirements Document
### Functional Requirements:
1. User Authentification:
  * User's must be able to create an account, verify their identities, link said account to their healthcare provider, and log in securely.
  * Access levels should vary between a basic user/patient, healthcare professionals, and drone dispatch operators.

2. Ordering:
  * Patients must be able to make orders/requests for medication and necessary supplies through an easy-to-understand UI.
  * The system must allow patients to schedule their deliveries, as well as set up a recurring plan.
  * Healthcare professionals must be able to place orders on a patients behalf.

3. Automated Dispatching:
  * The system should automatically dispatch drones at scheduled times.
  * Drone dispatch operators will oversee deliveries and returns as they are carried out.

4. Real-time Tracking:
  * Users must be able to track the statuses of orders they have placed through the system UI.
  * Drone dispatch operators must be able to track dispatched drones with great detail.

5. Navigation and Routing:
  * The system must be able to plan drone routes and have access to several geographical databases to ensure the data used is up to date.
  * A backup navigation system should be implemented to ensure drones can reroute or return safely if delivery is inhibited or halted entirely by external conditions, such as weather.

6. Weather Integration:
  * The system should be integrated with several weather APIs to receive detailed information on weather forecasts.
 
### Non-Functional Requirements:
1. Operational Reliability and Consistency:
  * System downtime should be minimized to the greatest extent.
  * Backup contingencies and system redundancies should be in place in case of system failure.

2. Security:
  * The system must comply with current data protection standards and ensure the privacy of patient data.
  * Encryption protocols must be implemented for the sake of both data transmission and storage.

3. User Friendly UI:
  * The UI should be easily accessible, simple to navigate for the average user, and generally visually appealing.

4. Scalability and Optimization:
  * The system must be capable of handling a high volume of concurrent delivery requests.
  * The system's scaling must occur in an efficient manner as to avoid negatively affecting overall performance.

5. System Recovery:
  * In case of critical failures, the system must be able to recover quickly and resume operation.
  * System data should regulary be backed up and checked for integrity.

6. Regulatory Compliance:
  * The system must comply with all relevant regulations, such as those within aviation and healthcare.

7. Documentation:
  * Comprehensive documentation should be created and distributed for system administrators and users.
  * Training materials must be available for the onboarding process.
   


## Fully Dressed Use Cases
 **Use Case Number:** DC-1  
 **Use Case Name:** Place Order  
 **Description:** The AeroMedic system allows patients/customers to place orders on medical supplies or medication, whether it be directly or through a healthcare professional.  
 **Primary Actor:** Patient/Customer, Healthcare Professional  
 **Priority:** High  
 **Type:** External  
 **Trigger:** Customer needs medication or supplies, or a healthcare professional prescribes them for them.  
   
 **Major Inputs:**

| **Major Inputs** | **Source** |
|   :---:          |   :---:    |
| Supply/Medication Request |  Patient  |
| Prescription         |  Healthcare Professional   |
| Supply/Medication Availability         |  System Database   |
| Delivery Preferences         |  Patient   |

**Major Outputs:**

| **Major Outputs** | **Source** |
|   :---:           |   :---:    |
| Order Confirmation           |  AeroMedic System   |
| Order Status           |  AeroMedic System   |
| Order           |  Drone   |

**Basic Flow:**

| **Step** | **Action** | **Actor**  |
|   :---:  |   :---:    |   :---:    |
| 1  |  Customer logs into the AeroMedic system   |  Customer   |
| 2  |  Customer selects items for their order   |  Customer   |
| 3  |  Inventory is checked to see if the selected items are available   |  AeroMedic System  |
| 3.1  |  Item is out of stock or nearly empty, so the user is notified   |  AeroMedic System   |
| 4  |  Customer proceeds to checkout   |  Customer   |
| 4.1  |  Customer's payment information or delivery address registers as invalid   |  AeroMedic System   |
| 5  |  Confirmation and tracking information are generated   |  AeroMedic System  |
| 6  |  Drone is dispatched   |  AeroMedic System  |
| 6.1  |  Drone comes across an issue that inhibits delivery   |  Drone  |
| 6.2  |  Drone either attempts an alternate path or returns to base   |  Drone  |
| 7  |  Customer is given updates on their order's status   |  AeroMedic System  |
| 8  |  Drone successfully delivers order   |  Drone  |
| 9  |  Customer receives order and confirms it in the system  |  Customer  |  
  
  
**Use Case Number:** DC-2  
 **Use Case Name:** Operation Monitoring  
 **Description:** The system allows for drone dispatch operators to monitor and manage deliveries as they are carried out to ensure that operations are both smooth and successful.  
 **Primary Actor:** Drone Dispatch Operator, Operational Manager  
 **Priority:** High  
 **Type:** Temporal  
 **Trigger:** Order is placed, scheduled delivery time arives, or an incident occurs during operation.  
   
 **Major Inputs:**

| **Major Inputs** | **Source** |
|   :---:          |   :---:    |
| Drone Telemetry Data |  Drone  |
| Drone Delivery Routes |  Drone Dispatch Operator   |
| Incident Report |  Drone Dispatch Operator   |

**Major Outputs:**

| **Major Outputs** | **Source** |
|   :---:           |   :---:    |
| Drone Status Updates  |  Drone   |
| Progress/Incident Report  |  Drone Dispatch Operator   |


**Basic Flow:**

| **Step** | **Action** | **Actor**  |
|   :---:  |   :---:    |   :---:    |
| 1  |  Operational Manager receives delivery schedule   |  Operational Manager  |
| 2  |  Drones begin operation   |  AeroMedic System  |
| 3  |  Drone Dispatch Operators monitor active deliveries   |  Drone Dispatch Operator   |
| 3.1  |  If an incident occurs, operators will inform the Operational Manager   |  Drone Dispatch Operator   |
| 3.2  |  Contingency protocols are executed   |  Operational Manager   |
| 4  |  If necessary, the Operational Manager may inform stakeholders of any notable occurences | Drone Dispatch Operator |
| 5  |  Delivery details are logged and placed in a daily system report | AeroMedic System |
| 6  |  Operational Manager conducts analysis of system report | Operational Manager |

**Use Case Number:** DC-3  
 **Use Case Name:** Performing System Maintenance  
 **Description:** Regular maintenance is scheduled to take place to ensure that the AeroMedic system remains secure, reliable, and technologically advanced. Mainenance is also conducted for the drones. 
 **Primary Actor:** Maintenance Technician, Operational Manager  
 **Priority:** Med  
 **Type:** Temporal  
 **Trigger:** Scheduled maintenance arrives, or the system encounters an issue.  
   
 **Major Inputs:**

| **Major Inputs** | **Source** |
|   :---:          |   :---:    |
| Maintenance Schedule |  System Administrator  |
| Incident Report |  Operational Manager, User, System   |

**Major Outputs:**

| **Major Outputs** | **Source** |
|   :---:           |   :---:    |
| Maintenance Log  |  Maintenance Technician   |
| Updated/Fixed System  |  Software Maintenance Technician   |
| Updated Drone Fleet  |  Hardware Maintenance Technician   |


**Basic Flow:**

| **Step** | **Action** | **Actor**  |
|   :---:  |   :---:    |   :---:    |
| 1  |  System Administrator schedules routine maintenance based on the system's requirements and usage |  System Administrator  |
| 2  |  User is notified of impending maintenance in a non-disruptive fashion   |  AeroMedic System  |
| 3  |  Drone Dispatch Operators monitor active deliveries   |  Drone Dispatch Operator   |
| 4  |  System Maintenance is conducted   |  Software Maintenance Technician   |
| 4.1  |  Drone maintenance is conducted if necessary   |  Hardware Maintenance Technician   |
| 5  |  System Admin monitors maintenance progress | System Administrator |
| 6  |  System updates are rolled out | Software Maintenance Technician |
| 7  |  Maintenance concludes | Maintenance Technician |
| 7.1  |  If new any issues are discovered, maintenance is extended | Maintenance Technician |
| 8  |  System administrator generates and stores maintenance logs within the system| System Administrator |


## System Research
A popular system that shares similarity with ours is Amazon Prime Air. While its basis is different, the drone delivery concept is essentially the same, and it offers insight and real life applications for large-scale drone delivery.

As for its design philosphy, Amazon Prime Air houses and employs a number of autonomouse drones to carry out package delivery to customers who request the service. Said deliveries usually take under an hour. Their system was designed and implemented to mesh with their existing and flourshing e-commerce platform so that customers can select Prime Air as an option at checkout for packages that are eligible. Similar services include Wing drone delivery, UPS Flight Forward, DHL Parcelcopter, and more.

Amazon Prime Air's capabilities are as follows:

1. ## Automated Dispatch:
   Similarly to our system, Amazon Prime Air uses an automated dispatching system to schedule and carry out deliveries. Factors that are accounted for include distance, package size and weight, and customer location. Routes are calculated with optimization in mind.

2. ## Real-Time Tracking:
   Customers are able to track the status of their drone-assisted deliveries in the same way they would track a standard delivery. Through this functionality, customers are kept in the know and can rest assured that their package is on the way.

3. ## Weather Integration:
   The Amazon Prime Air system is integrated with weather forecasting APIs to monitor weather conditions in real time. Such information allows the system to decide whether or not the weather is fit for operation.

4. ## Security:
   Amazon Prime Air's system also features encryption protocols to protect and mask data that is shared between drones and their control centers for the sake of both customer and company safety.

5. ## Backup Systems:
   Backup systems and redundancy measures are employed to ensure operation can persist through any system failures. Such measures include navigational sensors and dynamic routing algorithms to account for negative weather conditions, airspace restrictions, and other factors of that nature.
   
## API Descriptions
|Name|  Description | Usage |
|:---: | --- | --- |
|Google Maps| Provides mapping, geocoding, routing, and other location-based services. | Used to calculate optimal routes for drone delivery, display maps to users, geocode patient addresses, and provide real-time tracking of drone locations.|
|OpenWeatherMap| Offers weather forecasts and current weather data for various locations. | Helps in planning drone flights by providing weather conditions such as wind speed, precipitation, temperature, and visibility.|
|Drone Management| Manages the operation and control of drones, including flight planning, navigation, and telemetry data.| Allows the application to communicate with drones, send commands for takeoff, landing, and navigation, and retrieve status updates and telemetry data.|
|Medical Supplies Inventory| Manages the inventory of medical supplies available for delivery.| Allows the application to check the availability of specific medical supplies, update inventory levels after deliveries, and notify staff when supplies need to be restocked. |
|Patient Management| Manages patient information, including demographics, medical history, and delivery preferences.| Enables the application to retrieve patient addresses for delivery, verify patient eligibility for drone delivery, and update patient records after successful deliveries.| 
|Payment Gateway| Facilitates secure online payments for drone delivery services. |Allows users to pay for medical supply deliveries using credit/debit cards or other payment methods securely integrated into the application.|
|Firebased Cloud Messaging|Sends notifications to users via SMS, email, or push notifications.|Notifies patients about scheduled deliveries, provides status updates on delivery progress, and sends alerts in case of delays or issues during delivery.|
|Regulatory Compliance|Provides information and updates on drone regulations and compliance requirements.|Ensures that drone operations adhere to legal and regulatory standards, including airspace restrictions, flight permissions, and safety protocols|




