# 📊 SIT CSE 2024 — Semester 4 Result Dashboard

A data visualization and analysis project: a single-file, dependency-free dashboard for exploring and analyzing Semester 4 CGPA and SGPA results for the SIT Tumkur CSE 2024 batch (213 students). It turns raw result data into an interactive, ranked visualization with computed summary statistics, built as a static page.

## 🔒 Access

This dashboard is password-protected since it contains student results. It's already live on GitHub Pages — you just need the password to view it.

## ✨ Features

- 🔀 **CGPA / SGPA toggle** — switch between the two ranked views instantly
- 🔍 **Live search** — find any student by name or USN; the chart scrolls to and highlights the matching bar
- 📈 **Descriptive statistics** — max, min, average, median, mode, and standard deviation, computed and recalculated per view for quick batch-level analysis
- 📊 **Interactive bar chart** — hover or tap any bar for that student's name, USN, rank, and exact score; dashed reference lines mark the mean, median, and mode against the full distribution
- 🌙 **Dark theme, fully responsive** — works down to mobile width

## 🛠️ Tech

Plain HTML, CSS, and vanilla JavaScript. Chart is rendered directly as SVG, data is embedded inline as JSON — no frameworks, no build tools, no external dependencies besides system fonts.

## 🗂️ Data

Result data (name, USN, gender, value, percentage, rank) for both CGPA and SGPA is embedded directly in the script as a `DATA` object. To update it for a future semester, replace that object with the new records and stats.

## 📄 License

For personal / academic use.
