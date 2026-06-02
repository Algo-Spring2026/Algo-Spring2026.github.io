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
    <img src="{{ site.baseurl }}/_images/screenshots/image.png.jpeg" alt="Algorithms illustration">
  </div>

  <p><strong>Lecture slides</strong> are available per session in the <a href="{{ site.baseurl }}/lectures/" class="external-link">Lectures section</a>. There is no single comprehensive handout.</p>

  <h2>📖 Recommended Books & References</h2>

  <table class="books-table">
    <thead>
      <tr>
        <th>Ref.</th>
        <th>Book Title / Authors</th>
        <th>Download / Link</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>[CLRS]</strong></th>
        <td>Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein – <em>Introduction to Algorithms</em> (MIT Press)</th>
        <td><a class="download-link" href="https://mitpress.mit.edu/books/introduction-algorithms">📄 Link</a></th>
      </tr>
      <tr>
        <td><strong>[SKI]</strong></th>
        <td>Steven Skiena – <em>The Algorithm Design Manual</em> (Springer)</th>
        <td><a class="download-link" href="https://www.algorist.com/">📄 Link</a></th>
      </tr>
      <tr>
        <td><strong>[K&T]</strong></th>
        <td>Jon Kleinberg, Éva Tardos – <em>Algorithm Design</em> (Pearson)</th>
        <td><a class="download-link" href="https://www.cs.princeton.edu/~wayne/kleinberg-tardos/">📄 Link</a></th>
      </tr>
    </tbody>
  </table>

  <p><em>More resources will be added during the semester.</em></p>

  <div class="similar-courses">
    <h3>🌐 Similar Courses</h3>
    <ul>
      <li><a href="https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/" class="external-link">MIT 6.006: Introduction to Algorithms</a> – MIT OpenCourseWare</li>
      <li><a href="https://web.stanford.edu/class/cs161/" class="external-link">CS161: Design and Analysis of Algorithms</a> – Stanford University</li>
      <li><a href="https://www.cs.princeton.edu/~wayne/kleinberg-tardos/" class="external-link">Algorithm Design (Kleinberg & Tardos)</a> – Princeton University</li>
      <li><a href="https://www.coursera.org/specializations/algorithms" class="external-link">Algorithms Specialization</a> – Stanford (Coursera)</li>
      <li><a href="https://www.youtube.com/playlist?list=PLUl4u3cNGP63EdVPNLG3ToM6LaEUuStEY" class="external-link">MIT 6.046J: Design and Analysis of Algorithms</a> – YouTube</li>
    </ul>
  </div>

  <div class="extra-card">
    <h3>🛠 Additional Course Materials</h3>
    <ul>
      <li><a href="https://leetcode.com/" class="external-link">LeetCode</a> – Practice algorithmic problems</li>
      <li><a href="https://visualgo.net/" class="external-link">VisuAlgo</a> – Algorithm visualizations</li>
      <li><a href="https://www.geeksforgeeks.org/" class="external-link">GeeksforGeeks</a> – Tutorials and problem solutions</li>
      <li><a href="https://www.python.org/" class="external-link">Python</a> – Programming language for assignments</li>
      <li><a href="https://github.com/" class="external-link">GitHub</a> – Code repository and collaboration</li>
    </ul>
    <p><em>More resources will be added during the semester.</em></p>
  </div>
</div>
