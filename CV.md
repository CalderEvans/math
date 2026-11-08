---
title: CV
author: Calder Evans
layout: default
---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Calder Evans – CV</title>
<style>
  /* Styles are scoped to .cv so they won't clash with the rest of the site */
  body { margin: 0; background: #f2f2f2; }

  .cv {
    box-sizing: border-box;
    max-width: 8.5in;
    margin: 24px auto;
    padding: 0.75in 0.9in;
    background: #fff;
    color: #000;
    font-family: "Times New Roman", Times, "Liberation Serif", serif;
    font-size: 11pt;
    line-height: 1.2;
    box-shadow: 0 1px 6px rgba(0,0,0,.15);
  }
  .cv a { color: inherit; text-decoration: none; }
  .cv a:hover { text-decoration: underline; }

  /* Header */
  .cv-name { margin: 0; text-align: center; font-size: 17pt; font-weight: bold; }
  .cv-contact { margin: 0 0 6pt; text-align: center; font-size: 12pt; }

  /* Section headings: bold caps with a rule underneath */
  .cv h2 {
    margin: 12pt 0 0;
    padding: 0;
    font-size: 12pt;
    font-weight: bold;
    border-bottom: 0.75pt solid #000;
  }

  /* Entry lines: left text + right-aligned text */
  .row { display: flex; justify-content: space-between; align-items: baseline; gap: 12px; }
  .row .right { white-space: nowrap; text-align: right; }
  .org { font-weight: bold; }
  .sub { font-style: italic; padding-left: 0.1in; }
  .entry { margin-bottom: 11pt; }
  .entry:last-child { margin-bottom: 0; }

  .cv p { margin: 0; }
  .cv ul { margin: 0; padding-left: 0.5in; list-style: disc; }
  .cv ul ul { list-style: none; padding-left: 0.4in; }
  .cv ul ul li::before { content: "-"; display: inline-block; width: 0.3in; margin-left: -0.3in; }
  .cv li { margin: 0; padding-left: 0.05in; }
  .cv li::marker { font-size: 11pt; }

  /* Phones */
  @media (max-width: 640px) {
    .cv { margin: 0; padding: 20px 16px; box-shadow: none; }
    .row { flex-direction: column; gap: 0; }
    .row .right { white-space: normal; text-align: left; }
    .cv-contact { font-size: 11pt; }
  }

  /* Printing / Save as PDF */
  @media print {
    body { background: #fff; }
    .cv { margin: 0; padding: 0; max-width: none; box-shadow: none; }
    .entry { break-inside: avoid; }
    .cv h2 { break-after: avoid; }
    @page { size: letter; margin: 0.75in 0.9in; }
  }
</style>
</head>
<body>
<main class="cv">

  <h1 class="cv-name">Calder Evans</h1>
  <p class="cv-contact">Flagstaff, AZ | <a href="mailto:cme332@nau.edu">cme332@nau.edu</a> | (505) 501 – 2563 | <a href="https://calderevans.github.io/math">calderevans.github.io/math</a></p>

  <h2>PROFILE</h2>
  <p>Adaptable graduate student and instructor with knowledge of classroom management, course design, and curriculum development. Aiming to leverage my abilities to fulfill the position.</p>

  <h2>EDUCATION</h2>
  <div class="entry">
    <div class="row"><span class="org">Northern Arizona University</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>Master of Science in Mathematics | GPA 3.65</span><span class="right">August 2025 – Present</span></div>
    <div class="sub">Expected Graduation: May 2027</div>
    <ul>
      <li><strong>Relevant Coursework:</strong> Abstract Algebra, Complex Analysis, Python, Differential Equations, Linear Algebra, Real Analysis, Commutative Algebra, Functional Analysis</li>
      <li><strong>Awards/Honors:</strong>
        <ul>
          <li>Graduate Teaching Assistantship</li>
          <li>NAU Department of Mathematics and Statistics Johnson-Ratliff Memorial Scholarship</li>
        </ul>
      </li>
    </ul>
  </div>
  <div class="entry">
    <div class="row sub"><span>Bachelor of Science in Mathematics | Minor in Anthropology | GPA: 3.45</span><span class="right">August 2021 – May 2025</span></div>
    <ul>
      <li><strong>Relevant Coursework:</strong> Calculus, Mathematical Reasoning, Linear Algebra, Real Analysis, Abstract Algebra, Statistical Analysis, Data Wrangling, Topology</li>
      <li><strong>Awards/Honors:</strong>
        <ul>
          <li>NAU Gold Scholarship Recipient</li>
          <li>NAU Honors College Graduate</li>
          <li>2024 ASA Arizona DataFest: Judge’s Choice Winner</li>
          <li>2025 ASA Arizona DataFest: Best Use of Analytical Techniques Winner</li>
        </ul>
      </li>
    </ul>
  </div>

  <h2>WORK EXPERIENCE</h2>
  <div class="entry">
    <div class="row"><span class="org">Graduate Student Instructor – NAU Department of Mathematics and Statistics</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>Finite Mathematics – Business Calculus</span><span class="right">August 2026 – Present</span></div>
    <ul>
      <li>Full instructor of record for one section on MAT 121 with an enrollment of 40 students per semester.</li>
      <li>Prepared lectures and in class activities, held office hours,</li>
      <li>Wrote, proctored, and grades 4 midterm exams and a final exam</li>
      <li>Maintain active communication with students on their grade and their learning progression</li>
      <li>Regularly collaborated with Course Coordination team to provide consistent instructional expectations for all MAT 121 sections</li>
    </ul>
  </div>
  <div class="entry">
    <div class="row sub"><span>Quantitative Reasoning</span><span class="right">August 2025 – May 2025</span></div>
    <ul>
      <li>Full instructor of record for two sections of MAT 114 with enrollments of 36 students per section per semester.</li>
      <li>Prepared lectures and in class activities, held office hours, and guided students during lab work</li>
      <li>Grade homework, written exams, and digital exams while providing thoughtful feedback to help students understand their mistakes and perform better on future assignments and exams</li>
      <li>Create daily presentations to communicate course content to students efficiently</li>
      <li>Maintain active communication with students on their grade and their learning progression</li>
      <li>Extensively utilized Building Thinking Classroom strategies; entire class sessions frequently centered around students collaboratively working and discussing scaffolded selections of problems</li>
      <li>Regularly collaborated with Course Coordination team to provide consistent instructional expectations for all MAT 114 sections</li>
    </ul>
  </div>
  <div class="entry">
    <div class="row"><span class="org">College Instructor – NAU Upward Bound Math and Science</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>High School Math Theory</span><span class="right">May 2024 – July 2026</span></div>
    <ul>
      <li>Provided instruction and oversaw a group of 20 first-generation college and Native American students in a high-school math class aimed at growing their interest in studying math through graph theory, combinatorics, game theory, and number theory</li>
      <li>Managed the classroom effectively to ensure all students had the ability to learn</li>
      <li>Adjusted lesson plans to meet each student’s level of understanding and background knowledge</li>
      <li>Evaluated and assigned student’s work and participation for each assignment and for a final grade</li>
      <li>Actively communicated with colleagues to ensure students had the best chances of success</li>
    </ul>
  </div>
  <div class="entry">
    <div class="row"><span class="org">High School Math Tutor – NAU Upward Bound Math and Science</span><span class="right org">Virtual</span></div>
    <div class="row sub"><span>Algebra / Pre-Calculus / Calculus / Geometry</span><span class="right">August 2024 – December 2025</span></div>
    <ul>
      <li>Provided help for students with math related homework questions and assignments virtually through zoom</li>
      <li>Monitored students understanding and provided additional resources or practice problems</li>
    </ul>
  </div>
  <div class="entry">
    <div class="row"><span class="org">Math Achievement Program Team Lead – NAU Math Achievement Program</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>Calculus I / Calculus II / Calculus III</span><span class="right">January 2025 – May 2025</span></div>
    <ul>
      <li>Worked directly with NAU Academic Success Center Assistant Director on supervising the Math Achievement Program, including overseeing fifteen employees across the calculus subjects</li>
      <li>Communicated with professors on scheduling and course materials, trained new employees, assisted in hiring processes, and continued development of the program</li>
      <li>Retained the duties and responsibilities of a Lead Peer Math Assistant</li>
    </ul>
  </div>
  <div class="entry">
    <div class="row"><span class="org">Mathematics Grader – NAU Department of Mathematics and Statistics</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>Calculus I / Finite Mathematics / Applied Statistics / Linear Algebra</span><span class="right">August 2023 – May 2025</span></div>
    <ul>
      <li>Assigned grades to assignments while correcting mistakes and leading students in the right direction</li>
      <li>Maintained communication with professors on students’ progress of course material</li>
    </ul>
  </div>
  <div class="entry">
    <div class="row"><span class="org">Lead Peer Math Assistant – NAU Math Achievement Program</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>Calculus II</span><span class="right">January 2023 – December 2024</span></div>
    <ul>
      <li>Worked with students on homework and coursework to grow their understanding of materials and content</li>
      <li>Provided a welcoming, accommodating environment for all levels of understanding and learning styles</li>
      <li>Attended classes weekly to help professors with in-class activities</li>
      <li>Developed and delivered test reviews based on information gathered from professors</li>
      <li>Maintained active communication with professors about course content, scheduled and managed test reviews, and oversaw other Peer Math Assistants as the lead Peer Math Assistant</li>
    </ul>
  </div>

  <h2>RESEARCH EXPERIENCE</h2>
  <div class="entry">
    <div class="row"><span class="org">Thesis – NAU</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>Hyperplane Arrangements</span><span class="right">August 2026 – Present</span></div>
    <ul>
      <li>For the completion of my master’s degree, I elected to write and defend a thesis. This project was done under the supervision of NAU Associate Professor Michele Torielli.</li>
      <li>Working on Algebraic Extensions and Hyperplane Arrangements, specifically determining which situations an arrangement and its reduction modulo a prime number have isomorphic lattices via the use of weak Gröbner bases.</li>
      <li>A paper on our research is expected to be published in 2027.</li>
    </ul>
  </div>
  <div class="entry">
    <div class="row"><span class="org">Undergraduate Research – NAU</span><span class="right org">Flagstaff, AZ</span></div>
    <div class="row sub"><span>Quantum Graph Coloring</span><span class="right">August 2024 – May 2025</span></div>
    <ul>
      <li>Worked with NAU Assistant Professor Samuel Harris to study properties of graphs that are “quantum-colored”, quantum-colored graphs’ vertices are labeled with matrix valued solutions, as opposed to “coloring” each vertex with a single number like in the classical way</li>
      <li>Discovered the smallest graph that can be quantum 3-colored but not classically 3-colored by taking a known graph with these properties and removing superfluous vertices to get a graph with 110 vertices</li>
      <li>Used SageMath to create programs to check that graphs satisfy the conditions to be considered quantum 3-colorable</li>
      <li>Used SageMath to create programs to find unnecessary vertices that can be removed</li>
    </ul>
  </div>

  <h2>SKILLS &amp; INTERESTS</h2>
  <p><strong>Customer Service:</strong> Critical Thinking, Teamwork, Quick Learner, Adaptable</p>
  <p><strong>Coding Languages:</strong> Python, R, SageMath, LaTeX, HTML, Macaulay2</p>
  <p><strong>Interests:</strong> Puzzles, Teaching, Running, Baseball, Reading</p>

</main>
</body>
</html>