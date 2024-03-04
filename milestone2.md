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
###Functional Requirements
###Non-Functional Requirements


## Fully Dressed Use Cases


## System Research


## API Descriptions





