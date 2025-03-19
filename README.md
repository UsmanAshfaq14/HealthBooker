# HealthBooker 🧑‍⚕️

Welcome to **HealthBooker**, a comprehensive healthcare platform designed to offer a seamless experience for both users and doctors. Enjoy secure access to your information, book appointments with ease, and manage your profile—all in one place.

---

Demo of Website:

![image](https://github.com/user-attachments/assets/5e2c567b-5b81-4653-8bb8-ee0591ade9b1)
![image](https://github.com/user-attachments/assets/de6be1bd-bc1b-44cc-a945-7c37456535f5)
![image](https://github.com/user-attachments/assets/be7207db-f8e7-4786-b7f2-f8a2e21dcdd4)
![image](https://github.com/user-attachments/assets/438212f7-6d01-4ca4-925a-f7474865897b)
![image](https://github.com/user-attachments/assets/7d97eaeb-c480-4c7a-a8f1-88943a4b7476)
![image](https://github.com/user-attachments/assets/522e9466-4ff6-4e09-8c15-532bc39c49bc)
![image](https://github.com/user-attachments/assets/342eec47-c0b2-47ae-99cb-91c524c4098e)


## Description

Our platform provides:

- **User & Doctor Authentication:** Sign up or log in to access a range of features.
- **Doctor Listings:** Browse through available doctors to find the perfect match.
- **Profile Management:** Update and maintain accurate user information.
- **User Queries:** Submit questions via our contact section.
- **Notifications:** Stay informed with timely alerts on appointments, updates, and application statuses.
- **Doctor Application:** Aspiring doctors can apply easily through our user-friendly system.
- **Appointment Booking:** Schedule and track appointments seamlessly.
- **Admin Controls:** Manage user accounts, doctor applications, and more with robust admin features.
- **Data Security:** All data is stored securely, ensuring privacy and reliability.

---

## Live Site

Visit our live site: [HealthBooker Live Site](https://healthbooker.onrender.com/)

---

## Tools and Technologies

- **HTML5**
- **CSS3**
- **JavaScript**
- **React**
- **Node.js**
- **Express**
- **MongoDB**
- **Redux Toolkit**

---

## Features

- **User Registration and Login:** Secure authentication for all users.
- **View Available Doctors:** Easily browse a list of medical professionals.
- **Update Profile:** Maintain current and accurate personal information.
- **Contact Section for Queries:** Reach out for support or inquiries.
- **Notifications Tab:** Get real-time updates on appointments and applications.
- **Admin Management System:** Oversee users, appointments, and doctor applications.
- **Access Control:** Restrict sensitive sections to logged-in users.
- **Doctor Application:** Apply to become a doctor on the platform.
- **Book Appointments:** Schedule appointments with your chosen doctor.
- **Admin Approval for Doctor Requests:** Ensure only qualified professionals are listed.
- **User and Doctor Removal:** Maintain platform integrity with administrative controls.
- **Appointment Marking:** Mark appointments as completed for proper record-keeping.
- **Application and Appointment Notifications:** Receive updates across the platform.
- **Data Storage and Security:** All information is securely stored and easily accessible.

---

## Getting Started

### Installation

1. **Fork the Repository**

2. **Clone the Repository**

   Open your terminal or command prompt and run:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

   Replace `your-username` with your GitHub username and `your-repo` with the name of your repository.

3. **Configure Environment Variables**

   - Rename the `.env.example` files to `.env` in both the root and the `client` directory.
   - Add your specific environment variables to these files.

### Running the Project

1. **Backend**

   Open a terminal in the root directory and run:

   ```bash
   npm start
   ```

2. **Frontend**

   Open a new terminal, navigate to the `client` directory, and run:

   ```bash
   cd client
   npm start
   ```

---

## Admin Dashboard Access

To access the admin dashboard:

1. **Download the Project** from the Git repository.
2. **Set Up MongoDB:**
   - Create your own MongoDB instance.
   - Add your MongoDB URL to the `.env` file.
3. **Register on the Website:**
   - Create an account by signing up.
   - In your MongoDB database, locate the account document you wish to grant admin privileges.
   - Manually change the `isAdmin` field to `true`.
4. **Log Back In:**
   - Once updated, log back into the website to access the admin dashboard.

---

## Pages

- **Home Page:** `/home`
- **Sign Up Page:** `/signup`
- **Sign In Page:** `/signin`
- **Profile Page:** `/profile`
- **All Doctors Page:** `/doctors`
- **Apply for Doctor Page:** `/applyfordoctor`
- **Admin - All Users Dashboard:** `/users`
- **Admin - All Applications Page:** `/applications`
- **Book Appointment Page:** `/bookappointment`
- **Users - All Appointments Page:** `/appointments`
- **Doctors - All Appointments Page:** `/appointments`
- **Notifications Page:** `/notifications`

---

If you found this repository helpful, please give it a 🌟 and share your support!
