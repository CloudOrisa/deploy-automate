# Deploy Automate

## Description
This project is a static website deployed to **AWS S3** and distributed via **CloudFront CDN**.  
It includes **automation with GitHub Actions** to sync changes to S3 and invalidate the CloudFront cache automatically whenever changes are pushed to GitHub.

## Features
- Fully automated deployment to AWS S3
- CloudFront CDN caching with automatic invalidation
- CI/CD using GitHub Actions
- Easy updates by pushing changes to GitHub

## Setup / Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/CloudOrisa/deploy-automate.git
