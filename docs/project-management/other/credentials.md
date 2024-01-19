status: new

# Credentials

## Overview

Effective management of credentials, including access to various services and platforms, is vital for the security and efficiency of our projects. This guide outlines the process for storing credentials and the expected cooperation from clients regarding access permissions.

### Credential File Creation

For each project, create a `.txt` file named "ProjectName - Credentials" in the directory: _Projects -> Client -> Materials -> Secrets_.

### File Structure and Contents

Each credential entry must include:

1. **Service Name**: The name in uppercase.
2. **Link**: Direct link to the service or application.
3. **Credentials**: Username/email/phone and password.
4. **Additional Details**: Any extra information needed for access, like security questions or PINs.

### Example Entry Format

```plaintext title="ProjectName - Credentials.txt"
SERVICE NAME
- Link: [Service URL]
- Username: [Username]
- Password: [Password]
- Additional Info: [Any extra details]
```

## Essential Services List

For each project, ensure to include credentials for the following services:

1. **Cloud Hosting Services**: AWS, Azure, GCP, etc.
2. **Version Control**: GitHub, GitLab, Bitbucket.
3. **Continuous Integration/Deployment**: Jenkins, Travis CI, CircleCI.
4. **Project Management Tools**: Linear, Jira, Trello, Asana.
5. **Database Services**: MySQL, PostgreSQL, MongoDB.
6. **Third-Party APIs**: Any external services used by the project.
7. **App Store Accounts**: Google Play Store, Apple App Store.
8. **Domain Registrar and Hosting Services**: For managing web domains.
9. **Email Service Providers**: Especially for applications that send emails.
10. **SSH Credentials**: For secure shell access.

## Storing Testing Credentials for App Stores

### Android App Testing Credentials

- **App Link**: Direct link to the Google Play Store listing for testing.
- **Testing Access Details**: 
    - Username/email for tester access
    - Password

### iOS App Testing Credentials

- **App Link**: Direct link to the Apple App Store listing for testing.
- **Testing Access Details**: 
    - Username/email for tester access
    - Password

### Example for App Store Testing Credentials

```plaintext title="ProjectName - Credentials.txt"
ANDROID APP TESTING
- App Link: [https://play.google.com/store/apps/details?id=com.example.testapp]
- Username: testuser@example.com
- Password: TestPassword123!

IOS APP TESTING
- App Link: [https://apps.apple.com/app/id123456789]
- Username: iosuser@example.com
- Password: iOSpass456!
```

## SSH Testing Credentials

- **SSH Command**: Full SSH command for accessing testing environments.
- **Key Location**: Path to the SSH key file used for authentication.

### Example SSH Testing Credential

```plaintext title="ProjectName - Credentials.txt"
SSH TESTING CREDENTIALS
- SSH Command: ssh testuser@192.168.1.2 -i /path/to/testuser-key
- Key File: /path/to/testuser-key
```

## Client Collaboration in Access Management

- **Client Invitations**: Request clients to invite you to their platforms/services with appropriate user permissions.
- **Security Assurance**: This approach ensures that the client maintains control over their services while granting necessary access to the project team.
- **Roles and Permissions**: Clearly define the roles and permissions needed for each service.

## Security Guidelines

- **Confidentiality**: These files are confidential and should not be shared outside of the project team.
- **Regular Updates**: Update the credentials file whenever there is a change.
- **Backup**: Keep a secure backup of these files.
- **Encryption**: Consider encrypting the file if it contains highly sensitive information.

## Best Practices

- **Confidentiality**: Treat all files as confidential, restricted to project team members.
- **Regular Updates and Audits**: Update and audit credentials periodically.
- **Backup and Recovery Plan**: Implement a robust backup strategy.
- **Encryption and Security**: Encrypt files and use secure channels for sharing.
- **Access Control**: Restrict file access based on role and necessity.
- **Strong Password Policies**: Enforce strong, unique passwords for each service.
- **Two-Factor Authentication**: Where possible, enable 2FA for additional security.
- **Documentation and Training**: Regularly update the guide and train team members on best practices.