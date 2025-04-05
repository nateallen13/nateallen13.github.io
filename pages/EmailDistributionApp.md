---
layout: default
title: Email Distribution App
permalink: /pages/EmailDistributionApp/
---
<a href="{{ "/" | absolute_url }}" class="site-title back-link">← Back</a>

## Email Distribution PowerApp
Date Added: April 6, 2025
<img id="emailAppImage" class="fade-image" src="/images/screenshots/EmailApp1.png" style="display: block; margin: 20px auto;" />

<script>
  document.addEventListener("DOMContentLoaded", function () {
    startImageFader("emailAppImage", [
      "/images/screenshots/EmailApp1.png",
      "/images/screenshots/EmailApp2.png"
    ]);
  });
</script>
<script>
  function openLightbox(imageUrl) {
    const lightbox = document.getElementById('lightbox');
    const img = document.getElementById('lightbox-img');
    img.src = imageUrl;
    lightbox.style.display = 'flex';
  }

  function closeLightbox() {
    document.getElementById('lightbox').style.display = 'none';
  }
</script>

<div class="gallery">
  <img src="/images/UserPicture.jpg" onclick="openLightbox('/images/gallery/full1.jpg')" />
  <img src="/images/screenshots/EmailApp2.png" onclick="openLightbox('/images/gallery/full2.jpg')" />
  <img src="/images/screenshots/EmailApp1.png" onclick="openLightbox('/images/gallery/full3.jpg')" />
</div>


<!-- Lightbox container -->
<div id="lightbox" class="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img" src="" />
</div>

<!--<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/Db7V9Un1En0" frameborder="0" allowfullscreen></iframe>
</div>-->
**VIDEO WALKTHROUGH COMING SOON**

**Project description:** 

The Email Distribution PowerApp was built to address the following business requirements:
* Ability to quickly access and update Points of Contact (POC) - both internal external - associated to a specific account...in this case, Healthcare Facilities (HCF).
* Ability to send a report (as an attachment) to the HCF's Points of Contact with automated email language based on the report type.
* Ability to track reports that have already been sent
 
In order to achieve these business requirements, this app was built with the following features:
POINTS OF CONTACT SCREEN
* Quickly review the different POCs associated to each HCF based on a category
* Instantly unassign POCs from accounts in bulk (useful when accounting for internal/external staffing changes or portfolio assignment restructuring).
MONTHLY REPORT DISTRIBUTION SCREEN
* Filtering capabilities of existing HCF accounts
* Pre-populate email language based on user-defined inputs (ex: Account name, Report Type, Reporting Period, etc.)
* Filterable logging of reports for staff to know which reports have already been sent to specific HCFs.
*  Quality assurance measures incorporated:
    * Ability to review email language and make modifications either directly in app or by copy-paste from external text
    * Send Test Email to self to ensure the report email and attachments are correct
    * Verification of email accuracy input required before being able to send offical report email

This two-screen PowerApp delivers substantial power to end-users to ensure QA in the reports being sent, proper tracking of report history, and maintaining accurate Points of Contact internally and externally.

---
This Project Leveraged the Following Programs:
---

<div class="tech-stack">
  <div class="tech-item">
    <img src="/assets/icons/powerapps.svg" alt="Canvas Power App" />  
    <p>Canvas Power App</p>
  </div>
  <div class="tech-item">
    <img src="/assets/icons/sharepoint.png" alt="SharePoint" />
    <p>SharePoint Document Library</p>
  </div>
  <div class="tech-item">
    <img src="/assets/icons/dataverse.svg" alt="Dataverse" />
    <p>Dataverse</p>
  </div>
  <div class="tech-item">
    <img src="/assets/icons/azure.svg" alt="Azure" />
    <p>Azure Security Groups</p>
  </div>
</div>

<style>
  .tech-stack {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    justify-content: center;
  }
  .tech-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 70px; /* Adjust width for compact layout */
    text-align: center;
    font-size: 12px; /* Reduce text size */
  }
  .tech-item img {
    width: 30px; /* Set small icon size */
    height: 30px;
  }
</style>
