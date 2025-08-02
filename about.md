---
title: About
layout: page
---

<div class="about-wrapper" style="max-width: 800px; margin: 0 auto; padding: 1rem; font-family: sans-serif;">

  <div style="display: flex; flex-direction: column; align-items: center; gap: 1.5rem; text-align: center;">

    <img 
      class="profile-about" 
      src="{% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %}" 
      alt="{{ site.title }} profile image"
      style="width: 160px; height: 160px; object-fit: cover; border-radius: 50%; box-shadow: 0 4px 12px rgba(0,0,0,0.1);" 
      loading="lazy"
    />

    <p style="text-align: justify; max-width: 700px;">
      Hi, I’m <strong>Pranav</strong> – an acoustics engineer with a deep passion for sound and musical systems. I hold a Bachelor’s degree in Mechanical Engineering and a Master’s in Acoustical and Vibration Engineering. My academic journey and industry experience span mechanical systems, computational acoustics, numerical modelling, and hands-on work with tools like MATLAB, Python, and COMSOL Multiphysics.
    </p>

    <p style="text-align: justify; max-width: 700px;">
      My curiosity has always revolved around understanding how systems work—whether it's a vibrating structure, a musical instrument, or a complex software environment. During my Master’s, I focused on vibroacoustic modelling, sound radiation, and finite element analysis. My main project involved scanning and modelling an 18th-century square piano to analyse its acoustic behaviour. This work combined CT scanning, experimental testing (hammer tests), and numerical optimisation—developing my advanced modelling skills using COMSOL Multiphysics, MATLAB, and other simulation tools.
    </p>
  </div>

  <hr style="margin: 2rem 0;" />

  <h2 style="text-align: center;">🎓 Education</h2>

  <div style="text-align: center; line-height: 1.8;">
    <p><strong>University of Southampton</strong><br/>
    MSc. Acoustical and Vibration Engineering (2023–2025), with Distinction</p>

    <p><strong>Pondicherry University</strong><br/>
    B.Tech in Mechanical Engineering (2017–2021), First Class</p>
  </div>

  <hr style="margin: 2rem 0;" />

  <h2 style="text-align: center;">🛠️ Technical Skills</h2>

  <div style="max-width: 700px; margin: 0 auto;">
    <h3>🔊 Audio & Acoustics</h3>
    <ul>
      <li>Signal Processing</li>
      <li>Electroacoustics</li>
      <li>Active Control of Sound and Vibration</li>
      <li>Basic Machine Learning</li>
    </ul>

    <h3>💻 Programming & Scripting</h3>
    <ul>
      <li>Python</li>
      <li>MATLAB / Simulink</li>
      <li>OpenCV</li>
      <li>LaTeX</li>
      <li>C++</li>
      <li>MySQL</li>
      <li>Mathematica</li>
      <li>JCL / NATURAL</li>
    </ul>

    <h3>🧰 Simulation & Design Tools</h3>
    <ul>
      <li>COMSOL Multiphysics</li>
      <li>AutoCAD</li>
      <li>SolidWorks</li>
    </ul>
  </div>

  <hr style="margin: 2rem 0;" />

  <h2 style="text-align: center;">💬 Get in Touch</h2>

  <div style="text-align: center; font-size: 1.1rem;">
    <p>📞 <strong>Phone:</strong> +44 7383 773550</p>
    <p>📧 <strong>Email:</strong> <a href="mailto:rickypranav@outlook.com">rickypranav@outlook.com</a></p>
  </div>

</div>
