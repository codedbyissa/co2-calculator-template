# 🌍 CO2 Calculator — CO2 Emissions Calculation Model

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

![Preview](https://media.byissa.dev/co2/preview.webp)

<p align="center">
  <a href="#about">About</a> •
  <a href="#features">Features</a> •
  <a href="#structure">Structure</a> •
  <a href="#technologies">Technologies</a> •
  <a href="#how_to_use">How to Use</a> 
</p>

<h2 id="about">📌 About</h2>

CO2 Calculator is a static and responsive web model designed for companies to calculate their CO2 emissions across multiple categories, including fuel consumption, employee commuting, fugitive emissions, energy consumption, product and equipment transport, and business trips. It features:

- A dashboard to visualize monthly and yearly emissions
- Detailed analysis per emission category
- Data input pages for measurements
- Queue system to track bulk calculation status
- Configurable measurement settings for accuracy
- General and category-specific report generation

This project is built with PHP, HTML, CSS, and JavaScript, aiming to provide an easy-to-use and comprehensive environmental impact tool.

[![project](https://img.shields.io/badge/📱Visit_this_project-000?style=for-the-badge&logo=project)](https://co2c.byissa.dev/)

<h2 id="features">✨ Features</h2>

- Multi-category CO2 emissions calculation
- Responsive UI for desktop and mobile
- Dashboard with graphs and data summaries
- Measurement data entry with validation
- Calculation queue management
- Configurable settings per emission category
- Generate downloadable reports

<h2 id="structure">📁 Structure</h2>

```txt
📂 root/
 ├ 📄 index.php                    # homepage
 ├ 📄 README.md
 ├ 📄 styles.css                   # Global styles
 ├ 📂 create/                      # Insert measurement
 │ ├ 📄 index.php                  
 │ ├ 📄 styles.css
 │ └ 📂 source/                   
 │   ├ 📄 commuting.php
 │   ├ 📄 emissions.php
 │   ├ 📄 energy.php
 │   ├ 📄 fuel.php
 │   ├ 📄 shipping.php
 │   ├ 📄 styles.css
 │   └ 📄 trip.php
 ├ 📂 queue/                        # calculation queue 
 │ ├ 📄 index.php                 
 │ └ 📄 styles.css
 ├ 📂 reports/
 │ ├ 📄 index.php                   # Report overview
 │ ├ 📄 styles.css
 │ └ 📂 source/                   
 │   ├ 📄 commuting.php
 │   ├ 📄 emissions.php
 │   ├ 📄 energy.php
 │   ├ 📄 fuel.php
 │   ├ 📄 general.php
 │   ├ 📄 ghg.php
 │   ├ 📄 shipping.php
 │   ├ 📄 styles.css
 │   └ 📄 trip.php
 ├ 📂 settings/                     # Measurement configuration
 │ ├ 📄 index.php                  
 │ ├ 📄 styles.css
 │ └ 📂 source/                   
 │   ├ 📄 commuting.php
 │   ├ 📄 emissions.php
 │   ├ 📄 energy.php
 │   ├ 📄 fuel.php
 │   ├ 📄 shipping.php
 │   ├ 📄 styles.css
 │   └ 📄 trip.php
 ├ 📂 shared/
 │ ├ 📄 global.css                 # Global shared styles
 │ └ 📄 nav.php                    # Navigation bar component
 └ 📂 view/                        # view emissions
   ├ 📄 index.php                 
   ├ 📄 styles.css
   └ 📂 source/
     ├ 📄 commuting.php
     ├ 📄 emissions.php
     ├ 📄 energy.php
     ├ 📄 fuel.php
     ├ 📄 shipping.php
     ├ 📄 styles.css
     └ 📄 trip.php
```

<h2 id="technologies">🧪 Technologies</h2>

- PHP
- HTML5
- CSS3
- JavaScript

<h2 id="how_to_use">🚀 How to Use</h2>

1. Upload the project files to a PHP-enabled web server.  
2. Access `index.php` in your browser to open the **Painel de emissões**, which provides a summary overview of emissions.   
3. Navigate to the **Inserir medição** section to input measurement data for each emission category.  
4. Review the **Ver emissões** dashboard for visual summaries of emissions.
5. Use the **Fila de cálculos** section to monitor bulk calculations.  
6. Configure calculation parameters in **Configurar medições** for accuracy.  
7. Visit **Relatórios** to view and export emissions analysis.  
