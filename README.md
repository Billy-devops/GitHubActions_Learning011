# Complete Runtime Flow
Click Run Workflow
        |
        v
GitHub Actions
        |
        v
Create Ubuntu Runner
        |
        v
Checkout Repository
        |
        v
echo Hello DevOps Insiders
        |
        v
echo Build Started
        |
        v
echo Testing
        |
        v
echo Done
        |
        v
Destroy Runner


# GitHub Actions me 5 cheezein yaad rakh:

Workflow
   |
   Job
   |
   Runner
   |
   Step
   |
   Action / Script

Aur flow:

Trigger
   |
Workflow
   |
Job
   |
Runner (VM)
   |
Checkout Code
   |
Run Commands
   |
Destroy Runner

