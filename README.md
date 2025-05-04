# PRODIGY_WD_01
RESPONSIVE LANDING PAGE 

index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Student Portal</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Navigation Menu -->
  <nav id="navbar">
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#courses">Courses</a></li>
      <li><a href="#profile">Profile</a></li>
      <li><a href="#results">Results</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Page Content -->
  <div class="content">

    <section id="home">
      <h2>Welcome to the Student Portal</h2>
      <p>This portal provides students with access to academic resources, personal information, and course-related data. Stay updated and manage your academic journey effectively from one place.</p>
    </section>

    <section id="courses">
      <h2>Enrolled Courses</h2>
      <ul>
        <li><strong>CSEN2031:</strong> Artificial Intelligence</li>
        <li><strong>CSEN2071:</strong> Cryptography and Network Security</li>
        <li><strong>CSEN3071:</strong> Web Application Development</li>
        <li><strong>FINA3011:</strong> Financial Markets and Services</li>
      </ul>
      <p>You can view course materials, assignments, and submit your work through the LMS.</p>
    </section>

    <section id="profile">
      <h2>Your Profile</h2>
      <p><strong>Student ID:</strong> HU22CSEN0100198</p>
      <p><strong>Department:</strong> CSE </p>
      <p><strong>Email:</strong> student@university.edu</p>
      <p><strong>Status:</strong> Active</p>
    </section>

    <section id="results">
      <h2>Academic Results</h2>
      <table border="1" cellpadding="10" cellspacing="0">
        <thead>
          <tr>
            <th>Subject</th>
            <th>Grade</th>
            <th>Credits</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Artificial Intelligence</td>
            <td>A</td>
            <td>4</td>
          </tr>
          <tr>
            <td>Cryptography</td>
            <td>B+</td>
            <td>3</td>
          </tr>
          <tr>
            <td>Web Development</td>
            <td>A+</td>
            <td>4</td>
          </tr>
          <tr>
            <td>Finance</td>
            <td>A</td>
            <td>3</td>
          </tr>
        </tbody>
      </table>
    </section>

    <section id="contact">
      <h2>Contact Administration</h2>
      <p>If you have questions or need assistance, please contact the student affairs office.</p>
      <ul>
        <li>Email: support@university.edu</li>
        <li>Phone: +91-123-456-7890</li>
        <li>Office Hours: Mon–Fri, 9AM–5PM</li>
      </ul>
      <form>
        <label for="message">Message Us:</label><br />
        <textarea id="message" rows="5" cols="50" placeholder="Write your query here..."></textarea><br />
        <button type="submit">Send Message</button>
      </form>
    </section>

  </div>

  <script src="script.js"></script>
</body>
</html>
