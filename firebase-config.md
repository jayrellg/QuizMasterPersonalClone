# Firebase Configuration Documentation

## .firebaserc

This file contains Firebase project configuration and deployment targets.

### Projects
- `default`: "quizmaster-c66a2" - Main development project
- `staging`: "quizmaster-c66a2" - Staging environment (same as default)

### Targets
- `prod`: Production hosting target pointing to "quizmaster-c66a2"
- `testing`: Testing/staging hosting target pointing to "quizmaster-testing-ee900"

### Usage
- Use `firebase use default` for development
- Use `firebase use staging` for staging environment
- Deploy to production: `firebase deploy --only hosting:prod`
- Deploy to testing: `firebase deploy --only hosting:testing` 