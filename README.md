<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dong Hang's Resume</title>
  <style>
    /* Reset & base */
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #e9f0f7, #f4f9fc);
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #2c3e50;
      color: #ecf0f1;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0 0 10px;
      font-weight: 700;
      font-size: 2.8rem;
      letter-spacing: 1.2px;
    }
    header p {
      margin: 5px 0;
      font-weight: 300;
      font-size: 1.1rem;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      color: #bdc3c7;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .section {
      background-color: #fff;
      border-radius: 10px;
      padding: 25px 30px;
      margin-bottom: 30px;
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.05);
      transition: transform 0.3s ease;
    }
    .section:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #34495e;
      margin-top: 0;
      margin-bottom: 15px;
      font-weight: 700;
      border-left: 6px solid #2980b9;
      padding-left: 12px;
      font-size: 1.8rem;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }
    li {
      margin-bottom: 12px;
      font-size: 1.05rem;
      position: relative;
      padding-left: 15px;
    }
    li::before {
      content: "•";
      color: #2980b9;
      position: absolute;
      left: 0;
      font-size: 1.3rem;
      line-height: 1;
      top: 0;
    }

    a {
      color: #2980b9;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #1c5980;
      text-decoration: underline;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 15px;
    }
    strong {
      color: #2c3e50;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      h2 {
        font-size: 1.4rem;
      }
      .container {
        margin: 20px auto;
        padding: 0 15px;
      }
      .section {
        padding: 20px 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Dong Hang</h1>
    <p>Wastewater Treatment Engineer</p>
    <p>The environment needs everyone's care, and water resources need everyone's protection.</p>
  </header>

  <div class="container">
    <div class="section">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:donghangdb@gmail.com">donghangdb@gmail.com</a></p>
      <p>Social Media: WeChat</p>
    </div>

    <div class="section">
      <h2>Education</h2>
      <ul>
        <li>University of Science and Technology of Liaoning, Major in Computer Information Management, Graduated in June 2021</li>
      </ul>
    </div>

    <div class="section">
      <h2>Work Experience</h2>
      <p><strong>Huadian Sihanoukville Power Co., Ltd.</strong> — Chief Chemist<br>
      Sep 2021 – Present (3 years 8 months)</p>
      <p>Responsible for chemical team operations: supplying demineralized water, seawater desalination, domestic sewage treatment, oily and coal-containing wastewater management. Ensured proper operation of purification systems, water-steam quality control, electrolysis hydrogen production, and seawater chlorination. Familiar with chemical equipment principles, capable of handling emergencies and coordinating with engineering staff on technical tasks and team training.</p>
    </div>

    <div class="section">
      <h2>Skills</h2>
      <ul>
        <li>Polishing treatment systems</li>
        <li>Raw water pretreatment systems</li>
        <li>Seawater chlorination</li>
        <li>Electrolytic hydrogen production</li>
        <li>RO systems, EDI systems, UF systems, MF systems</li>
        <li>Cation/Anion exchangers</li>
        <li>Domestic sewage treatment to surface water</li>
        <li>Recycling of industrial wastewater</li>
      </ul>
    </div>

    <div class="section">
      <h2>Project Experience</h2>
      <p><strong>Cambodia Power Plant Water Treatment Project - China Huadian</strong></p>
      <p>Description: The project treats seawater and well water to produce high-quality boiler feedwater using a system consisting of ultrafiltration, seawater reverse osmosis, two-stage freshwater reverse osmosis, and EDI. Pretreatment capacity is 2×300 m³/h, desalination output is 2×76 t/h. The system can switch modes depending on water source availability to ensure steady freshwater supply.</p>
      <p>Achievement: Responsible for all wastewater, sewage, and drinking water treatment for the plant. Ensured compliant water quality and stable water supply, enabling full-load power generation. The plant contributes about 30% of Cambodia's national electricity grid output.</p>
    </div>
  </div>
</body>
</html>
