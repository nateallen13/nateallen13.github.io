## Projects


---

### PowerApps Projects
{% if false %}
[Team Resources/Onboarding App](/pages/TeamResourcesApp) 
{% endif %}
<div class="project-row">
  <a href="/pages/TeamResourcesApp" class="project-link">
    Team Resources/Onboarding App
  </a>
  <span class="project-date">
    Updated March 26, 2025
  </span>
</div>

 <a href="/pages/TeamResourcesApp">
 <img src="images/screenshots/ThumbnailResourceApp.png?raw=true"/>
</a>

{% if false %}
[Email Distribution App](/pages/EmailDistributionApp) 
{% endif %}
<div class="project-row">
  <a href="/pages/EmailDistributionApp" class="project-link">
    Email Distribution App
  </a>
  <span class="project-date">
    Updated April 6, 2025
  </span>
</div>

<a href="/pages/EmailDistributionApp">
  <img id="emailAppImage" src="/images/screenshots/OnboardingApp.png" style="max-width: 100%; height: auto;" />
</a>

<script>
  const images = [
    "/images/screenshots/OnboardingApp.png",
    "/images/screenshots/ThumbnailResourceApp.png"
  ];
  let index = 0;

  setInterval(() => {
    index = (index + 1) % images.length;
    document.getElementById("emailAppImage").src = images[index];
  }, 5000);
</script>

Stay put...more projects are coming soon!

{% if false %}
---
[Project 2 Title](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>


---
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
{% endif %}
<!-- Remove above link if you don't want to attibute -->
