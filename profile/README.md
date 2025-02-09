# CS1821 2025 Group R04

## Members
- Charlie Kingsland - [@ChopsKingsland](www.github.com/ChopsKingsland)
- James O'Mahoney - [@Hairlesscat7406](www.github.com/Hairlesscat7406)
- Yassine Makni - [@Yassine-Makni](www.github.com/Yassine-Makni)
- David Dodica - [@its-me-dav](www.github.com/its-me-dav)

## Setting up Java for the EV3
- Download and Install Java 1.7 (also known as Java 7)
- Download and Install Java 11 to 17
- Download and Install Eclipse 2024-06 (or older)
- Download and Extract Lejos to a memorable location
- Open Eclipse
  - Lejos setup
    - Go to Help > Eclipse Marketplace
    - Install Lejos EV3 plugin
    - Go to Settings > EV3 and set the path to where you saved Lejos
  - Java config
    - In Eclipse settings, add and set Java 1.7 as the default JVM
    - Change the compliance level to 1.7
    - ... tbc

## Using git
### 0. Install and configure git on local machine

### 1. Initial setup
- `git clone https://github.com/CS1821-2025-R04/Milestone3.git`
- `cd Milestone3`

### 2. Prepare feature branch
- `git checkout main` # Start from main
- `git pull origin main` # Get latest changes
- `git checkout -b [branch-name]` # Create feature branch

### 3. Development cycle
*(make code changes here)*
- `git add .`
- `git commit -m "message"`
- `git push origin [branch-name]` # Push to remote

### 4. Create PR to merge code (after pushing)

1. Go to GitHub: https://github.com/[org]/[repo]/pulls
2. Click "New pull request" 
3. Compare: base=main ← compare=[branch-name]
4. Add description & request reviewers

