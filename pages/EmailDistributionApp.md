---
layout: default
title: Email Distribution App
permalink: /pages/EmailDistributionApp/
---
<a href="{{ "/" | absolute_url }}" class="site-title back-link">← Back</a>

## Email Distribution PowerApp
Date Added: April 6, 2025

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
  <img src="/images/screenshots/EmailApp2.png" onclick="openLightbox('/images/screenshots/EmailApp2.png')" />
  <img src="/images/screenshots/EmailApp4.png" onclick="openLightbox('/images/screenshots/EmailApp4.png')" />
  <img src="/images/screenshots/EmailApp1.png" onclick="openLightbox('/images/screenshots/EmailApp1.png')" />
  <img src="/images/screenshots/EmailApp3.png" onclick="openLightbox('/images/screenshots/EmailApp3.png')" />
</div>


<!-- Lightbox container -->
<div id="lightbox" class="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img" src="" />
</div>

<img id="emailAppImage" class="fade-image" src="/images/screenshots/EmailApp1.png" style="display: block; margin: 20px auto;" />

<script>
  document.addEventListener("DOMContentLoaded", function () {
    startImageFader("emailAppImage", [
      "/images/screenshots/EmailApp1.png",
      "/images/screenshots/EmailApp2.png",
      "/images/screenshots/EmailApp3.png",
      "/images/screenshots/EmailApp4.png"
    ]);
  });
</script>


<!--<div class="video-wrapper">
  <iframe src="https://www.youtube.com/embed/Db7V9Un1En0" frameborder="0" allowfullscreen></iframe>
</div>-->

**VIDEO WALKTHROUGH COMING SOON**

**Project description:** 

The **Email Distribution PowerApp** was developed to meet the following business requirements:
* Quickly access and update Points of Contact (POCs)—both internal and external—associated with specific accounts, namely Healthcare Facilities (HCFs).
* Send reports (as attachments) to HCF POCs with automated email content based on the type of report.
* Track which reports have already been sent.

To meet these needs, the app includes the following features:

**Points of Contact Screen**
* View POCs associated with each HCF by category.
* Unassign POCs from accounts in bulk—useful for managing staffing changes or portfolio reassignments.

**Monthly Report Distribution Screen**
* Filter existing HCF accounts to locate target recipients.
* Automatically generate email language using user-defined inputs (e.g., account name, report type, reporting period).
* Maintain a searchable log of sent reports to help staff track which HCFs have received them.

**Quality Assurance Features**
* Review and edit email content directly in the app or via copy-paste from external sources.
* Send a test email to yourself to verify the content and attachment accuracy.
* Require verification of email accuracy before the official report is sent.

This two-screen PowerApp empowers end-users to ensure quality assurance in report distribution, maintain accurate contact information, and efficiently track communication history with both internal and external contacts.

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
