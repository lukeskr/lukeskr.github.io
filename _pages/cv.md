---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-page">
  <div class="cv-intro">
    <p>Mixed reality researcher and software engineer working across immersive interfaces, real-time systems, computer vision and applied research.</p>
    <div class="cv-actions">
      <a href="mailto:lucchas.ribeiroskreinig@gmail.com">Email</a>
      <a href="{{ site.author.linkedin | prepend: 'https://www.linkedin.com/in/' }}">LinkedIn</a>
      <a href="{{ site.author.googlescholar }}">Google Scholar</a>
      <button type="button" onclick="window.print()">Print CV</button>
    </div>
  </div>

  <section class="cv-section">
    <h2>Education</h2>
    <div class="cv-timeline">
      <article class="cv-item">
        <div class="cv-date">2022 - 2027<small>expected</small></div>
        <div class="cv-details">
          <h3>Ph.D. in Computer Science</h3>
          <p class="cv-org">Graz University of Technology · Institute of Visual Computing</p>
          <p>Research focus: developing mixed reality instructional applications.</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2019 - 2022</div>
        <div class="cv-details">
          <h3>M.Sc. in Computer Science</h3>
          <p class="cv-org">Graz University of Technology · Institute of Computer Graphics and Vision</p>
          <p>Visual Computing major · Interactive and Visual Information Systems minor · Passed with distinction.</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2014 - 2019</div>
        <div class="cv-details">
          <h3>B.Sc. in Computer Science</h3>
          <p class="cv-org">Graz University of Technology · Institute of Computer Graphics and Knowledge Visualisation</p>
        </div>
      </article>
    </div>
  </section>

  <section class="cv-section">
    <h2>Experience</h2>
    <div class="cv-timeline">
      <article class="cv-item">
        <div class="cv-date">2022 - 2026</div>
        <div class="cv-details">
          <h3>Research Assistant</h3>
          <p class="cv-org">Graz University of Technology · Graz, Austria</p>
          <p>Software engineering and applied research.</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2021 - 2022</div>
        <div class="cv-details">
          <h3>Student Project Assistant</h3>
          <p class="cv-org">Graz University of Technology · Graz, Austria</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2019 - 2022</div>
        <div class="cv-details">
          <h3>Software Engineer</h3>
          <p class="cv-org">Andritz AG (via Altech GmbH) · Graz, Austria</p>
        </div>
      </article>
    </div>
  </section>

  <section class="cv-section">
    <h2>Skills</h2>
    <div class="cv-skills">
      <div class="cv-skill-group">
        <h3>Programming</h3>
        <span>C#</span><span>Python</span><span>C++</span><span>Java</span><span>SQL</span>
      </div>
      <div class="cv-skill-group">
        <h3>Software Engineering</h3>
        <span>Object-oriented design</span><span>State machines</span><span>Multithreading</span><span>REST APIs</span><span>Git</span>
      </div>
      <div class="cv-skill-group">
        <h3>Computer Vision &amp; AI</h3>
        <span>OpenCV</span><span>Camera calibration</span><span>Pose estimation</span><span>Object tracking</span><span>Machine learning</span><span>LLM integration</span>
      </div>
      <div class="cv-skill-group">
        <h3>Interactive Systems</h3>
        <span>Unity</span><span>Augmented reality</span><span>Virtual reality</span><span>Real-time rendering</span><span>Standalone HMDs</span>
      </div>
      <div class="cv-skill-group">
        <h3>Infrastructure &amp; Tools</h3>
        <span>MSSQL</span><span>Talend</span><span>ActiveMQ</span><span>Docker</span><span>Linux</span><span>Visual Studio</span>
      </div>
    </div>
  </section>

  <section class="cv-section">
    <h2>Selected Publications</h2>
    <div class="cv-publications">
      {% assign cv_publications = site.publications | sort: "date" | reverse %}
      {% for post in cv_publications %}
        <article>
          <a href="{{ post.link }}">{{ post.title }}</a>
          <span>{{ post.venue }} · {{ post.date | date: "%Y" }}</span>
        </article>
      {% endfor %}
    </div>
  </section>

  <section class="cv-section">
    <h2>Teaching &amp; Leadership</h2>
    <div class="cv-timeline cv-timeline--compact">
      <article class="cv-item">
        <div class="cv-date">2026</div>
        <div class="cv-details">
          <h3>AR/VR Training Program</h3>
          <p class="cv-org">Teaching Team · Western Pacific University, Ialibu, Papua New Guinea</p>
          <p>Five-day professional development program for academic staff, supported by an AAPNG-funded Stream 2 Capacity Development initiative.</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2026</div>
        <div class="cv-details">
          <h3>Graduate Student Advisor</h3>
          <p>Immersive tutorial authoring for a standalone head-mounted display.</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2024</div>
        <div class="cv-details">
          <h3>Undergraduate Student Advisor</h3>
          <p>Procedural AR piano instruction for Magic Leap 2 and a desktop teacher interface.</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2023 - 2024</div>
        <div class="cv-details">
          <h3>Teaching Assistant · Augmented Reality</h3>
          <p class="cv-org">Graz University of Technology</p>
          <p>Lecture content, lectures, examinations, grading and practical exercises.</p>
        </div>
      </article>
      <article class="cv-item">
        <div class="cv-date">2018</div>
        <div class="cv-details">
          <h3>Student Teaching Assistant · Computer Graphics</h3>
          <p class="cv-org">Graz University of Technology</p>
        </div>
      </article>
    </div>
  </section>

  <section class="cv-section">
    <h2>Service &amp; Review</h2>
    <div class="cv-service">
      <article>
        <h3>Peer review</h3>
        <p>TVCG · VRST · UIST · ISMAR / ISMAR-Adjunct · IEEE VR · SIGGRAPH Asia</p>
      </article>
      <article>
        <h3>Volunteer service</h3>
        <p>OzCHI 2026 student volunteer · Lebenshilfe Österreich, 2018-2019</p>
      </article>
    </div>
  </section>
</div>
