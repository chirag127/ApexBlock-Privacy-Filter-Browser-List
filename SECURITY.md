# Security Policy

The security of the ApexBlock Privacy Filter is a top priority. Given our frontend-only architecture, our security model is focused on protecting the user within the browser environment.

## Frontend-Only Architecture

-   **No Server-Side Components:** This application runs entirely on the client-side. There is no backend server, and we do not host any of your data.
-   **User-Managed API Keys:** API keys for AI providers are provided by you and stored exclusively in your browser's `LocalStorage`. These keys are never transmitted to any server other than the respective AI provider's API endpoint. You are in full control of your keys.

## Reporting a Vulnerability

We encourage the responsible disclosure of security vulnerabilities. If you discover a security issue, please report it to us privately.

1.  **DO NOT** create a public GitHub issue.
2.  Email the details of the vulnerability to `<PROJECT-SECURITY-EMAIL>` (note: this is a placeholder and should be updated).
3.  Please include the following in your report:
    -   A clear and descriptive title.
    -   A detailed description of the vulnerability.
    -   Steps to reproduce the vulnerability.
    -   Any proof-of-concept code, screenshots, or screen recordings.

We will acknowledge your email within 48 hours and will work with you to address the issue promptly.

## Supported Versions

Security updates are only provided for the latest stable version of the application.

## Scope

The following are examples of vulnerabilities that are within the scope of our security policy:

-   Cross-Site Scripting (XSS)
-   Insecure storage or handling of API keys in the browser
-   Data leakage to third-party services without user consent

Issues that are not considered vulnerabilities include:

-   Social engineering attacks
-   Vulnerabilities in the underlying AI provider APIs
-   Security issues related to the user's own browser or operating system

Thank you for helping to keep ApexBlock secure.
