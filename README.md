# Shifting Security Left: DevSecOps Workshop

Welcome to the "Shifting Security Left" repository, a recreation of a workshop I participated in at BSides Tampa 2024. This repository demonstrates the importance and implementation of DevSecOps practices. It showcases various workflows and tools used to enhance the security of the software development lifecycle by integrating security early into the process.

## Overview

This repository contains several workflows and tools used to scan for secrets, manage them securely, and perform static analysis to detect vulnerabilities. The main focus of this project is to demonstrate the concept of "shifting security left," which involves integrating security measures early in the software development lifecycle to identify and mitigate risks as soon as possible.

## Why Shift Security Left?

Shifting security left means incorporating security practices early in the development process rather than addressing them at the end. This approach offers several benefits:
- **Early Detection and Mitigation**: Identifying vulnerabilities and security issues early in the development process reduces the cost and effort required to fix them.
- **Improved Security Posture**: Continuously integrating security tools helps maintain a robust security posture, reducing the risk of breaches and vulnerabilities in production.
- **Faster Delivery**: Integrating security into the CI/CD pipeline allows for automated checks, leading to faster and more secure software delivery.

## Implemented Workflows and Tools

### 1. Secret Scanning
- **TruffleHog and Custom Pattern Scan**: These tools are used to scan the repository for secrets, such as API keys and passwords, to prevent accidental exposure.
  - ![Secret Scanning Workflows](https://i.allthepics.net/2024/05/19/2Secret-scanning.png)
  - ![TruffleHog Scan](https://i.allthepics.net/2024/05/19/3-secret-scan-trufflehog.md.png)

### 2. Using Secrets Securely
- **GitHub Secrets Management**: This demonstrates how to securely manage and use secrets in GitHub Actions workflows.
  - ![Example Using Secrets Workflow](https://i.allthepics.net/2024/05/19/4a-Using-secrets.png)
  - ![Secrets Workflow Run](https://i.allthepics.net/2024/05/19/5-using-secrets.png)

### 3. Tartufo Secret Scanning
- **Tartufo**: This tool scans the repository for secrets and sensitive information, providing an additional layer of security.
  - ![Tartufo Workflow](https://i.allthepics.net/2024/05/19/6-Tatufro.png)
  - ![Tartufo Scan Results](https://i.allthepics.net/2024/05/19/7-Tatufro.png)

### 4. Horusec Security Scan
- **Horusec**: This tool performs static analysis and scans the codebase for vulnerabilities, ensuring code security.
  - ![Horusec Workflow](https://i.allthepics.net/2024/05/19/8-Horusec.png)
  - ![Horusec Scan Results](https://i.allthepics.net/2024/05/19/9-Horusec.png)

### 5. CodeQL Analysis
- **CodeQL**: This tool identifies vulnerabilities and coding errors in the codebase, providing detailed analysis and recommendations.
  - ![CodeQL Analysis Workflow](https://i.allthepics.net/2024/05/19/11-Security-Tab.png)
  - ![Branch Protection Rules](https://i.allthepics.net/2024/05/19/12-Branch-Protection-rules.png)

## Software Bill of Materials (SBOM)

The SBOM provides a detailed inventory of the components used in the project, ensuring transparency and aiding in vulnerability management.

- [SBOM File](https://github.com/alexmalooley/Shifting-security-Left/blob/main/SBOMShifting-security-Left_alexmalooley_494c99c0a2a790cece3e65ecff04dda61a05952b.json)

## Conclusion

By incorporating these security practices and tools into your development workflow, you can significantly enhance the security and quality of your software. This project demonstrates the practical application of DevSecOps principles and the benefits of shifting security left.

Feel free to explore the repository and the workflows to understand how these tools are integrated and used. If you have any questions or feedback, please open an issue or reach out to the repository maintainer.

Happy coding and stay secure!

