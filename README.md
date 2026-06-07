GitHub Repository Roles Lab

Objective

Understand and validate GitHub repository permission levels through hands-on practice.

Environment

- GitHub Organization: aws-devops-roles-lab
- Repository: github-roles-lab
- Test User: Petr7077

Tasks Performed

1. Organization Setup

- Created GitHub Organization
- Created repository inside the organization
- Invited additional member account

2. Write Role Validation

Assigned Write permission to a test user and verified:

- Create branch
- Modify repository files
- Commit changes
- Push changes
- Create Pull Request
- Merge Pull Request

Evidence:

- Created branch: "feature/test-write-role"
- Updated "README.md"
- Created Pull Request
- Successfully merged changes into "main"

3. Read Role Validation

Changed user permission from Write to Read and verified:

- Unable to create branches
- Unable to edit repository files
- Unable to commit changes
- Unable to push changes
- GitHub required repository fork before proposing changes

Observed GitHub message:

«You need to fork this repository to propose changes.»

Permission Comparison

Action| Read| Write
View repository| Yes| Yes
Create branch| No| Yes
Edit files| No| Yes
Commit changes| No| Yes
Push changes| No| Yes
Create Pull Request from repository branch| No| Yes
Merge Pull Request*| No| Yes

* Without Branch Protection Rules.

Skills Demonstrated

- GitHub Organizations
- Repository Access Management
- Collaborator Permissions
- Read vs Write Access
- Pull Requests
- Branching Workflow
- Repository Administration

Key Learning

The minimum GitHub repository permission required for code contribution is Write. Users with Read access can view code but cannot directly modify repository content.
