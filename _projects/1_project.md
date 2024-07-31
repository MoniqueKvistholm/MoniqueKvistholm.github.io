<style>
  body {
    background-color: #E6DED0; /* Background color for the entire page */
    margin: 0;
    padding: 0;
  }
  .custom-container {
    background-color: #E6DED0; /* Background color for the content */
    padding: 20px; /* General padding */
    margin: 0; /* Remove margins */
  }
  .post-title {
    font-weight: bold;
    color: #062A40; /* Color for the title */
    text-align: left; /* Left-align the title */
    font-size: 2.5em; /* Increase font size of the title */
    margin-top: 10px; /* Reduce top margin for the title */
    margin-bottom: 20px;
  }
  .custom-contact-box {
    background-color: #F4F0EB; /* Background color for the contact box */
    border: 1px solid #ddd; /* Border around the contact box */
    border-radius: 5px; /* Rounded corners */
    padding: 10px; /* Reduced padding inside the contact box */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Shadow */
  }
  .custom-contact-box h4.small-header {
    color: #062A40; /* Color for the header in the contact box */
    font-weight: bold;
    font-size: 1em; /* Smaller font size for the header */
    margin-bottom: 10px; /* Reduced bottom margin for the header */
  }
  .custom-contact-box .contact-item {
    margin-bottom: 5px; /* Reduced bottom margin for contact items */
  }
  .custom-contact-box .contact-item strong {
    color: #555; /* Color for strong tags (e.g., 'Name:', 'Email:', etc.) */
    font-size: 0.9em; /* Smaller font size for strong tags */
  }
  .custom-contact-box .contact-item span {
    color: #333; /* Color for span tags (e.g., 'Christian Hinge', email link, etc.) */
    font-size: 0.9em; /* Smaller font size for span tags */
  }
  article {
    font-size: 1.1em;
    line-height: 1.6;
  }
  .figure-column {
    padding-right: 15px; /* Right padding to separate figure from text */
  }

  /* Responsive design */
  @media (max-width: 768px) {
    .post-title {
      font-size: 1.8em; /* Smaller font size for the title on small screens */
    }
    .custom-container {
      padding-left: 10px; /* Reduced side padding for small screens */
      padding-right: 10px; /* Reduced side padding for small screens */
    }
    .figure-column {
      padding-right: 0; /* Remove right padding on small screens */
    }
    .row {
      display: block; /* Stack columns vertically on small screens */
    }
    .col-md-7, .col-md-5 {
      width: 100%; /* Full width for columns on small screens */
      padding: 0; /* Remove padding inside columns on small screens */
    }
  }

  @media (max-width: 480px) {
    .post-title {
      font-size: 1.5em; /* Even smaller font size for the title on extra small screens */
    }
    .custom-contact-box h4.small-header {
      font-size: 0.9em; /* Smaller font size for contact box header */
    }
    article {
      font-size: 1em; /* Slightly smaller font size for article text */
    }
  }
</style>
