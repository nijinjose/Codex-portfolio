---
layout: about
title: About
permalink: /
---

<div class="social-icons">
  {% if site.email %}<a href="mailto:{{ site.email }}"><i class="fas fa-envelope"></i></a>{% endif %}
  {% if site.linkedin_username %}<a href="https://www.linkedin.com/in/{{ site.linkedin_username }}"><i class="fab fa-linkedin"></i></a>{% endif %}
  {% if site.github_username %}<a href="https://github.com/{{ site.github_username }}"><i class="fab fa-github"></i></a>{% endif %}
  
</div>

<div class="row justify-content-center">
    <div class="col-md-8 text-center">
        <h1 class="mt-4">NIJIN JOSE</h1>
        <p class="lead mb-5">Data Scientist & Machine Learning Engineer</p>
        <p>
            <a href="mailto:nijinxose@gmail.com">Email</a> | 
            <a href="https://linkedin.com/in/nijinjose">LinkedIn</a> | 
            <a href="https://github.com/nijinjose">GitHub</a> | 
            <a href="https://scholar.google.com/citations?user=7e7_dq0AAAAJ"><i class="ai ai-google-scholar"></i> Google Scholar</a>
        </p>
    </div>
</div>

<div class="row">
    <div class="col-md-12">
        <div class="alert alert-light">
            <p>I build scalable AI systems and MLOps infrastructure that works in the real world 🤖🚀
            Seeking to contribute to advanced AI research and deployments at leading AI organizations.</p>
        </div>
    </div>
</div>
<hr class="my-5" />

<div class="row align-items-center mb-5">
    <div class="col-md-2 text-center">
        <div class="company-logo p-3">
            <!-- Markerstudy logo placeholder -->
            <img src="/assets/img/companies/msg.jpg" alt="Markerstudy Logo" class="company-logo" style="max-width: 100px; max-height: 30px; object-fit: contain;" />
        </div>
    </div>
    <div class="col-md-10">
        <h3>Senior Data Science and MLOps Analyst</h3>
        <h4 class="text-muted">Markerstudy Group, London, UK</h4>
        <p class="text-muted">Dec 2023 - Present</p>
        <p>I'm leading risk prediction initiatives for motor insurance using advanced ML techniques. Recently engineered a gradient boosting model with nested experiment tracking that delivered a 120K GBP annual revenue uplift!<br>
I've transformed our team's approach to ML deployment by implementing containerized services on Kubernetes and establishing robust CI/CD pipelines with Azure DevOps. My work on systematic load testing frameworks ensures our models perform reliably under various traffic conditions.<br>
Currently spearheading our cloud migration initiatives, transitioning from on-premises deployments to a scalable, cloud-native architecture in Azure.</p>
    </div>
</div>

<div class="row align-items-center mb-5">
    <div class="col-md-2 text-center">
        <div class="company-logo p-3">
            <!-- Capgemini logo placeholder -->
            <span class="display-4">🔷</span>
        </div>
    </div>
    <div class="col-md-10">
        <h3>Associate Consultant - Data Scientist and MLOps</h3>
<h4 class="text-muted">Capgemini Invent, Bangalore, India</h4>
<p class="text-muted">July 2022 – July 2023</p>
<p>Consulting gave me a crash course in delivering ML at enterprise scale. For Michelin I developed an inspection module that halved manual review time, and I helped several clients introduce Evidently-based drift monitoring to keep production models honest.<br>
A highlight was co-writing a build-versus-buy MLOps playbook that is still used by Fortune 500 teams. I also contributed to an internal tool that records the carbon footprint of ML pipelines—useful when “efficient” has to mean both fast and sustainable.</p>
    </div>
</div>

<div class="row align-items-center mb-5">
    <div class="col-md-2 text-center">
        <div class="company-logo p-3">
            <!-- ITTStar logo placeholder -->
            <span class="display-4">🔍</span>
        </div>
    </div>
    <div class="col-md-10">
        <h3>Associate Data Scientist</h3>
        <h4 class="text-muted">ITTStar Consulting LLC, Bangalore, India</h4>
        <p class="text-muted">March 2021 – May 2022</p>
        <p>Developed predictive models using AWS HealthLake that improved insurance cost estimation accuracy. Built a computer vision solution with Amazon Rekognition that achieved 82% detection accuracy for retail inventory management.<br>
Created intuitive dashboards using Amazon QuickSight and AWS Glue that transformed raw data into actionable insights. Proud to have driven a 40% increase in analytics engagement among stakeholders through data-driven implementation strategies.</p>    </div>
</div>

<div class="row align-items-center mb-5">
    <div class="col-md-2 text-center">
        <div class="company-logo p-3">
            <!-- Ethna Attributes logo placeholder -->
            <span class="display-4">🔹</span>
        </div>
    </div>
    <div class="col-md-10">
        <h3>Engineering Intern</h3>
        <h4 class="text-muted">Ethna Attributes Soft Technologies Pvt Ltd, Chennai, India</h4>
        <p class="text-muted">Aug 2019 – June 2020</p>
        <ul class="list-unstyled">
            <li>• Developed SOTA Machine learning models for predictive maintenance (tool wear analysis), reducing waste and improving tool utilization. Research published and presented at International Conference.</li>
        </ul>
    </div>
</div>

<hr class="my-5" />

<!-- Projects Section -->
<section id="projects" class="py-5">
  <div class="container">
    <h2 class="text-center mb-5">Personal Projects</h2>
    <div class="row row-cols-1 row-cols-md-2 g-4">
      {% for project in site.projects %}
        <div class="col">
          <div class="card h-100 shadow-sm">
            <div class="card-body">
              <h5 class="card-title">{{ project.title }}</h5>
              <p class="card-text">{{ project.description }}</p>
              <a href="{{ project.url | relative_url }}" class="btn btn-primary">View Project</a>
            </div>
          </div>
        </div>
      {% endfor %}
    </div>
  </div>
</section>

<hr class="my-5" />

<section id="skills" class="py-5 bg-white">
  <div class="container">
    <h2 class="text-center mb-4">Technical Skills</h2>
    <div class="row">
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Languages & ML Libraries</h5>
            <p>Python (pandas, NumPy, SciPy), SQL; scikit-learn, LightGBM, XGBoost, PyTorch; familiar with TensorFlow/Keras</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Machine Learning & Deep Learning</h5>
            <p>Predictive Modeling, Classification & Regression, Computer Vision (OpenCV, Rekognition), Time Series Forecasting, NLP (basic LLM and APIs integration and experience, Gemini Flash 2.0, xAI Grok)</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">MLOps</h5>
            <p>MLflow, Optuna, Docker, Kubernetes, Great Expectations, CI/CD Pipelines, Model Monitoring, Evidently AI</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Cloud Platforms</h5>
            <p>AWS (SageMaker, S3, Lambda, Glue, Athena), Azure (Azure ML, DevOps, AKS, Databricks)</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Data Engineering</h5>
            <p>Pandas, NumPy, PySpark, ETL, Statistical Analysis, Feature Engineering</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Programming & Tools</h5>
            <p>Python, SQL, Git, REST APIs, Postman, Jupyter, Docker</p>
          </div>
        </div>
      </div>
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Visualization Tools</h5>
            <p>Amazon QuickSight, Power BI, Streamlit, Matplotlib, Seaborn</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Education Section -->
<section id="education" class="py-5">
  <div class="container">
    <h2 class="text-center mb-5">Education</h2>
    <div class="row">
      <!-- M.Tech -->
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm custom-card">
          <div class="card-body d-flex align-items-center">
            <i class="fas fa-university fa-3x text-primary me-3"></i>
            <div>
              <h5 class="card-title">Masters in CAD/CAM/CAE (M.Tech)</h5>
              <h6 class="card-subtitle mb-2 text-muted">Vellore Institute of Technology (VIT University)</h6>
              <p class="card-text"><small class="text-muted">2018-2020 | Chennai, India | CGPA: 8.61/10</small></p>
              <p class="card-text"><small class="text-muted">Relevant Coursework: IoT, Product development, Mathematics Methods, and Modeling</small></p>
            </div>
          </div>
        </div>
      </div>
      <!-- B.E. -->
      <div class="col-md-6 mb-4">
        <div class="card h-100 shadow-sm custom-card">
          <div class="card-body d-flex align-items-center">
            <i class="fas fa-graduation-cap fa-3x text-success me-3"></i>
            <div>
              <h5 class="card-title">Bachelor of Engineering (B.E) in Mechanical Engineering</h5>
              <h6 class="card-subtitle mb-2 text-muted">Christian College of Engineering & Technology</h6>
              <p class="card-text"><small class="text-muted">2011-2015 | Bhilai, India | CGPA: 7.99/10</small></p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Certifications Section -->
<section id="certifications" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Certifications</h2>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-2 g-4">
      <!-- Certification 1 -->
      <div class="col">
        <div class="card h-100 shadow-sm custom-card cert-card">
          <div class="card-body">
            <div class="d-flex align-items-center mb-2">
              <i class="fab fa-aws fa-2x text-warning me-3"></i>
              <h5 class="card-title mb-0">AWS Certified Machine Learning Specialist</h5>
            </div>
            <p class="card-text">Advanced certification validating expertise in designing, implementing, and maintaining ML solutions using AWS technologies.</p>
          </div>
        </div>
      </div>
      <!-- Certification 2 -->
      <div class="col">
        <div class="card h-100 shadow-sm custom-card cert-card">
          <div class="card-body">
            <div class="d-flex align-items-center mb-2">
              <i class="fab fa-microsoft fa-2x text-info me-3"></i>
              <h5 class="card-title mb-0">Microsoft Certified: Azure Data Scientist Associate</h5>
            </div>
            <p class="card-text">Validated expertise in using Azure services to implement and run machine learning workloads on Azure.</p>
          </div>
        </div>
      </div>
      <!-- Certification 3 -->
      <div class="col">
        <div class="card h-100 shadow-sm custom-card cert-card">
          <div class="card-body">
            <div class="d-flex align-items-center mb-2">
              <i class="fab fa-aws fa-2x text-primary me-3"></i>
              <h5 class="card-title mb-0">AWS Cloud Practitioner</h5>
            </div>
            <p class="card-text">Foundational certification demonstrating understanding of AWS Cloud services, architecture, and pricing.</p>
          </div>
        </div>
      </div>
      <!-- Certification 4 -->
      <div class="col">
        <div class="card h-100 shadow-sm custom-card cert-card">
          <div class="card-body">
            <div class="d-flex align-items-center mb-2">
              <i class="fas fa-university fa-2x text-danger me-3"></i>
              <h5 class="card-title mb-0">Stanford Machine Learning (Coursera)</h5>
            </div>
            <p class="card-text">Completed comprehensive course covering fundamental machine learning concepts, algorithms, and implementation techniques.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Languages Section -->
<section id="languages" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Languages</h2>
    <div class="row text-center">
      <div class="col-md-3 mb-3">
        <div class="card h-100 shadow-sm custom-card">
          <div class="card-body">
            <i class="fas fa-language fa-3x text-primary mb-3"></i>
            <h5 class="card-title">English</h5>
            <p class="card-text">Professional Working Proficiency</p>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-3">
        <div class="card h-100 shadow-sm custom-card">
          <div class="card-body">
             <i class="fas fa-language fa-3x text-success mb-3"></i>
            <h5 class="card-title">Malayalam</h5>
            <p class="card-text">Native Proficiency</p>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-3">
        <div class="card h-100 shadow-sm custom-card">
          <div class="card-body">
             <i class="fas fa-language fa-3x text-info mb-3"></i>
            <h5 class="card-title">Hindi</h5>
            <p class="card-text">Professional Proficiency</p>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-3">
        <div class="card h-100 shadow-sm custom-card">
          <div class="card-body">
             <i class="fas fa-language fa-3x text-warning mb-3"></i>
            <h5 class="card-title">Tamil</h5>
            <p class="card-text">Basic Proficiency</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Publications Section -->
<section id="publications" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Publications & Talks</h2>
    <div class="row row-cols-1 row-cols-md-2 g-4">
      <!-- Publication 1 -->
      <div class="col">
        <div class="card h-100 shadow-sm custom-card publication-card">
          <div class="card-body">
            <div class="d-flex align-items-start mb-3">
              <i class="fas fa-file-alt fa-2x text-primary me-3 mt-1"></i>
              <div>
                <h5 class="card-title mb-1">Free vibration analysis of an aluminum honeycomb sandwich panel filled with CFRP tubes – Numerical study</h5>
                <p class="card-text mb-1"><strong>Journal:</strong> Australian Journal of Mechanical engineering (2020)</p>
                <p class="card-text"><small class="text-muted">Scopus Indexed</small></p>
                <span class="badge bg-info me-1">Mechanical Engineering</span>
                <span class="badge bg-secondary">Numerical Analysis</span>
              </div>
            </div>
            <p class="card-text">This paper explores vibration characteristics of composite sandwich panels with carbon fiber reinforced polymer tubes.</p>
          </div>
        </div>
      </div>

      <!-- Publication 2 -->
      <div class="col">
        <div class="card h-100 shadow-sm custom-card publication-card">
          <div class="card-body">
            <div class="d-flex align-items-start mb-3">
              <i class="fas fa-file-alt fa-2x text-primary me-3 mt-1"></i>
              <div>
                <h5 class="card-title mb-1">Machine learning classification for tool wear modeling: A comparative study</h5>
                <p class="card-text mb-1"><strong>Conference:</strong> International Conference on Applications in Computational Engineering & Sciences (IConACES 2020)</p>
                <p class="card-text"><small class="text-muted">ISBN: 978-93-92811-00-5</small></p>
                <span class="badge bg-warning me-1">Machine Learning</span>
                <span class="badge bg-danger">Tool Wear Analysis</span>
              </div>
            </div>
            <p class="card-text">A comparative study of machine learning models for predicting tool wear in manufacturing processes.</p>
          </div>
        </div>
      </div>

      <!-- Talk -->
      <div class="col">
        <div class="card h-100 shadow-sm custom-card publication-card">
          <div class="card-body">
            <div class="d-flex align-items-start mb-3">
              <i class="fas fa-microphone-alt fa-2x text-success me-3 mt-1"></i>
              <div>
                <h5 class="card-title mb-1">AWS Healthlake Webinar</h5>
                <p class="card-text mb-1"><strong>Role:</strong> Technical Speaker</p>
                <span class="badge bg-primary me-1">AWS</span>
                <span class="badge bg-info">Healthcare</span>
                <span class="badge bg-secondary">Data Analytics</span>
              </div>
            </div>
            <p class="card-text">Presented technical insights on using AWS HealthLake for healthcare data analytics and machine learning applications.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-4">Get In Touch</h2>
    <p class="text-center text-muted mb-4">Feel free to reach out for collaborations or inquiries.</p>
    <div class="text-center">
      <a href="mailto:nijinxose@gmail.com" class="btn btn-primary me-2">
        <i class="fas fa-envelope me-2"></i>Email Me
      </a>
      <a href="https://linkedin.com/in/nijinjose" target="_blank" class="btn btn-info me-2">
        <i class="fab fa-linkedin me-2"></i>LinkedIn
      </a>
      <a href="https://github.com/nijinjose" target="_blank" class="btn btn-dark">
        <i class="fab fa-github me-2"></i>GitHub
      </a>
    </div>
  </div>
</section>
