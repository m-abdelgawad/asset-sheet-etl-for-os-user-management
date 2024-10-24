<a name="readme-top"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="readme_files/logo.png" alt="Logo" width="80">
  <h3 align="center">Asset Sheet ETL for OS User Management</h3>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#business-case">Business Case</a></li>
        <li><a href="#technical-solution">Technical Solution</a></li>
        <li><a href="#flowchart">Flowchart</a></li>
        <li><a href="#tech-stack">Tech Stack</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<img src="readme_files/cover.jpg" alt="Cover Image">

* **Project Name:** Asset Sheet ETL for OS User Management  
* **Version:** v1.0.0  
* **Department:** Technology

---

### Business Case

This project serves as an extension to the **Automated User Management with Ansible** project. It automates the process of loading the **Assets Sheet** into a configuration SharePoint list, containing details of all machines in the company, their team owners, and their OS types. 

When a user submits a request to access a new machine, the system fetches the available machines from this configuration list. This automation reduces the manual effort required to manage machine assets and ensures that the most up-to-date information is available for user requests.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Technical Solution

I developed an ETL process to extract machine asset data from an Excel sheet, fetch the corresponding owner information from Active Directory, and load the data into the configuration SharePoint list. This ensures seamless integration with the **Automated User Management with Ansible** project, making asset management more efficient and scalable.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Flowchart

<img src="readme_files/flowchart.jpg">

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Tech Stack

This project was developed using the following tech stack:

* **Python**
* **Ansible**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Mohamed AbdelGawad Ibrahim - [@m-abdelgawad](https://www.linkedin.com/in/m-abdelgawad/) - <a href="tel:+201069052620">+201069052620</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/m-abdelgawad/
