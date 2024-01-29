# Iemhacks_InnoWebInnovators

**Team Name**: InnoWeb Innovators

**Team Members Name**:Keshav Kumar Jha and Yuvraj Singh

Team Members GithubUsername:keshavjha05, yuvraj567

**Introduction:**
Introducing a cutting-edge EdTech platform Studysavy thoughtfully designed to cater to the growing need for personalized learning journeys. Our innovative web-based system offers a sophisticated solution that seamlessly tailors content, engagement, and progression according to the distinct requirements of every learner. This adeptly tackles the issue of accommodating a wide array of learning preferences and approaches.

**Website Link**:https://studysavy.vercel.app/

**Key Features and Innovations:**
1.	Personalized Learning Journey: This targeted approach ensures that students receive content tailored to their individual needs.
2.	Real-Time Progress Tracking: It offers real-time tracking of student progress, allowing educators and learners to monitor growth and performance instantly.
3.	User-Friendly Interface: It boasts an intuitive interface that ensures ease of use for students of all technological backgrounds. This accessibility enhances  engagement and reduces barriers to entry.

**Tech Stacks:**
The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

**System Architecture:**
1.	Front-end:
The front end of the platform is built using ReactJS, which is a popular JavaScript library for building user interfaces.
2.	Back-end:
•	The back end of the platform is built using NodeJS and ExpressJS, which are popular frameworks for building scalable and robust server-side applications. 
•	The database for the platform is built using MongoDB, which is a NoSQL database that provides a flexible and scalable data storage solution. MongoDB's unique capability to store data in flexible formats, whether structured or semi-structured, proves invaluable for hosting a wide array of data which is useful for storing course content such as videos, images, and PDFs. The database stores the course content, user data, and other relevant information related to the platform.

**Functionalities of the website:**
The front end of Studysavy has all the necessary pages that an ed-tech platform should have. Some of these pages are:
 _**For Students:**_
1.	Homepage: This is like the main page that introduces the platform. You'll find a short explanation about what the platform does and links to the list of courses and your user details.
2.	Course List: On this page, you'll see a list of all the available courses. Each course will come with a description and ratings to help you choose.
3.	Wishlist: This page is where you'll find the courses you've saved to check out later. It's like a reminder list.
4.	Cart Checkout: If you decide to buy a course, this is where you complete the purchase. It's like the checkout counter for online shopping.
5.	Course Content: This page is where you access all the materials for a specific course. This includes things like videos and other stuff related to what you're learning.
6.	User Edit Details: On this page, students can make changes to their account information. It's like editing your profile.
7.	User Details: This page contains important info about a student's account, like their name, email, and other important details. It's a summary of your account information.

 _**For Instructors:**_
1.	Dashboard: Here, instructors get a summary of their courses, along with ratings and feedback from students. It's a quick overview of their teaching impact.
2.	Insights: This page provides in-depth information about an instructor's courses, like how many times they've been viewed and clicked on, plus other important stats.
3.	Course Management Pages: These pages give instructors control over their courses. They can create new courses, update existing ones, delete courses, and manage the content and pricing of each course.
4.	View and Edit Profile Details: Instructors can see and change their own account info using these pages. It's like a backstage pass to manage their personal information.

**Features and Functionalities of the Back-end:**
1.	User Authentication and Authorization: Students and instructors can sign up and log in using their email and password. For extra security, there's also OTP verification and a way to reset forgotten passwords.
2.	Course Management: Instructors have control here. They can create, edit, delete courses, and manage the materials. Students can view and rate these courses.
3.	Payment Integration: Students can buy and enroll in courses using a smooth checkout process, powered by Razorpay for handling payments.
4.	Cloud-Based Media Management: We're using Cloudinary, a cloud service, to keep and organize all media stuff like images, videos, and documents.
5.	Markdown Formatting: For easy display, the course content is stored in a format called Markdown. It's like a simple code that makes things look nice when shown on the front end.

**Breakdown of the API endpoints** 
Sample list of API endpoints and their functionalities:
_POST Endpoints:_
1.	/api/auth/signup: Create a new user (student or instructor) account.
2.	/api/auth/login: Log in using existing credentials and generate a JWT token.
3.	/api/auth/verify-otp: Verify the OTP sent to the user's registered email.
4.	/api/auth/forgot-password: Send an email with a password reset link to the registered email.
5.	/api/courses: Create a new course.
6.	/api/courses/:id/rate: Add a rating (out of 5) to a course.
_GET Endpoints:_
1.	/api/courses: Get a list of all available courses.
2.	/api/courses/:id: Get details of a specific course by ID.
_PUT Endpoints:_
1.	/api/courses/:id: Update an existing course by ID.
_DELETE Endpoints:_
2.	/api/courses/:id: Delete a course by ID.
