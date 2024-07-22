# GitHub Actions Learning Syllabus

## Module 1: Introduction to GitHub Actions

#### [1.1 What is GitHub Actions?](./01-Module/1.1-What-is-github-action.md)

- Overview
- Use Cases
- Pricing and Limits

#### [1.2 Understanding Workflows](./01-Module/1.2-Understanding-Workflows.md)

- Workflow Basics
- YAML Syntax
- Workflow Files and Configuration

#### [1.3 Key Concepts](./01-Module/1.3-Key-Concepts.md)

- Jobs
- Steps
- Actions
- Runners

#### [**Project 1:** Create a Simple CI Workflow](./01-Module/1.4-Project-1.md)

- Set up a repository
- Create a basic workflow to run on push events
- Include steps to checkout code, set up a programming environment, and run a simple script or test

## Module 2: Core Concepts and Syntax

#### 2.1 Events

- Types of Events (push, pull_request, schedule, etc.)
- Event Triggers

#### 2.2 Jobs and Steps

- Defining Jobs
- Running Steps Sequentially
- Using Shell Scripts in Steps

#### 2.3 Actions

- Types of Actions (Docker, JavaScript, Composite)
- Using Actions from the Marketplace
- Creating Custom Actions

#### **Project 2:** Multi-Job Workflow

- Create a workflow with multiple jobs running in parallel
- Use different types of actions in each job
- Add conditionals to run specific steps based on outcomes of previous steps

## Module 3: Advanced Workflow Features

#### 3.1 Matrix Builds

- Matrix Strategy Basics
- Dynamic Matrix Configurations

#### 3.2 Caching and Artifacts

- Using Caches for Dependencies
- Storing and Retrieving Artifacts

#### 3.3 Secrets and Environment Variables

- Managing Secrets in Workflows
- Using Environment Variables Securely

#### **Project 3:** Matrix Build Workflow

- Set up a matrix build for multiple environments
- Implement caching to speed up builds
- Store build artifacts for later use

## Module 4: Continuous Integration and Delivery (CI/CD)

#### 4.1 CI Basics

- Setting Up Continuous Integration
- Running Tests Automatically

#### 4.2 CD Basics

- Continuous Delivery vs. Continuous Deployment
- Deployment Strategies

#### 4.3 Integrating with External Services

- Notifications (Slack, Email)
- Deploying to Cloud Providers (AWS, Azure, GCP)

#### **Project 4:** Complete CI/CD Pipeline

- Create a workflow for CI/CD
- Run tests and build on every push
- Deploy to a staging environment
- Notify via Slack on deployment success/failure

## Module 5: Security and Compliance

#### 5.1 Secure Workflows

- Best Practices for Secure Workflows
- Handling Secrets and Sensitive Information

#### 5.2 Compliance

- Audit Logs
- Dependency Scanning and Vulnerability Management

#### 5.3 Code Scanning and Analysis

- Integrating Code Scanning Tools
- Automated Code Quality Checks

#### **Project 5:** Secure and Compliant Workflow

- Set up a secure workflow with proper secret handling
- Implement code scanning and quality checks
- Generate audit logs for workflow runs

## Module 6: Optimizing and Scaling Workflows

#### 6.1 Workflow Optimization

- Reducing Workflow Run Times
- Optimizing Job Execution Order

#### 6.2 Scaling Workflows

- Using Self-Hosted Runners
- Managing Runner Fleets

#### 6.3 Monitoring and Debugging

- Debugging Workflow Failures
- Monitoring Workflow Performance

#### **Project 6:** Optimized and Scalable Workflow

- Optimize an existing workflow to reduce run time
- Set up self-hosted runners for resource-intensive jobs
- Implement monitoring for workflow performance

## Module 7: Advanced Use Cases and Customization

#### 7.1 Custom Actions

- Creating and Publishing Custom Actions
- Best Practices for Reusable Actions

#### 7.2 Advanced CI/CD Pipelines

- Multi-Repository Workflows
- Cross-Project Dependencies

#### 7.3 Integration with Other DevOps Tools

- Terraform and Infrastructure as Code (IaC)
- Kubernetes and Container Orchestration

#### **Project 7:** Custom Action and Advanced CI/CD Pipeline

- Create and publish a custom action
- Implement an advanced CI/CD pipeline with multi-repo dependencies
- Integrate with Terraform for infrastructure deployment

## Final Project: Real-World CI/CD Implementation

- Design and implement a comprehensive CI/CD pipeline for a multi-service application
- Use advanced features like matrix builds, custom actions, and multi-repo workflows
- Ensure security, compliance, and scalability throughout the pipeline
