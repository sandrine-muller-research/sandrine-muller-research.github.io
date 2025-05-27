<style>
.profile-card {
  text-align: center;
  width: 150px;
  cursor: pointer;
  margin-bottom: 1.5em; /* space below each card */
  border: 1px solid transparent;
  padding-bottom: 0.5em;
  transition: border-color 0.3s;
}
.profile-card:hover {
  border-color: #0078d7;
}
.profile-img {
  width: 120px;
  height: 120px;
  object-fit: cover;
  border-radius: 50%;
  border: 3px solid #ccc;
  transition: border-color 0.3s;
}
.profile-img:hover {
  border-color: #0078d7;
}
.profile-name {
  margin-top: 0.5em;
  font-weight: bold;
  font-size: 1.1em;
}
.profile-subheader {
  font-weight: normal;
  font-size: 0.9em;
  color: #555;
  margin-top: 0.2em;
}
.profile-bio {
  display: none; 
  margin-top: 0.8em;
  font-size: 0.9em;
  color: #333;
  border-top: 1px solid #ddd;
  padding-top: 0.5em;
  text-align: left;
}
.profile-card.active .profile-bio {
  display: block; /* show bio when active */
}
</style>

<div class="profile-grid">
  <div class="profile-card" onclick="this.classList.toggle('active')">
    <img class="profile-img" src="/images/sandrine_portrait.png" alt="Sandrine Muller">
    <div class="profile-name">Sandrine Muller, Eng. Msc., PhD</div>
    <div class="profile-subheader">Asst. Prof., Group lead</div>
    <div class="profile-bio">Sandrine Muller is a tenure track assistant professor at the LIGLAB (Informatics Laboratory of Grenoble), Grenoble-Alpes University (UGA). In April 2025, Sandrine joined UGA, hosting one of the top AI French cluster, to pursue her academic career in AI for health. During her academic career, Sandrine specialized in the fields of artificial intelligence (AI) applied to chemoinformatics, genomics, and brain imaging with core component in methodology. Her current interests are on data integration, health use cases, and Bayesian generative modelling. 
    With a PhD in neuroscience, her expertise lies in statistical analysis applied to high-dimensional health data, particularly in small sample size problems.
    Throughout her scientific career, both in academia and the private sector, she has collaborated with renowned institutions such as the Swiss Federal Institute of Technology in Lausanne (EPFL), Harvard Medical School/Massachusetts General Hospital, Duke University, and the Broad Institute of MIT and Harvard.
    Her work encompasses various aspects of health, from chemical biology (gene expression analysis to biomarker discovery), and extends to machine learning domains, including signal processing, Bayesian statistics, predictive analysis, biological networks, and experimental design.</div>
  </div>
  <div class="profile-card" onclick="this.classList.toggle('active')">
    <img class="profile-img" src="person2.jpg" alt="Laurent Torlay">
    <div class="profile-name">Laurent Torlay,  Eng. Msc.</div>
    <div class="profile-subheader">Senior staff scientist</div>
    <div class="profile-bio">...</div>
  </div>
  <!-- Add more profiles as needed -->
</div>

---


<p>
  <a href="https://github.com/sandrine-muller-research/" target="_blank" title="GitHub">
    <img src="https://img.shields.io/badge/-GitHub-black?style=flat&logo=github&logoColor=white" alt="GitHub Profile">
  </a>
  <a href="https://www.linkedin.com/in/sandrine-muller-phd-ba459725/" target="_blank" title="LinkedIn">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn Profile">
  </a>
  <a href="https://bsky.app/profile/sandrine-muller.bsky.social" target="_blank" title="Bluesky">
    <img src="https://img.shields.io/badge/-Bluesky-00A1E4?style=flat&logo=bluesky&logoColor=white" alt="Bluesky Profile">
  </a>
</p>

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
