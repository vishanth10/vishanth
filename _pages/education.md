---
layout: page
permalink: /education/
title: Education
description:
nav: true
nav_order: 3
---


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Education</title>
<style>
    .content {
        display: none;
        margin-top: 10px;
    }

    .toggle-button {
        cursor: pointer;
        color: blue;
        margin-bottom: 5px;
    }
</style>
</head>
<body>

<div>
    <div class="toggle-button" onclick="toggleContent('ucla')">MS in Business Analytics (Data Science) - UCLA</div>
    <div id="ucla" class="content">
        <p><strong>University of California, Los Angeles</strong></p>
        <p>Sep 2023 - Dec 2024 (Expected)</p>
        <p><strong>Courses:</strong> Computer Science, Statistics, Machine Learning, Analytics</p>
    </div>
</div>

<div>
    <div class="toggle-button" onclick="toggleContent('nitt')">BS Industrial Engineering, Computer Science - NIT-T</div>
    <div id="nitt" class="content">
        <p><strong>National Institute of Technology, Tiruchirapalli (NIT-T)</strong></p>
        <p>Jul 2017 - May 2022</p>
        <p><strong>GPA:</strong> 9.1/10</p>
        <p><strong>Courses:</strong> Computer Science, Industrial Engineering, Math, Electives</p>
    </div>
</div>

<script>
function toggleContent(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none") {
        content.style.display = "block";
    } else {
        content.style.display = "none";
    }
}
</script>

</body>
</html>


<!--
<hr style="border:2px solid gray">

<figure style="display: flex; align-items: center;">
    <img src="../assets/img/ucla.png"  alt="Sample Image" style="width:50px; margin-right: 10px;"/>
    <figcaption>
        <span style="font-size: 25px;"><b> MS in Business Analytics (Data Science)</b></span><br>
        <span style="font-size: 25px;"> University of California, Los Angeles </span><br>
    </figcaption>
</figure>

Sep 2023 - Dec 2024 (Expected)

**Courses:** 
- **Computer Science :** 
    - SQL, Data Management
- **Statistics**
    - Statistics, Probablity
- **Machine Learning**
    - Machine Learning, Advance Machine Learning, Optimisation
- **Analytics**
    - Prescriptive Models and Data Analytics, Business Fundamentals, Market Analytics, A/B Testing, Finance
    - Business, Economics, Finance.


<hr style="border:1px solid gray">

<figure style="display: flex; align-items: center;">
    <img src="../assets/img/NITT_logo.png"  alt="Sample Image" style="width:50px; margin-right: 10px;"/>
    <figcaption>
        <span style="font-size: 25px;"><b>BS Industrial Engineering, Computer Science</b></span><br>
        <span style="font-size: 25px;">National Institute of Technology, Tiruchirapalli (NIT-T)</span><br>
    </figcaption>
</figure>
<!-- #### **BS NIT 

Jul 2017 - May 2022

**GPA:** 9.1/10 

**Courses:**
- **Computer Science :** 
    - Operating Systems, Computer Network, Database Management Systems
    - Data Structures & Algorithms, Computer Architecture
    - Software Engineering
- **Industrial Engineering :**
    - Finite Element Analysis, Product Development Strategy, Quality Relaibility Engineering
    - Thermodynamic, Kinematics and Dynamics of Machine, CAD/CAM, Lean Manufacturing, Mechanics of Solids and Fluids
    - Operation Research, Supply Chain Management.
- **Math:** 
    - Linear Algebra, Vector Theory, Differential Calculas
    - Probability and Statistics.
- **Electives:** 
    - Big Data Analytics, Project Management, System Simulation



<hr style="border:1px solid gray">
>>

--!>
