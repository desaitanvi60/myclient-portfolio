# myclient-portfolio

**1. Set Up AWS S3 Bucket**
Create S3 Bucket: In AWS S3, create a new bucket with a unique name.
Enable Static Website Hosting: Set the index document (e.g., index.html).

**2. Configure IAM User for GitHub Actions**
Create IAM User: In AWS IAM, create a user with Programmatic access.
Attach Policy: Attach AmazonS3FullAccess or a custom policy with S3 permissions.
Save Access Keys: Note down the access key ID and secret access key.

**3. Develop the Portfolio Website**
Create the Website: Develop Harsh Desai’s portfolio using HTML, CSS, and JavaScript.
Initialize Git Repository: Initialize a Git repository and commit the website files

**4. Set Up GitHub Repository and Secrets**
Create GitHub Repository: Create a new repository on GitHub and push the code.
Add Secrets: In GitHub repository settings, add:
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_S3_BUCKET (bucket name)
AWS_REGION (bucket region)

**5. Configure GitHub Actions Workflow**
Create Workflow File: In the repository, create .github/workflows/deploy.yml

**6. Deploy the Website**
Push to GitHub: Commit and push changes to the GitHub repository.
Verify Deployment: Check the S3 bucket and visit the website URL to ensure it’s live
