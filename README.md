## 🌍 The world’s most high-end designed, lightweight, and feature-rich learning management system.

# **LMS by Vaibhav**: Open Source Learning Management System

**LMS by Vaibhav** is a powerful, lightweight, and modern learning management system built using the Django web framework. Whether for an educational institute or personal learning, this LMS provides all essential features to manage courses, users, assessments, and academic records in one place.

> The goal is to build the most lightweight yet feature-rich LMS for educational institutions and developers alike. ⭐️

📄 *Documentation is currently under development.*

👩‍💻 Contributions are welcome — let’s improve it together!

---

<img width="1440" alt="screenshot" src="https://github.com/officialvayu/lms-image/blob/main/WhatsApp%20Image%202025-07-09%20at%207.15.41%20PM.jpeg">

---

## 🚀 Key Features

* **Admin Dashboard**: Overview of school statistics and analytics
* **News & Events**: Public updates and event listings
* **Student Management**: Add, edit, and remove student profiles
* **Lecturer Management**: Full control over lecturer records
* **Course Enrollment**: Students can enroll or drop courses
* **Marks Entry**: Lecturers can input attendance, mid, final, and assignment scores
* **Auto Grade Calculation**: Total, average, grade points, and letter grades generated automatically
* **Performance Comments**: Pass, fail, or warning indicators
* **Results Pages**: Students can view assessment and final grade reports
* **Semester/Session Control**: Organize records by academic period
* **Course Media Uploads**: Attach PDFs, documents, and videos per course
* **PDF Generator**: Downloadable registration slips and grade sheets
* **Role-Based Access**: Permissions based on user type (Admin, Lecturer, Student)
* **Quiz System**:

  * Randomized question order
  * Attempt limits per user
  * View previous quiz results
  * Show correct answers immediately or at the end
  * Resume incomplete quizzes
  * Categories for questions
  * Track success rates
  * Answer explanations
  * Pass mark settings
  * Custom messages on pass/fail
  * Multiple-choice and true/false questions
  * Essay questions (coming soon)
  * Admin quiz marking system
  * Permissions to view other users’ results

---

## 🤝 Contributing

Pull requests and new ideas are always welcome!

---

## 🔧 Requirements

* [Python 3.11+](https://www.python.org/downloads/)

---

## 💻 Installation Guide

1. **Clone the repository**

```bash
git clone https://github.com/your-username/LMS-by-Vaibhav.git
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Set environment variables**

* Create a `.env` file in the root directory
* Copy content from `.env.example` and fill out required values

4. **Run database migrations**

```bash
python manage.py migrate
```

5. **Create a superuser**

```bash
python manage.py createsuperuser
```

6. **Start the development server**

```bash
python manage.py runserver
```

7. **Open in your browser**

```
http://127.0.0.1:8000
```

---

## 🔗 Reference

* Quiz module adapted from: [django\_quiz by tomwalker](https://github.com/tomwalker/django_quiz)

---

⭐️ **If you like LMS by Vaibhav, consider giving it a star on GitHub!**
