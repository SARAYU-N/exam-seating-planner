# Exam Seating Planner

A smart web-based application designed to generate optimized exam seating arrangements efficiently. This tool helps institutions automate seating allocation while minimizing conflicts between students of the same department.

---

## Overview

The Exam Seating Planner allows users to import student data, define exam rooms, and automatically generate seating arrangements using algorithmic approaches. It ensures better distribution of students and improves overall exam management.

---

## Features

- Import student data directly from Google Sheets (copy-paste supported)
- Manual student entry option
- Add and manage multiple exam rooms with capacities
- Automatic seating allocation
- Conflict detection for same-department students
- Two algorithm options:
  - **Greedy Algorithm**
  - **Dynamic Programming (DP) Optimized Algorithm**
- Visual seating layout for each room
- Export seating data as CSV
- Generate detailed PDF reports
- Real-time statistics (utilization, conflicts, room usage)

---

## Technologies Used

- **HTML, CSS, JavaScript**
- **jsPDF** (for PDF generation)
- **jsPDF-AutoTable** (for structured tables)

---

## How It Works

1. Import student data by copying from Google Sheets and pasting into the input area  
2. Map columns such as Name and Department  
3. Add exam rooms along with their seating capacity  
4. Choose seating preferences (e.g., separate same-department students)  
5. Generate the seating plan using available algorithms  
6. View results visually and export if needed  

The system uses both Greedy and Dynamic Programming approaches to optimize seating and reduce conflicts.

---

## Algorithms

### Greedy Algorithm
- Assigns students sequentially  
- Faster execution  
- May result in minor conflicts  

### DP Optimized Algorithm
- Distributes students more evenly across departments  
- Reduces adjacency conflicts  
- More efficient for balanced seating  

---

## Use Cases

- Colleges and universities conducting examinations  
- Institutions managing large student seating arrangements  
- Automated invigilation planning systems  

---

## Future Enhancements

- Login system for administrators  
- Cloud-based data storage  
- Integration with live Google Sheets API  
- Advanced AI-based optimization  
- Multi-floor or building-level seating planning  

---

## Project Structure

- Single-page web application  
- Sidebar for input and configuration  
- Main panel for visualization and results  

---

## Author

**Sarayu**  
B.Tech Computer Science Engineering (2nd Year)

---
