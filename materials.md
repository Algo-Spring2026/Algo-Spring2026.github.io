---
layout: page
title: Materials
permalink: /materials/
---

<style>
  .materials-container {
    max-width: 100%;
  }
  .image-card {
    float: right;
    margin: 0 0 20px 20px;
    background: #f8fafc;
    padding: 10px;
    border-radius: 16px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    max-width: 200px;
    text-align: center;
  }
  .image-card img {
    max-width: 100%;
    border-radius: 12px;
  }
  .books-table {
    width: 100%;
    border-collapse: collapse;
    font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    margin: 1.5rem 0;
  }
  .books-table thead tr {
    background: #2f4454;
    color: #ffffff;
    text-align: left;
    font-weight: 600;
  }
  .books-table th,
  .books-table td {
    padding: 14px 12px;
    border-bottom: 1px solid #e2e8f0;
    vertical-align: middle;
  }
  .books-table tbody tr {
    background-color: #ffffff;
    transition: all 0.2s ease;
  }
  .books-table tbody tr:nth-child(even) {
    background-color: #f8fafc;
  }
  .books-table tbody tr:hover {
    background-color: #fef2f4;
    transform: scale(1.01);
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }
  .download-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: #f1f5f9;
    padding: 6px 12px;
    border-radius: 30px;
    font-size: 0.85rem;
    font-weight: 500;
    color: #994c5f;
    text-decoration: none;
    transition: background 0.2s;
  }
  .download-link:hover {
    background: #da7b93;
    color: #ffffff;
    text-decoration: none;
  }
  .external-link {
    color: #994c5f;
    text-decoration: none;
    font-weight: 500;
  }
  .external-link:hover {
    text-decoration: underline;
  }
  .handout-card {
    background: #f1f5f9;
    border-radius: 16px;
    padding: 1rem 1.5rem;
    margin: 1.5rem 0;
    border-left: 5px solid #994c5f;
  }
  .similar-courses {
    background: #f8fafc;
    border-radius: 16px;
    padding: 1.2rem 1.5rem;
    margin: 1.5rem 0;
    border-left: 5px solid #994c5f;
    clear: both;
  }
  .similar-courses ul {
    margin: 0;
    padding-left: 1.2rem;
  }
  .similar-courses li {
    margin: 0.5rem 0;
  }
  .extra-card {
    margin-top: 1.5rem;
    background: #f1f5f9;
    border-radius: 16px;
    padding: 1.2rem 1.5rem;
    border-left: 5px solid #994c5f;
    clear: both;
  }
  .extra-card h3 {
    margin-top: 0;
    color: #1c3334;
  }
  .extra-card ul {
    margin-bottom: 0;
  }
  @media (max-width: 700px) {
    .image-card {
      float: none;
      margin: 0 auto 20px auto;
    }
    .books-table th, .books-table td {
      padding: 10px 8px;
    }
    .download-link {
      padding: 4px 8px;
      font-size: 0.75rem;
    }
  }
</style>

<div class="materials-container">
  <div class="image-card">
    <img src="{{ site.baseurl }}/_images/screenshots/image.png.jpeg" alt="Algorithms">
  </div>

  <div class="handout-card">
    <strong>Hand-out</strong><br>
    Algorithm Design - Spring 2026 - Dr. Eskandari<br>
    <a class="download-link" href="{{ site.baseurl }}/static_files/presentations/algorithms_spring2026.pdf">📄 Download full textbook (PDF)</a>
  </div>

  <h2>📖 Recommended Books & References</h2>

  <table class="books-table">
    <thead>
      <tr>
        <th>#</th>
        <th>Book / Resource</th>
        <th>Link</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>1</strong></td>
        <td><em>Introduction to Algorithms</em> – Cormen, Leiserson, Rivest, Stein</th>
        <td><a class="external-link" href="#">Official site</a> (to be added)</th>
      </tr>
      <tr>
        <td><strong>2</strong></th>
        <td><em>The Algorithm Design Manual</em> – Steven Skiena</th>
        <td><a class="external-link" href="#">Official site</a> (to be added)</th>
      </tr>
      <tr>
        <td><strong>3</strong></th>
        <td><strong>Online Judge Practice:</strong> LeetCode | HackerRank</th>
        <td><a class="external-link" href="https://leetcode.com/">LeetCode</a> | <a class="external-link" href="https://www.hackerrank.com/">HackerRank</a></th>
      </tr>
    </tbody>
  </table>

  <p><em>More resources will be added during the semester.</em></p>

  <div class="similar-courses">
    <h3>🌐 Similar Courses</h3>
    <ul>
      <li><a href="https://www.ebooksworld.ir/post/index/949" class="external-link">Grokking Algorithms</a> – visual & simple guide to algorithms with Python</li>
      <li><a href="https://web.stanford.edu/class/archive/cs/cs161/cs161.1138/" class="external-link">CS161 2013</a> – Stanford University</li>
      <li><a href="https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/" class="external-link">6.046J Design and Analysis of Algorithms (Spring 2015)</a> – MIT OpenCourseWare</li>
      <li><a href="https://www.cs.cmu.edu/afs/cs/Web/People/15451/index.html" class="external-link">15-451/651: Algorithms</a> – Carnegie Mellon University (check Schedule section for materials)</li>
      <li><a href="https://student.cs.uwaterloo.ca/~cs341/" class="external-link">CS 341: Algorithms</a> – University of Waterloo</li>
      <li><a href="https://www.cs.purdue.edu/homes/tamaldey/course/580/" class="external-link">CS 580: Algorithms</a> – Purdue University</li>
      <li><a href="https://www.cs.ox.ac.uk/teaching/courses/2021-2022/algdesign/" class="external-link">Design and Analysis of Algorithms (2021-2022)</a> – University of Oxford</li>
      <li><a href="https://www.cs.princeton.edu/~wayne/kleinberg-tardos/" class="external-link">Algorithm Design (Kleinberg & Tardos) Lecture Slides</a> – Princeton University</li>
      <li><a href="https://www.cs.princeton.edu/~wayne/kleinberg-tardos/pearson/" class="external-link">Algorithm Design (Official Pearson Slides)</a> – Princeton University</li>
      <li><a href="https://www.ebooksworld.ir/post/index/949" class="external-link">Grokking Algorithms (Illustrated Guide)</a> – EBooksWorld</li>
    </ul>
  </div>

  <div class="extra-card">
    <h3>🛠 Additional Course Materials</h3>
    <ul>
      <li><a href="https://docs.python.org/3/tutorial/" class="external-link">Python for Beginners</a> – Official Python tutorial</li>
      <li><a href="https://visualgo.net" class="external-link">Visualgo</a> – Algorithm visualizations</li>
      <li><a href="https://geeksforgeeks.org" class="external-link">GeeksforGeeks</a> – Algorithm problems and solutions</li>
    </ul>
    <p><em>More resources will be added during the semester.</em></p>
  </div>
</div>
