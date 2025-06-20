---
layout: default
title: About
permalink: /about/
---

<div class="hero-section">
  <div class="container">
    <div class="hero-content">
      <div class="skill-badge">CLOUD ENGINEERING • DEVOPS • AUTOMATION</div>
      
      <h1 class="hero-title">
        I can help your business to<br>
        <span class="gradient-text">Scale in the cloud</span> <span class="gradient-text-pink">and grow fast</span>
      </h1>
      
      <div class="hero-buttons">
        <a href="#resume" class="btn btn-primary">Resume</a>
        <a href="#projects" class="btn btn-secondary">Projects</a>
      </div>
    </div>
    
    <div class="hero-image">
      <div class="profile-container">
        <!-- Replace with your professional photo -->
        <img src="/assets/images/your-photo.jpg" alt="Your Name" class="profile-image">
        <div class="gradient-bg"></div>
      </div>
    </div>
  </div>
</div>

<section id="about" class="about-section">
  <div class="container">
    <h2>About Me</h2>
    <p>I'm a passionate Cloud Engineer with expertise in designing, implementing, and managing scalable cloud infrastructure solutions. I help businesses migrate to the cloud, optimize costs, and improve reliability.</p>
    
    <div class="skills-grid">
      <div class="skill-category">
        <h3>Cloud Platforms</h3>
        <ul>
          <li>Amazon Web Services (AWS)</li>
          <li>Microsoft Azure</li>
          <li>Google Cloud Platform</li>
        </ul>
      </div>
      
      <div class="skill-category">
        <h3>Infrastructure as Code</h3>
        <ul>
          <li>Terraform</li>
          <li>AWS CloudFormation</li>
          <li>Azure Resource Manager</li>
        </ul>
      </div>
      
      <div class="skill-category">
        <h3>DevOps & Automation</h3>
        <ul>
          <li>Docker & Kubernetes</li>
          <li>Jenkins, GitHub Actions</li>
          <li>Ansible, Chef</li>
        </ul>
      </div>
      
      <div class="skill-category">
        <h3>Monitoring & Security</h3>
        <ul>
          <li>CloudWatch, Prometheus</li>
          <li>AWS Security Hub</li>
          <li>Infrastructure Monitoring</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="resume" class="resume-section">
  <div class="container">
    <h2>Experience</h2>
    
    <div class="experience-item">
      <h3>Cloud Engineer</h3>
      <p class="company">Your Company • 2023 - Present</p>
      <ul>
        <li>Designed and implemented cloud infrastructure for 50+ applications</li>
        <li>Reduced infrastructure costs by 30% through optimization strategies</li>
        <li>Led migration of legacy systems to cloud-native solutions</li>
      </ul>
    </div>
    
    <div class="experience-item">
      <h3>DevOps Engineer</h3>
      <p class="company">Previous Company • 2021 - 2023</p>
      <ul>
        <li>Implemented CI/CD pipelines reducing deployment time by 70%</li>
        <li>Managed container orchestration with Kubernetes</li>
        <li>Automated infrastructure provisioning with Terraform</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects" class="projects-section">
  <div class="container">
    <h2>Featured Projects</h2>
    
    <div class="projects-grid">
      <div class="project-card">
        <h3>Multi-Tier Web Application</h3>
        <p>Built scalable web application on AWS with auto-scaling, load balancing, and RDS database.</p>
        <div class="project-tech">
          <span>AWS</span> <span>Terraform</span> <span>Docker</span>
        </div>
        <a href="#" class="project-link">View Project →</a>
      </div>
      
      <div class="project-card">
        <h3>CI/CD Pipeline Automation</h3>
        <p>Implemented complete DevOps pipeline with automated testing, security scanning, and deployment.</p>
        <div class="project-tech">
          <span>Jenkins</span> <span>Docker</span> <span>Kubernetes</span>
        </div>
        <a href="#" class="project-link">View Project →</a>
      </div>
      
      <div class="project-card">
        <h3>Infrastructure as Code</h3>
        <p>Created reusable Terraform modules for rapid cloud infrastructure deployment.</p>
        <div class="project-tech">
          <span>Terraform</span> <span>AWS</span> <span>CloudFormation</span>
        </div>
        <a href="#" class="project-link">View Project →</a>
      </div>
    </div>
  </div>
</section>

<style>
/* Custom CSS to match the design */
.hero-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  min-height: 80vh;
  display: flex;
  align-items: center;
  color: white;
  padding: 4rem 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: center;
  gap: 4rem;
}

.hero-content {
  flex: 1;
}

.skill-badge {
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(10px);
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 600;
  margin-bottom: 2rem;
  display: inline-block;
}

.hero-title {
  font-size: 3.5rem;
  font-weight: 700;
  line-height: 1.2;
  margin-bottom: 2rem;
}

.gradient-text {
  background: linear-gradient(45deg, #667eea, #764ba2);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.gradient-text-pink {
  background: linear-gradient(45deg, #f093fb, #f5576c);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-buttons {
  display: flex;
  gap: 1rem;
  margin-top: 2rem;
}

.btn {
  padding: 1rem 2rem;
  font-size: 1.1rem;
  font-weight: 600;
  text-decoration: none;
  border-radius: 8px;
  transition: all 0.3s ease;
}

.btn-primary {
  background: #6c5ce7;
  color: white;
  border: none;
}

.btn-secondary {
  background: transparent;
  color: white;
  border: 2px solid white;
}

.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

.hero-image {
  flex: 1;
  position: relative;
}

.profile-container {
  position: relative;
  width: 300px;
  height: 300px;
}

.profile-image {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  object-fit: cover;
  position: relative;
  z-index: 2;
}

.gradient-bg {
  position: absolute;
  top: -20px;
  left: -20px;
  right: -20px;
  bottom: -20px;
  background: linear-gradient(45deg, #667eea, #764ba2, #f093fb);
  border-radius: 50%;
  z-index: 1;
}

.about-section, .resume-section, .projects-section {
  padding: 4rem 0;
}

.skills-grid, .projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.skill-category, .project-card {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.project-tech {
  margin: 1rem 0;
}

.project-tech span {
  background: #6c5ce7;
  color: white;
  padding: 0.3rem 0.8rem;
  border-radius: 20px;
  font-size: 0.8rem;
  margin-right: 0.5rem;
}

.project-link {
  color: #6c5ce7;
  text-decoration: none;
  font-weight: 600;
}

@media (max-width: 768px) {
  .container {
    flex-direction: column;
    text-align: center;
  }
  
  .hero-title {
    font-size: 2.5rem;
  }
  
  .hero-buttons {
    justify-content: center;
  }
}
</style>
