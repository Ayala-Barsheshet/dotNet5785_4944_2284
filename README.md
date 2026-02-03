# Volunteer Management System | C#, .NET
A comprehensive, enterprise-grade system designed for volunteer organizations to orchestrate emergency and service calls.<br>
The platform bridges the gap between administrators managing logistics and volunteers responding to real-time events in the field.

### Key Features

* Sophisticated Call Lifecycle: End-to-end management of service calls with dynamic status tracking (Open, Assigned, Completed, Expired).

* Advanced Simulation Engine: A built-in real-time simulator that advances system time independently of the OS clock, enabling stress-testing of time-sensitive operations.

* Intelligent Automation: Internal timers and logic modules that automatically flag calls as "At Risk" or "Expired" based on predefined organizational thresholds.

* Geo-Location Optimization: Algorithms to calculate distances (Aerial/Walking/Driving) between volunteers and call sites to ensure the fastest response time.

* Robust Audit Trail: Full transparency with history tracking for every call, including assignment changes, cancellations, and handovers.

### Tech Stack
Language: C#

Framework: .NET 8.0

UI Framework: WPF (XAML)

Storage: XML, In-Memory Lists

Concepts: LINQ, Multi-threading, Asynchronous Programming (Async/Await).

### Architecture & Design
The project strictly adheres to Layered Architecture (3-Tier) principles to ensure high maintainability and scalability:
1. DAL (Data Access Layer)
Data Persistence: Managed via XML files and optimized In-Memory collections.<br>
Patterns: Implemented using CRUD patterns and generic interfaces for decoupled data handling.

2. BL (Business Logic Layer)
Core Logic: The "brain" of the system, handling complex validation and business rules.<br>
Technology: Extensive use of LINQ for data manipulation and Multi-threading for background tasks.<br>
Design Patterns: Implementation of Singleton and Factory Method for robust object management.

3. PL (Presentation Layer)
User Experience: Modern Desktop UI built with WPF (Windows Presentation Foundation).
Features: Reactive interface utilizing XAML, Data Binding, and event-driven programming.

### User Roles & Permissions
*Admin Mode:

Full system orchestration (Manage volunteers, calls, and entities).

Control over the "System Clock" to simulate time-lapse scenarios.

Access to advanced reporting and system initialization.

*Volunteer Mode:

Personalized dashboard based on location and skills.

View filtered calls within a specific radius.

Self-assignment and real-time status reporting.

### Getting Started
Prerequisites
* Visual Studio 2022 or newer.
* .NET 8.0 SDK.

### Installation & Execution
Clone the repository:
Bash
git clone https://github.com/Ayala-Barsheshet/dotNet5785_4944_2284.git

Open the Project: Locate and open the .sln file in Visual Studio.

Startup Configuration (Crucial):

Right-click on the PL (Presentation Layer) project in the Solution Explorer.

Select "Set as Startup Project".

Run: Press F5 or click the Start button to launch the application.

### Installation & Execution
Follow these steps to run the project locally:

1. **Clone the repository** Copy and run the following command in your terminal:  
   `git clone https://github.com/Ayala-Barsheshet/dotNet5785_4944_2284.git`

2. **Open the Project** Locate and open the `.sln` file in Visual Studio.

3. **Startup Configuration (Crucial)** Right-click on the **PL** (Presentation Layer) project in the Solution Explorer.  
   Select **"Set as Startup Project"**.

4. **Run the Application** Press **F5** or click the **Start** button to launch the application.

### Project Context
Developed as part of the .NET Windows Systems course (2025). This project demonstrates high-level software engineering capabilities, 
focusing on complex logic, multi-layered design, and real-world simulation challenges.

Created by Ayala Barsheshet

