<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dong Hang's Resume</title>
  <style>
    /* Reset */
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #eef4f8;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #2a5d9f, #3d7fcc);
      color: white;
      padding: 50px 20px 60px;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    header img.avatar {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 4px solid #fff;
      object-fit: cover;
      margin-bottom: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.15);
    }
    header h1 {
      font-size: 3rem;
      margin: 0 0 10px;
      font-weight: 700;
      letter-spacing: 2px;
    }
    header p {
      margin: 8px 0;
      font-weight: 300;
      font-size: 1.15rem;
      max-width: 700px;
      line-height: 1.4;
      color: #dbe9fb;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .section {
      background: white;
      border-radius: 12px;
      padding: 30px 35px;
      margin-bottom: 30px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.07);
      transition: transform 0.3s ease;
      cursor: default;
    }
    .section:hover {
      transform: translateY(-8px);
      box-shadow: 0 15px 35px rgba(0,0,0,0.12);
    }

    h2 {
      font-weight: 700;
      font-size: 1.9rem;
      margin-top: 0;
      margin-bottom: 20px;
      color: #1c3d6a;
      border-left: 6px solid #3d7fcc;
      padding-left: 14px;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }
    li {
      margin-bottom: 14px;
      font-size: 1.1rem;
      position: relative;
      padding-left: 20px;
      color: #444;
    }
    li::before {
      content: "▹";
      position: absolute;
      left: 0;
      color: #3d7fcc;
      font-weight: bold;
      font-size: 1.2rem;
      line-height: 1;
      top: 0;
    }

    p {
      font-size: 1.1rem;
      color: #444;
      margin-bottom: 18px;
    }
    strong {
      color: #1c3d6a;
    }

    a {
      color: #3d7fcc;
      font-weight: 600;
      text-decoration: none;
      transition: color 0.25s ease;
    }
    a:hover {
      color: #1c2f5c;
      text-decoration: underline;
    }

    /* Project image styling */
    .project-image {
      display: block;
      max-width: 100%;
      height: auto;
      margin-top: 15px;
      border-radius: 10px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      cursor: zoom-in;
      transition: transform 0.3s ease;
    }
    .project-image:hover {
      transform: scale(1.05);
    }

    /* Responsive */
    @media (max-width: 600px) {
      header {
        padding-bottom: 40px;
      }
      header h1 {
        font-size: 2.2rem;
      }
      h2 {
        font-size: 1.5rem;
      }
      .container {
        margin: 20px auto;
        padding: 0 15px;
      }
      .section {
        padding: 25px 20px;
      }
      li {
        font-size: 1rem;
      }
      p {
        font-size: 1rem;
      }
      header img.avatar {
        width: 110px;
        height: 110px;
        margin-bottom: 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.pravatar.cc/140?img=12" alt="Dong Hang" class="avatar" />
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
      
      <!-- 相关项目图片 -->
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Reverse_osmosis_process.svg/320px-Reverse_osmosis_process.svg.png" alt="Reverse Osmosis Process" class="project-image" />
      
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7f/Water_treatment_plant_11.jpg/320px-Water_treatment_plant_11.jpg" alt="Water Treatment Plant" class="project-image" />
      
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9f/Industrial_wastewater_treatment_plant.jpg/320px-Industrial_wastewater_treatment_plant.jpg" alt="Industrial Wastewater Treatment Plant" class="project-image" />
    </div>
  </div>
</body>
</html>
