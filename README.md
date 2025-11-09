# Multi-Platform Matrix Build Demo

This repository demonstrates GitHub Actions matrix builds with artifact management.

## Contact
Email: your.email@example.com

## Workflow Features
- Matrix builds across multiple OS platforms (Ubuntu, macOS, Windows)
- Multiple Node.js versions (18, 20)
- 6 parallel build jobs
- Artifact upload for each build variant

## Build Artifacts
Each build generates an artifact with the naming pattern:
`build-594f6f9-{platform}-node{version}`

## View Results
Check the [Actions tab](../../actions) to see workflow runs and download artifacts.
