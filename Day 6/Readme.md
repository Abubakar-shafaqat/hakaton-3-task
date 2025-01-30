# Marketplace Deployment Preparation - Day 6

## Objective
Prepare the marketplace for production by setting up a **staging environment**, configuring hosting platforms, and ensuring the application is functional, secure, and reliable before going live.

---

## Steps Overview

### 1. Hosting Platform Setup
- **Platform Choice:**  
  Used **Vercel** for deployment (fast and user-friendly) and **GitHub** for version control.  
  Future scalability options include AWS or Azure.

- **Repository Connection:**  
  - Connected GitHub repo to Vercel for automatic deployments.
  - Configured build settings and added necessary scripts for smooth operation.

---

### 2. Configure Environment Variables
- **Local Setup:**  
  Created a `.env` file to include sensitive data like API keys and tokens.  

- **Hosting Setup:**  
  Uploaded environment variables securely through the Vercel dashboard.

---

### 3. Deploy to Staging
- **Application Deployment:**  
  - Logged into Vercel and selected the GitHub repository.  
  - Deployed the application to a staging environment via Vercel's build process.

- **Deployment Validation:**  
  - Verified logs to ensure the build completed without errors.  
  - Tested basic functionality on the staging URL:
    - Confirmed all pages loaded correctly.
    - Verified key features like user login, product listings, and search functionality.
    - Ensured no broken links or missing assets.

---

### 4. Staging Environment Testing
- **Testing Conducted:**  
  - Functional Testing  
  - Security Testing  
  - API Testing  

- **Test Case Reporting:**  
  [Test Case Report - Day 5 CSV](https://github.com/Abubakar-shafaqat/hakaton-3-task/blob/main/csv%20test%20report/abubakar%20Test-case%20Report%20%20day-5.csv)

- **Performance Testing:**  
  Ongoing as part of staging validation.

---

## Conclusion
The staging environment is set up successfully, and the application has been deployed to Vercel. Key features have been tested and validated for smooth functionality. The app is now ready for further testing and final deployment.
