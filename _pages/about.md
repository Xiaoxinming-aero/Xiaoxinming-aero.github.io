---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<p>
  I am a junior undergraduate student majoring in Aircraft Design and Engineering at Shenyang Aerospace University, ranking <strong>1st in my major (1/143)</strong>. My research interests lie primarily in <strong>Experimental Fluid Mechanics</strong>, <strong>Data-driven Fluid Dynamics</strong>, and <strong>Aerodynamic Structural Design & Flow Control</strong>.
</p>
<p>
  Currently, I am leading a research project on cross-Reynolds number flow field prediction. In this project, we independently modified and assembled a 3D-printed desktop wind tunnel for flow field testing, and are exploring the application of operator learning (FNO) methods in flow field reconstruction. We are currently focusing on optimizing flow visualization and CFD data solving.
</p>
<p>
  Previously,  I participated in the CUADC as a core member (China Undergraduate Aircraft Design and Construction Innovation Grand Prix) Wing Static Load Challenge, where our team won the <strong>National First Prize</strong>. My primary contributions included CAD modeling and structural simulation, helping the team achieve an extreme static load of 48kg with a 195g structure. I am highly passionate about bridging hardware experiments with numerical simulations.
</p>

# 🔥 News
- *2026.05*: &nbsp;🎉 Started leading the cross-Reynolds number flow field prediction project and assembling the 3D-printed desktop wind tunnel.
- *2025.09*: &nbsp;🏆 Won the **Provincial First Prize** in the 2025 Liaoning Province University Student Physics Competition.
             &nbsp;🏆 Awarded the National Scholarship for Undergraduate Students and the University-level "Merit Student" (Three Good Student) Honor.
- *2024.09*: &nbsp;🥇 Won the **National First Prize** in the CUADC (China Undergraduate Aircraft Design and Construction Innovation Grand Prix).

# 💻 Selected Projects

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">正在进行</div> 
      <img src='images/wind-tunnel.png' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
   <p style="font-size: 1.2em; margin-bottom: 5px;"><strong><a href="/wind-tunnel/" style="color: #005088; text-decoration: none;">低成本桌面风洞设计与机器学习流场预测分析项目 (点击查看详情) &raquo;</a></strong></p>
    <p style="margin-top: 0; margin-bottom: 10px; font-size: 0.9em; color: #666;"><strong>项目负责人</strong> | 2025.09 - 至今</p>
    <ul style="padding-left: 20px; font-size: 0.95em; color: #444; line-height: 1.5;">
      <li style="margin-bottom: 5px;"><strong>硬件开发</strong>：独立改造并搭建了一套 3D 打印桌面风洞装置，优化了烟线流动显示效果。</li>
      <li style="margin-bottom: 5px;"><strong>数据求解</strong>：目前正在进行 CFD 数据校验与 PIV 实验数据的融合处理。</li>
      <li><strong>算法探索</strong>：计划探索算子学习（FNO）方法在流场重构中的应用，实现从稀疏实验数据到高分辨率流场的映射。</li>
    </ul>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">国一等奖</div> 
      <img src='images/CUADC-wing.png' alt="CUADC Wing" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <p style="font-size: 1.2em; margin-bottom: 5px;"><strong><a href="/cuadc-wing/" style="color: #005088; text-decoration: none;">CUADC 机翼静载挑战项目——大展弦比直机翼结构设计与验证 (点击查看详情) &raquo;</a></strong></p>
    <p style="margin-top: 0; margin-bottom: 10px; font-size: 0.9em; color: #666;"><strong>核心成员</strong> |2023.12 - 2024.12</p>
    <ul style="padding-left: 20px; font-size: 0.95em; color: #444; line-height: 1.5;">
      <li style="margin-bottom: 5px;">负责平直机翼的 CAD 建模与 Patran/Nastran 结构仿真。</li>
      <li>最终以 195g 的机翼结构实现了 48kg 的极限静载，获国家级一等奖。</li>
    </ul>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">省一等奖</div> 
      <img src='images/pressure-device.png' alt="Micro-Pressure Device" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <p style="font-size: 1.2em; margin-bottom: 5px;"><strong><a href="/pressure-device/" style="color: #005088; text-decoration: none;">基于压电陶瓷与帕斯卡原理的翼表微弱压力测量装置 (点击查看详情) &raquo;</a></strong></p>
    <p style="margin-top: 0; margin-bottom: 10px; font-size: 0.9em; color: #666;"><strong>项目负责人</strong> | 2025.03 - 2025.09</p>
    <ul style="padding-left: 20px; font-size: 0.95em; color: #444; line-height: 1.5;">
      <li style="margin-bottom: 5px;">基于压电陶瓷与帕斯卡原理，开发了一套用于微弱气动压力测量的装置（测试精度达 0.5g）。</li>
      <li>完成了 COMSOL 压电多物理场耦合仿真，并通过 Multisim 进行了后续信号处理电路的优化。</li>
    </ul>
  </div>
</div>


# 🏆 荣誉与奖项 (Selected Honors)

- **国家奖学金** (National Scholarship), *2025*
- **国家级一等奖 / 省级一等奖** (核心队员), 中国大学生飞行器设计创新大赛 (CUADC) 机翼静载挑战, *2023.092024.09*
- **国家级二等奖** (队长), 第九届国际无人飞行器创新大奖赛 无人机机翼强度, *2024.11*
- **国家级优秀奖 / 省级二等奖** (个人), 第十五届全国周培源大学生力学竞赛, *2025.08*
- **省级一等奖** (队长), 辽宁省大学生物理竞赛 (实验赛道) 命题类微弱压力测量, *2025.09*
- **省级二等奖** (个人), 辽宁省中外大学生中华经典诵写讲大赛 (篆刻赛道), *2024.10*
