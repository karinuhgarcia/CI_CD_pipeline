# Full-Stack Application with CI/CD Pipeline

This application demonstrates a complete CI/CD pipeline using GitHub Actions, with:
- Automated testing on PRs to `develop`
- Automated deployment to Render on merges to `main`

## Features
- React frontend
- Express backend
- MongoDB database
- Cypress component tests
- GitHub Actions CI/CD

## Development Workflow
1. Create feature branches from `develop`
2. Make changes and push to feature branch
3. Create PR to `develop` (triggers tests)
4. After tests pass, merge to `develop`
5. When ready, create PR from `develop` to `main` (triggers deployment)

## Live Application
[View deployed application](https://ci-cd-pipeline-o0k8.onrender.com)

## Screenshots
![GitHub Actions Tests](images/tests.png)
![GitHub Actions Deployment](images/deployment.png)