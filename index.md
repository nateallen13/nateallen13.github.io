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

<style>
  #emailAppImage {
    max-width: 100%;
    height: auto;
    transition: opacity 1s ease-in-out;
    opacity: 1;
  }

  .fade-out {
    opacity: 0;
  }
</style>

<a href="/pages/EmailDistributionApp">
  <img id="emailAppImage" src="/images/screenshots/EmailApp1.png" />
</a>

<script>
  const images = [
    "/images/screenshots/EmailApp1.png",
    "/images/screenshots/EmailApp2.png"
  ];
  let index = 0;
  const imageElement = document.getElementById("emailAppImage");

  setInterval(() => {
    // Fade out
    imageElement.classList.add("fade-out");

    setTimeout(() => {
      // Change image source once faded out
      index = (index + 1) % images.length;
      imageElement.src = images[index];

      // Fade back in
      imageElement.classList.remove("fade-out");
    }, 1000); // Match this with CSS transition duration
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
