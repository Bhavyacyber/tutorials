# Cybersecurity Foundations

A beginner-friendly, static tutorial site for cybersecurity foundations, application security, product security, and AI application security.

## Learning paths

- [Networking](networking.html): TCP/IP, DNS, HTTP, TLS, routing, and firewalls.
- [Operating systems](operating-systems.html): Linux, Windows, macOS, processes, services, permissions, authentication, and logs.
- [Security](security.html): the CIA triad, threats, vulnerabilities, risk, cryptography, IAM, security controls, and threat modeling.
- [Application security](application-security.html): web architecture, HTTP, REST, APIs, identity, OWASP risks, and safe security testing with common tools.
- [Product security](product-security.html): security across the product lifecycle, from requirements and design to deployment, monitoring, and vulnerability management.
- [AI application security](ai-application-security.html): LLM, RAG, agent, and AI infrastructure risks, with AI red teaming and security engineering practices.
- [Standards and compliance](compliance.html): practical guidance on NIST, ISO, SOC 2, PCI DSS, GDPR, AI governance, and threat frameworks for security engineers.

Start at [index.html](index.html). The lessons include safe exercises intended for systems you own or are authorized to use.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the site to GitHub Pages whenever changes are pushed to `main`, or when the workflow is run manually.

To publish it, push this repository to GitHub, then open **Settings → Pages** and select **GitHub Actions** as the build and deployment source if it is not already selected. The workflow run will publish the site; its deployment job shows the live URL.

## Preview locally

Open `index.html` in a browser, or serve this folder with any static file server. No build step or package installation is required.
