## Continuous Integration

This project uses GitHub Actions for automated checks.

### Workflow triggers

- Push to main

- Pull requests to main

### Project configuration

- Project: HelloWorkshop

- .NET version: 10.0.x

### Automated checks

- Repository structure check

- .NET restore

- .NET build

- .NET publish

### Build artifacts

The published application is uploaded as a GitHub Actions artifact.

- Name: app-<commit-sha>

- Retention: 7 days

### Results

To view workflow logs and artifacts:

1. Open the GitHub repository.

2. Go to Actions.

3. Select a workflow run.

4. Check logs or download the artifact.
 
