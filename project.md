---
layout: page
title: Course Project
permalink: /project/
---

<style>
  .project-container { max-width: 100%; overflow-x: auto; }
  .project-table { width: 100%; border-collapse: collapse; font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.05); }
  .project-table thead tr { background: #2f4454; color: #fff; text-align: left; font-weight: 600; }
  .project-table th, .project-table td { padding: 14px 12px; border-bottom: 1px solid #e2e8f0; vertical-align: middle; }
  .project-table tbody tr { background-color: #fff; transition: all 0.2s ease; }
  .project-table tbody tr:nth-child(even) { background-color: #f8fafc; }
  .project-table tbody tr:hover { background-color: #fef2f4; transform: scale(1.01); }
  .download-link { display: inline-flex; align-items: center; gap: 6px; background: #f1f5f9; padding: 6px 12px; border-radius: 30px; font-size: 0.85rem; font-weight: 500; color: #994c5f; text-decoration: none; transition: background 0.2s; }
  .download-link:hover { background: #da7b93; color: #fff; text-decoration: none; }
  .deadline-badge { background: #fef9c3; color: #854d0e; padding: 5px 12px; border-radius: 30px; font-size: 0.8rem; font-weight: 500; display: inline-block; }
  .note-card { margin-top: 2rem; background: #f1f5f9; border-radius: 16px; padding: 1.2rem 1.5rem; border-left: 5px solid #994c5f; }
  @media (max-width: 700px) { .project-table th, .project-table td { padding: 10px 8px; } .download-link { padding: 4px 8px; font-size: 0.75rem; } }
</style>

<div class="project-container">
  <table class="project-table">
    <thead>
      <tr>
        <th>Phase</th>
        <th>Description</th>
        <th>Deadline</th>
        <th>Download</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Phase 1</strong></th>
        <td>Implementation of classic algorithms: Coin Change (greedy & DP), Matrix Chain Multiplication, LIS/LCS, Huffman Coding, Graph algorithms (Dijkstra, Floyd‑Warshall), Knapsack (fractional & 0/1), and Climb Stairs. — From‑scratch coding, autograder validation.</th>
        <td><span class="deadline-badge">Ordibehesht 23, 1405</span></th>
        <td><a class="download-link" href="/static_files/projects/f1.zip">📄 ZIP</a></th>
      </tr>
      <tr>
        <td><strong>Phase 2</strong></th>
        <td>Advanced techniques: Knuth Optimization for optimal merge, Rabin‑Karp string matching, O(n log n) LIS, FPTAS for 0/1 knapsack, Edmonds‑Karp max flow, and Floyd‑Warshall all‑pairs shortest paths. — Theoretical analysis included.</th>
        <td><span class="deadline-badge">Khordad 7, 1405</span></th>
        <td><a class="download-link" href="/static_files/projects/f2.zip">📄 ZIP</a></th>
      </tr>
      <tr>
        <td><strong>Phase 3</strong></th>
        <td>NP‑hard problems: Held‑Karp DP for TSP, Hamiltonian cycle/path backtracking, Graph coloring (greedy/backtracking), 2‑approximation for metric TSP (MST‑based), and written questions on P, NP, NP‑completeness.</th>
        <td><span class="deadline-badge">Khordad 25, 1405</span></th>
        <td><a class="download-link" href="/static_files/projects/f3.zip">📄 ZIP</a></th>
      </tr>
    </tbody>
  </table>
</div>
<div class="note-card"><p><strong>📌 Note:</strong> Detailed instructions and submission guidelines will be announced via Telegram and Quera. The autograder must pass all tests. For download issues, contact TAs.</p></div>
