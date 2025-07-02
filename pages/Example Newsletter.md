---
title: Example Newsletter
permalink: /example-newsletter/
variant: markdown
description: ""
---
<style>
  .text-kaleido-blue {
    color: #1976C5;
    font-weight: bold;
  }
  .content-wrapper {
    max-width: 1140px;
    margin: 0 auto;
    padding: 0 1rem;
  }
  .issues-container {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem; /* consistent space between items */
  }
  .issue-item {
    flex: 1 1 calc(25% - 2rem); /* 4 items per row, subtract gap */
    min-width: 200px; /* minimum width for smaller screens */
    text-align: left;
  }
  .issue-item img {
    width: 100%;
    height: auto;
    display: block;
  }

  /* Tablet view: 2 items per row */
  @media (max-width: 768px) {
    .issue-item {
      flex: 1 1 calc(50% - 2rem);
    }
  }

  /* Mobile view: 1 item per row */
  @media (max-width: 480px) {
    .issue-item {
      flex: 1 1 100%;
    }
  }
</style>


<div style="background-color: #1976C5; padding: 1rem 0;">
  <div class="content-wrapper">
    <p style="color: white; font-size: 2rem; font-weight: bold; margin: 0;">2025</p>
  </div>
</div>


<section style="background-color: #F7F7F7; padding: 1.25rem 0;">
  <div class="content-wrapper">
    <p style="font-size: 1.2rem; margin-bottom: 1.5rem;" class="text-kaleido-blue">Issue 2</p>
    <a target="_blank" href="https://go.gov.sg/nyps-kldcp-2025-issue1">
      <img style="width: 100%; max-width: 720px; height: auto;" alt="Current Issue Thumbnail" src="/images/2025_Issue_1.png">
    </a>
  </div>
</section>


<section style="background-color: #F7F7F7; padding: 1.25rem 0;">
  <div class="content-wrapper">
    <div class="issues-container">
      <div class="issue-item">
        <a target="_blank" href="/files/kaleidoscope/2025-issue1.pdf">
          <img alt="Issue 1 Thumbnail" src="/images/kaleidoscope/2025-issue1-thumb.jpg">
        </a>
        <p style="margin-top: 0.5rem;" class="text-kaleido-blue">Sample Issue 1</p>
      </div>
      <div class="issue-item">
        <a target="_blank" href="/files/kaleidoscope/2025-issue2.pdf">
          <img alt="Issue 2 Thumbnail" src="/images/kaleidoscope/2025-issue2-thumb.jpg">
        </a>
        <p style="margin-top: 0.5rem;" class="text-kaleido-blue">Sample Issue 2</p>
      </div>
    </div>
  </div>
</section>


<section style="background-color: #1976C5; padding: 1.25rem 0; color: white;">
  <div class="content-wrapper">
    <p style="font-size: 1.2rem; font-weight: bold; margin-bottom: 1rem;">Archived Issues</p>
    <p style="line-height: 1.5; margin: 0;">
      These are static PDF versions of previous Kaleidoscope issues. They do not include interactive elements such as videos or photo albums. For the complete experience, we recommend the current-year editions above.
    </p>
  </div>
</section>


<section style="background-color: #F7F7F7; padding: 1.25rem 0;">
  <div class="content-wrapper">
    <p style="font-size: 1.2rem; margin-bottom: 1.5rem;" class="text-kaleido-blue">2024</p>
    <div class="issues-container">
      <div class="issue-item">
        <a target="_blank" href="/files/kaleidoscope/2024-issue1.pdf">
          <img alt="2024 Issue 1 Thumbnail" src="/images/kaleidoscope/2024-issue1-thumb.jpg">
        </a>
        <p style="margin-top: 0.5rem;" class="text-kaleido-blue">Issue 1</p>
      </div>
      <div class="issue-item">
        <a target="_blank" href="/files/kaleidoscope/2024-issue2.pdf">
          <img alt="2024 Issue 2 Thumbnail" src="/images/kaleidoscope/2024-issue2-thumb.jpg">
        </a>
        <p style="margin-top: 0.5rem;" class="text-kaleido-blue">Issue 2</p>
      </div>
      <div class="issue-item">
        <a target="_blank" href="/files/kaleidoscope/2024-issue3.pdf">
          <img alt="2024 Issue 3 Thumbnail" src="/images/kaleidoscope/2024-issue3-thumb.jpg">
        </a>
        <p style="margin-top: 0.5rem;" class="text-kaleido-blue">Issue 3</p>
      </div>
      <div class="issue-item">
        <a target="_blank" href="/files/kaleidoscope/2024-issue4.pdf">
          <img alt="2024 Issue 4 Thumbnail" src="/images/kaleidoscope/2024-issue4-thumb.jpg">
        </a>
        <p style="margin-top: 0.5rem;" class="text-kaleido-blue">Issue 4</p>
      </div>
    </div>
  </div>
</section>