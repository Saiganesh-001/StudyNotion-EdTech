# Study Notion

Study Notion is an ED Tech (Education Technology) web application developed using the MERN stack.

## Note

This project is intended as a learning tool and can be used as a sample project for educational or personal projects.

---

## Features

- User Authentication: Study Notion provides secure user registration and authentication using JWT (JSON Web Tokens). Users can sign up, log in, and manage their
  profiles with ease.
- Courses and Lessons: Instructors can create and edit created courses. Students can enroll in courses, access course materials, and track their progress.
- Progress Tracking: Study Notion allows students to track their progress in enrolled courses. They can view completed lessons, scores on quizzes and
  assignments, and overall course progress.
- Payment Integration: Study Notion integrates with Razorpay for payment processing. Users can make secure payments for course enrollment and other services
  using various payment methods supported by Razorpay.
- Search Functionality: Users can easily search for courses, lessons, and resources using the built-in search feature. This makes it convenient to find relevant
  content quickly.
- Instructor Dashboard: Instructors have access to a comprehensive dashboard to view information about their courses, students, and income. The
  dashboard provides charts and visualizations to present data clearly and intuitively. Instructors can monitor the total number of students enrolled in
  each course, track course performance, and view their income generated from course sales.

---

## Screenshots

<img width="1280" alt="Screenshot 2024-10-16 042131" src="https://github.com/user-attachments/assets/e1cc8dc4-7df2-4434-8d1f-af91015b9eee">
<img width="1280" alt="Screenshot 2024-10-16 042158" src="https://github.com/user-attachments/assets/c05cafa0-3c6e-4434-a177-50ed0e67266c">


<details>
  <summary>More screenshots</summary>
  
<img width="1280" alt="Screenshot 2024-10-16 042221" src="https://github.com/user-attachments/assets/e12295e4-bc4f-4a1d-b775-494f55f4d501">
<img width="1280" alt="Screenshot 2024-10-16 042239" src="https://github.com/user-attachments/assets/491f841a-bc40-42dc-b355-5a5beee10ff6">
<img width="1280" alt="Screenshot 2024-10-16 042301" src="https://github.com/user-attachments/assets/dd041e46-a005-4832-9a74-5778fc4a90f9">

</details>

---

## Important

- Backend is in the server folder.
- Before uploading courses and anything create the categories e.g. web dev, Python, etc. (without categories courses cannot be added). To create categories create an Admin account and go to dashboard then admin panel.
- To create an Admin account first sign up with a student or instructor account then go to your Database under the users model and change that 'accountType' to 'Admin'.

## Installation

1. Clone the repository to your local machine.

   ```sh
   git clone https://github.com/Saiganesh-001/StudyNotion-EdTech.git
   ```

2. Install the required packages.

   ```sh
   cd StudyNotion-EdTech
   npm install

   cd server
   npm install
   ```

3. Set up the environment variables:

   Create a .env file in the root directory and /server
   Add the required environment variables, such as database connection details, JWT secret, and any other necessary configurations check .env.example files for more info.

4. Start the development server.

   ```sh
   npm run dev
   ```

5. Open the project in your browser at [`http://localhost:3000`](http://localhost:3000) to view your project.

The project is set up to use `postcss-cli` to process your CSS files. You can add your own `tailwind.config.js` file to customize your Tailwind setup.
