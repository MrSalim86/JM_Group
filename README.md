🌟 Warehouse Control System (WCS) Project 🌟
🚀 Project Overview
Welcome to the Warehouse Control System (WCS) project! This software is designed to manage the storage, handling, and transport of hazardous chemicals at the Associated Chemical Merchant Enterprises depot. Given the depot operates under strict EU and UK health and safety regulations, our mission is to ensure full regulatory compliance through seamless automation and monitoring.

The system handles the logistics of three classes of chemicals (A, B, and C), each with unique safety requirements. It facilitates both deliveries and dispatches, monitors stock levels, triggers alerts in emergencies (like fire or spills), and tracks every movement for auditing. With safety as a top priority, the system will alert the fire brigade when required and provide real-time inventory updates. We’ve also ensured that our auditing data is resilient in the event of any disasters, safeguarding compliance.

🔧 Team Collaboration and Project Board Workflow
📋 Workflow
Our development process revolves around GitHub’s Project Board, leveraging a Team Planning approach to keep everyone in sync. Tasks are visualized and flow through three main stages:

To Do: A list of upcoming tasks, ready to be tackled.
In Progress: Active tasks being worked on by the team.
Done: Completed tasks, approved and closed.
This clear workflow ensures transparency and accountability within the team.

📝 Task Breakdown
We break down each user story into actionable tasks, making it easier to manage the scope of work. These tasks move across the board as the development progresses, providing a clear, visual representation of where things stand.

To streamline our process, we have workflow automation set up. This means that issues and pull requests with specific labels are automatically added to the project board. For example, if a new issue is labeled as User Story, it will automatically be added to the project, saving us time and ensuring nothing slips through the cracks.

🏷️ Labels and Issue Categorization
Our issue management system is powered by a series of well-defined labels that help us track, prioritize, and organize tasks effectively. Here’s the breakdown:

Issue Types:

Blocked/Waiting: Tasks that are temporarily on hold due to dependencies.
Bug: For those pesky defects that need to be squashed.
User Story: Core functionality or feature tied to end-user needs.
Duplicate: Issues that overlap with existing ones.
Documentation: For improving or adding to our project documentation.
Enhancement: Opportunities for improving or adding new features.
Invalid: Issues that are no longer relevant.
Technical Story (Tech Story): For non-customer-facing, backend work.
Wontfix: Issues that won’t be addressed, based on prioritization.
Priority Levels:

High: Critical issues that need immediate attention.
Medium: Important issues, but not immediately urgent.
Low: Lower-priority tasks that can wait.
⏳ Estimation and Task Assignment
Each task is carefully estimated in terms of effort and complexity, helping us plan and allocate resources efficiently. Every task is assigned to a specific team member, ensuring accountability and smooth transitions through the development phases.

🌿 Branching Strategy
To maintain simplicity and agility, we are utilizing GitHub Flow for our branching strategy. This straightforward approach ensures that development is clean and organized:

Our main (master) branch always holds deployable, production-ready code.
Developers create feature branches from the main branch to work on individual stories or tasks.
Once complete, the feature branch is merged back into the main branch through a pull request. Only thoroughly tested and stable code makes it to the main branch.
This strategy ensures a continuous flow of deployable code while allowing for rapid development cycles.

🛠️ Technology Stack
Here’s a peek under the hood at the technologies powering the Warehouse Control System:

Backend:
Language: C#
Framework: .NET Web API
Frontend:
Language: JavaScript
Framework: React.js
Hosting:
Cloud Platform: Azure
Database: Microsoft SQL Server (MSSQL)
📡 Deployment and Monitoring
We host our system on Azure, leveraging its scalability and performance to ensure the smooth operation of the WCS. Our database, powered by MSSQL, ensures high performance, security, and resilience for storing sensitive chemical storage data.
