---
layout: page
permalink: /code/
title: code
nav: true
nav_order: 4
---

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Software</title>
  <style>
    .software-entry {
      margin-bottom: 30px;
      padding: 15px;
      border: 1px solid #ddd;
      border-radius: 8px;
      background-color: #f9f9f9;
    }

    .software-entry h3 {
      margin-top: 0;
    }

    .software-entry p {
      margin: 10px 0;
      font-size: 14px;
    }

    .software-entry .badges {
      display: flex;
      flex-wrap: wrap; /* Ensures badges wrap if they don't fit in one row */
      gap: 10px; /* Adds space between badges */
    }

    .software-entry .badges a {
      text-decoration: none; /* Removes underline from links */
    }

    .software-entry .badges img {
      vertical-align: middle;
      height: 20px; /* Uniform height for all badges */
    }
  </style>
</head>

<body>
  <div class="software-entry">
    <h3><a href="https://github.com/KumarLabJax/ptz-seizure-supervised" target="_blank">casebase</a></h3>
    <p>
      <a href="https://www.biorxiv.org/content/10.1101/2024.05.29.596520v1" target="_blank">
        Journal Article: Visual detection of seizures in mice using supervised machine learning
      </a>
    </p>
    <p>
    Data and scripts for reproducing results in the seizure manuscript. To appear in Cell Reports Methods (2025). 
    </p>
</div>
</body>