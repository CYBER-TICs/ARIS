# ARIS - Automated Reporting and Information System

![image](https://github.com/user-attachments/assets/502069af-6565-481b-a6f6-b12e388fa2ec)


**ARIS** (Automated Reporting and Information System) is a digital platform designed to modernize and optimize the management of complaints and reports within the **Internal Affairs Unit (IAU)** of the **National Police Service of Kenya**. This project aims to improve transparency, efficiency, and accountability in handling citizen complaints against police misconduct.

ARIS allows citizens to submit complaints quickly and easily, track the progress of their cases, and ensure that each complaint is documented, investigated, and resolved in a timely manner. Additionally, the system facilitates data collection and analysis to identify behavioral patterns and improve training and supervision policies.

---

## Key Features

- **Simplified Complaint Submission:** Users can submit complaints by selecting from a list of common complaint types and providing additional details.
- **Responsible Officer Identification:** Users can identify the involved officer, if possible, to expedite the investigation.
- **Complaint Tracking:** Users can track the status of their complaints in real-time using a unique reference number.
- **Attachment Management:** Users can attach photos, videos, and documents to support their complaints.
- **Intuitive and Accessible Interface:** Responsive design accessible from any device with an internet connection. The platform has been designed following accessibility standards to ensure usability for people with disabilities.
- **Data Security:** Robust security measures, including data encryption and access controls.
- **Integration with Existing Systems:** Compatibility with other systems of the National Police Service of Kenya for seamless interoperability.

---

## Technologies Used

- **Frontend:** React.js, HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Node.js, Express.js, Sequelize (ORM)
- **Database:** MySQL
- **Authentication:** JWT (JSON Web Tokens)
- **Deployment:** Serverless Deployment 
- **Other Tools:** Git, GitHub, Postman (for API testing)

---

## Project Structure

The repository is organized as follows:

```
aris/
├── backend/            # Server-side code and business logic
├── frontend/           # User interface and React components
├── database/           # Database schemas, migrations, and seeds
├── docs/               # Project documentation
├── scripts/            # Deployment and backup scripts
├── tests/              # Unit and integration tests
├── .gitignore          # Files and folders ignored by Git
├── LICENSE             # Project license
├── README.md           # This file
```

---

## Accessibility and Inclusion

ARIS has been designed with a focus on **universal accessibility**, ensuring that all individuals, including those with disabilities, can effectively use the platform. We have implemented the following features to ensure inclusivity:

- **Screen Reader Compatibility:** The platform is compatible with assistive technologies like screen readers for users with visual impairments.
- **Keyboard Navigation:** All platform functionality can be accessed and operated using the keyboard.
- **Contrast and Font Size:** We have optimized contrast and allow font size adjustments to improve readability.
- **Responsive Design:** The platform adapts to different devices, including desktops, tablets, and mobile phones.

We are committed to continuously improving ARIS's accessibility to ensure that all users, regardless of their abilities, can interact with the system effectively.

---

## How to Contribute

We welcome contributions! If you'd like to contribute to the development of ARIS, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/CYBER-TICs/aris.git
   cd aris
   ```

2. **Install Dependencies:**
   - **Backend:**
     ```bash
     cd backend
     npm install
     ```
   - **Frontend:**
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set Up the Environment:**
   - Create a `.env` file in the `backend/` and `frontend/` folders with the necessary environment variables.
   - Set up the database in `database/schema.sql`.

4. **Run the Project:**
   - **Backend:**
     ```bash
     cd backend
     npm start
     ```
   - **Frontend:**
     ```bash
     cd ../frontend
     npm start
     ```

5. **Create a Branch and Submit a Pull Request:**
   - Create a new branch for your contribution:
     ```bash
     git checkout -b name
     ```
   - Make your changes and submit a pull request to the `main` branch.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## Contact

If you have any questions or suggestions, feel free to reach out:

- **Email:** jorge.carmona@un.org
- **GitHub Issues:** [Report an Issue](https://github.com/CYBER-TICs/aris/issues)

---

Thank you for your interest in **ARIS**! Together, we can build a more transparent, efficient, and inclusive system for complaint management in the National Police Service of Kenya. 🚀

---
