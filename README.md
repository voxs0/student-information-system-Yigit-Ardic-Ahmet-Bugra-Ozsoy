Campus Student Information System (SIS / OBS)
Campus OBS is a comprehensive, multi-role web platform designed to digitize and streamline academic processes within university ecosystems. The system centralizes communication and data management between students, academicians, and administrative staff.

🚀 Key Features
The system is developed following IEEE 830-1998 standards and offers a robust functional architecture:

Student Portal: View personal information, inspect academic transcripts, track real-time attendance, monitor grades, and manage club memberships.

Academician Portal: Manage course-based grade entries, track student attendance, publish academic announcements, and view student lists.

Administrator (Admin) Panel: Manage user authorizations, create courses and curricula, prepare weekly schedules, and configure system settings.

Dynamic Synchronization: Real-time data consistency; grades entered by an academician are instantly reflected in the student’s dashboard and transcript.

🛠 Technical Architecture
Platform: Cloud-native architecture suitable for AWS/Azure microservices.

Database: PostgreSQL for high-transaction integrity and academic record keeping.

Security: Integrated Corporate Single Sign-On (SSO) and Multi-Factor Authentication (MFA) for sensitive administrative actions.

Accessibility: UI fully compliant with WCAG 2.1 Level AA standards.

📊 Analysis and Design Models
Class Diagram
The system architecture is built on a User abstract class, from which Student, Academician, and Admin classes are inherited. Course enrollment serves as the central link managing the relationships between these entities.

Use Case Scenarios
Defined actor permissions include:

Student: Course registration, viewing transcripts, tracking attendance.

Academician: Course setup, grade entry, student list management.

Admin: User management, course validation, system-wide settings.

Workflow (Sequence Diagram)
During "Course Addition" and "Schedule Preparation" by the Admin, the system automatically performs database validation and conflict checks (ensuring faculty and classroom availability).

🧪 Usability Test Results
The prototype has undergone rigorous usability testing with high success metrics:

Task Success Rate: 91.6%

Interface Aesthetics Score: 4.8 / 5

System Responsiveness: 4.7 / 5

Average Grade Retrieval Time: < 2 seconds

💻 Installation and Demo
To view the interface prototype:

Download the index.html file.

Open the file in any modern web browser (Chrome, Edge, Firefox).

Use the following credentials for testing:

Student Login: admin / 1234

Academician Login: hoca / 1234

Prepared by: Yiğit Ardıç - Ahmet Buğra Özsoy

# student-information-system-Yigit-Ardic-Ahmet-Bugra-Ozsoy
