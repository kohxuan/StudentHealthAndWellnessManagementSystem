# 🏥 Student Health And Wellness Management System (SHWMS)
The **Student Health And Wellness Management System (SHWMS)** is a comprehensive software engineering course project developed by **Group Software** in collaboration with Pusat Kesihatan Universiti (PKU) at Universiti Teknologi Malaysia (UTM). It aims to enhance the wellbeing of university students by providing an accessible platform to manage their physical, mental, and emotional health.<br><br>
**This repository serves as the central hub for the project's design artifacts and documentation. The primary deliverable is a high-fidelity, interactive prototype created exclusively using Figma.** The initial user scope focuses on students residing at Kolej Tun Dr. Ismail (KTDI), UTM.
<br><br>

### 🤔 Background / Problem Statement
University students often encounter difficulties when accessing campus health services (PKU), including:
*   Complex and potentially overwhelming procedures.
*   Travel time for some students.
*   Long waiting periods, particularly during peak times or with limited staff availability.
*   Inefficient time utilization for students needing care.
This project addresses these challenges by designing a streamlined digital solution.
<br>

### 🎯 Objectives
The key design objectives of the SHWMS prototype are:
1.  **Enhance Student Wellbeing:** Design intuitive access to medical resources, health tracking tools (BMI, reports), and reliable health advice. *(Potential: Improve overall wellbeing)*
2.  **Streamline PKU Interaction:** Create interfaces for students to view queue status, manage appointments (mental/dental), and potentially communicate with PKU staff. *(Potential: Reduce PKU processing time by 25%, increase online consultations by 30%)*
3.  **Provide Emergency Contact:** Include an easily accessible SOS feature for urgent contact with PKU. *(Potential: Improve emergency response efficiency by 30%)*
4.  **Support Health Management:** Design features for students to manage personal health info and for PKU staff (Admin/Doctors) to manage appointments, tips, and user accounts conceptually. *(Potential: Increase diagnostic efficiency by 20% and healthcare service provision by 25%)*
5.  **Facilitate Feedback:** Incorporate a feedback mechanism for continuous improvement.
<br>

### 🚀 Potential Impact
*   **Efficiency:** Reduced administrative workload and processing time for PKU staff. Shorter waiting times for students seeking medical attention.
*   **Accessibility:** Improved access to health resources, appointment scheduling (mental/dental), and emergency support for students.
*   **Wellbeing:** Enhanced student physical and mental health through accessible self-assessment tools, health tips, and streamlined care pathways.
*   **Communication:** Better channels for interaction between students and PKU professionals.
*   **Data-Driven Care:** Potential for PKU to better understand student health needs and provide targeted interventions (based on aggregated/anonymized data).
<br>

### 🏗️ Scope & System Modules
This project focuses entirely on the **design and documentation** of the SHWMS application using Figma. It does not involve coding, hardware implementation, or changes to existing PKU operational policies. The system design is organized into 7 core modules:
- P001: Authentication
- P002: Account Management
- P003: Patient Queue Management
- P004: Health Tips
- P005: Mental Health Support
- P006: Dental Health Appointment
- P007: Feedback and Reviews

*(Refer to the [SRS Document](https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemRequirementSpecification-SRS.pdf) for detailed Use Case descriptions, Activity Diagrams, and Sequence Diagrams.)*
<br><br>

### 👥 User Roles
The system design caters to three primary user roles:
1.  **UTM Student:** Access personal health info, self-tests, appointments, health tips, queue status, give feedback.
2.  **PKU Doctor:** Access relevant patient info (conceptually), manage appointments, view feedback, access own profile.
3.  **PKU Administrator:** Manage user accounts, manage appointments, manage health tips, manage patient queue data, view feedback, access own profile.
*(Detailed user characteristics are defined in the [SRS, Section 2.1](https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemRequirementSpecification-SRS.pdf)*
<br>

### 🎨 Design & Technology
#### Primary Tool: Figma
**All User Interface (UI) design, User Experience (UX) flows, wireframing, and the interactive prototype were created using Figma.**

#### User Interface (UI) / User Experience (UX) Design
A user-centric approach was adopted to create an intuitive and accessible interface. Key design considerations include:
*   Clear navigation through a central Home Page.
*   Dedicated sections for each module (Profile, Mental Health, Dental, Tips, etc.).
*   Role-specific interfaces and prototypes for Students, Doctors, and Administrators.
*   Visual feedback for actions (e.g., successful submission pop-ups).
*   Consideration for accessibility standards (WCAG 2.1 mentioned).

*Detailed UI overview and screen images for all system flows are available in the [SDD Document (Section 6)](https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemDesignDescriptions-SDD.pdf).*
<br><br>

### 🧪 Testing Approach (Conceptual)
Although no code was written, the design's logic and flows were validated conceptually using a **Black-Box Testing** strategy.
*   **Techniques:** Equivalence Partitioning (EP) and Boundary Value Analysis (BVA) were used to define test conditions for input fields and user actions within the Figma prototype.
*   **Test Cases:** 17 detailed test cases (TC01-TC17) covering all major functionalities (UC01-UC17) were designed.

*Detailed test cases, EP/BVA analysis, and the traceability matrix are available in the [STD Document](https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemTestingDocumentation-STD.pdf).*
<br><br>

### 📚 Project Documentation & Design Files
| Document / File               | Link                                                                                                                                                            | 
| :---------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Project Proposal              | <a href="https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/Proposal.md" ><img src="https://github.com/user-attachments/assets/680fbc90-1078-4a35-8178-841f158b8f16" width="24px" height="24px" ></a>                                                |
| SRS Documentation             | <a href="https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemRequirementSpecification-SRS.pdf" ><img src="https://github.com/user-attachments/assets/680fbc90-1078-4a35-8178-841f158b8f16" width="24px" height="24px" ></a>          |
| SDD Documentation             | <a href="https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemDesignDescriptions-SDD.pdf" ><img src="https://github.com/user-attachments/assets/680fbc90-1078-4a35-8178-841f158b8f16" width="24px" height="24px" ></a>          |
| STD Documentation             | <a href="https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemTestingDocumentation-STD.pdf" ><img src="https://github.com/user-attachments/assets/680fbc90-1078-4a35-8178-841f158b8f16" width="24px" height="24px" ></a>          |
| Figma UI Design File          | <a href="https://www.figma.com/file/j0nAd3Ph1MnHZljmIi8kTk/UI-Design?type=design&node-id=0-1&mode=design&t=FRriUK1E9AQFO2BO-0" ><img src="https://github.com/user-attachments/assets/0b9cc8e9-8387-43d7-bbc5-88e24291ee5c" width="24px" height="24px" ></a>          |
| Figma High Fidelity (Alt Link) | <a href="https://www.figma.com/file/l76fJTJbZyY5oTFQS13les/High-Fidelity-Design?type=design&node-id=0-1&mode=design&t=LYWg1QTbaq1JAEzD-0" ><img src="https://github.com/user-attachments/assets/0b9cc8e9-8387-43d7-bbc5-88e24291ee5c" width="24px" height="24px" ></a>          |
<br>

### ✨ Interactive Prototypes (Figma)
Explore the user experience through dedicated prototypes for each role:
| Prototype Role | Link                                                                                                                                                                                           |
| :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Student**    | <a href="https://www.figma.com/proto/j0nAd3Ph1MnHZljmIi8kTk/UI-Design?type=design&node-id=138-31312&t=HpTPOmIpNtYfA6J9-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=138%3A31312"><img src="https://github.com/user-attachments/assets/0b9cc8e9-8387-43d7-bbc5-88e24291ee5c" width="24px" height="24px" ></a> |
| **Doctor**     | <a href="https://www.figma.com/proto/j0nAd3Ph1MnHZljmIi8kTk/UI-Design?type=design&node-id=169-31207&t=PY91ONQprdWeFRVu-0&scaling=scale-down&page-id=1%3A3&starting-point-node-id=169%3A31207" ><img src="https://github.com/user-attachments/assets/0b9cc8e9-8387-43d7-bbc5-88e24291ee5c" width="24px" height="24px" ></a>  |
| **Administrator**      | <a href="https://www.figma.com/proto/j0nAd3Ph1MnHZljmIi8kTk/UI-Design?type=design&node-id=169-32026&t=kHR7XsjA8CP5Sn6o-0&scaling=scale-down&page-id=1%3A4&starting-point-node-id=169%3A32026" ><img src="https://github.com/user-attachments/assets/0b9cc8e9-8387-43d7-bbc5-88e24291ee5c" width="24px" height="24px" ></a> |

**How to Use:**
1.  Click the badge or link for the desired user role.
2.  Interact with the prototype directly in your browser.
3.  Refer to the [SDD (Section 6)](https://github.com/kohxuan/StudentHealthAndWellnessManagementSystem/blob/main/docs/SystemDesignDescriptions-SDD.pdf) for screen descriptions if needed.
<br>

### 📊 Presentation
A summary presentation of the project is available on [Canva](https://www.canva.com/design/DAGk84QmbKg/sGHGl-HFrEQyed_3rfl3Yg/view?utm_content=DAGk84QmbKg&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hf969b64464)
<br><br>

### 🤝 Team
| Name                                            | Matric No. | Role                         | 
| :-------------                                  | :--------- | :-------------------------   | 
| [Lee Yik Hong](https://github.com/YIKHONGLEE)   | A21BE0376  | User Experience Designer     |
| [Koh Su Xuan](https://github.com/kohxuan)       | A22EC0060  | Quality Assurance Tester     |
| [Tang Yan Qing](https://github.com/yan-qing09)  | A22EC0109  | Documentation Specialist     |
| [Goh Jiale](https://github.com/Jialegoh)        | A22EA0043  | Main Developer (Design Lead) |
| [Ong Yi Yan](https://github.com/ONGYIYAN)       | A22EC0101  | Requirements Analyst         |
<br>
