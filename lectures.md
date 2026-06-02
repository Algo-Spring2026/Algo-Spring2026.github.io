---
layout: page
title: Lectures
permalink: /lectures/
---

<style>
  .quizzes-container { max-width: 100%; overflow-x: auto; }
  .quizzes-table { width: 100%; border-collapse: collapse; font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.05); margin: 1.5rem 0; }
  .quizzes-table thead tr { background: #2f4454; color: #fff; text-align: left; font-weight: 600; }
  .quizzes-table th, .quizzes-table td { padding: 14px 12px; border-bottom: 1px solid #e2e8f0; vertical-align: middle; }
  .quizzes-table tbody tr { background-color: #fff; transition: all 0.2s ease; }
  .quizzes-table tbody tr:nth-child(even) { background-color: #f8fafc; }
  .quizzes-table tbody tr:hover { background-color: #fef2f4; transform: scale(1.01); }
  .download-link { display: inline-flex; align-items: center; gap: 6px; background: #f1f5f9; padding: 6px 12px; border-radius: 30px; font-size: 0.85rem; font-weight: 500; color: #994c5f; text-decoration: none; transition: background 0.2s; }
  .download-link:hover { background: #da7b93; color: #fff; text-decoration: none; }
  .two-columns { display: flex; flex-wrap: wrap; gap: 2rem; margin: 1rem 0; }
  .column { flex: 1; min-width: 280px; }
  .column h2 { margin-top: 0; color: #1c3334; border-bottom: 2px solid #da7b93; display: inline-block; padding-bottom: 0.3rem; }
  .supplement-card { margin-top: 2rem; background: #f1f5f9; border-radius: 16px; padding: 1.2rem 1.5rem; border-left: 5px solid #994c5f; }
  .supplement-card h3 { margin-top: 0; color: #1c3334; }
  .intro-text { margin-bottom: 1rem; }
  @media (max-width: 700px) {
    .quizzes-table th, .quizzes-table td { padding: 10px 8px; }
    .download-link { padding: 4px 8px; font-size: 0.75rem; }
  }
</style>

<div class="quizzes-container">
  <p class="intro-text">Lecture slides will be uploaded before each session. Below are the quiz files and answer keys for this course.</p>

  <div class="two-columns">
    <div class="column">
      <h2>📝 Quizzes</h2>
      <table class="quizzes-table">
        <thead>
          <tr><th>Quiz</th><th>Title</th><th>Download</th></tr>
        </thead>
        <tbody>
          <tr><td style="text-align:center;">1</th><td>Quiz 1</th><td><a class="download-link" href="/static_files/quizzes/Quiz01.PDF">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">2</th><td>Quiz 2</th><td><a class="download-link" href="/static_files/quizzes/Quiz02.PDF">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">3</th><td>Quiz 3</th><td><a class="download-link" href="/static_files/quizzes/Quiz03.PDF">📄 PDF</a></th></tr>
        </tbody>
      </table>
    </div>

    <div class="column">
      <h2>🔑 Answer Keys</h2>
      <table class="quizzes-table">
        <thead>
          <tr><th>Quiz</th><th>Answer Key</th><th>Download</th></tr>
        </thead>
        <tbody>
          <tr><td style="text-align:center;">1</th><td>Quiz 1 Answer</th><td><a class="download-link" href="/static_files/answer_Q/A-Algo-Quiz-1.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">2</th><td>Quiz 2 Answer</th><td><a class="download-link" href="/static_files/answer_Q/Answers%20-%20Quiz2.pdf">📄 PDF</a></th></tr>
          <tr><td style="text-align:center;">3</th><td>Quiz 3 Answer</th><td><a class="download-link" href="/static_files/answer_Q/Quiz-3%20Answers.pdf">📄 PDF</a></th></tr>
        </tbody>
      </table>
    </div>
  </div>

  <div class="supplement-card">
    <h3>📖 Supplementary Material – Maximum Flow Problem</h3>
    <p>Lecture notes on Maximum Flow, including Ford‑Fulkerson algorithm, residual networks, and the Max‑Flow Min‑Cut theorem with examples.</p>
    <a class="download-link" href="/static_files/Maximum_flow_problem.pdf">📄 Download PDF</a>
  </div>

  <p><em>More materials will be added during the semester.</em></p>
</div>
