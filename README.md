# GitHub Copilot Premium Requests - Redirect

This repository serves as a redirect page that automatically forwards visitors to the [GitHub ToolBox](https://jackgkafaty.github.io/GitHub_ToolBox/).

## Purpose

When users visit `https://jackgkafaty.github.io/GitHubCopilot_PremiumRequests/`, they will be automatically redirected to `https://jackgkafaty.github.io/GitHub_ToolBox/`.

## How it works

The redirect is implemented using:
- HTML meta refresh tag for immediate redirection
- JavaScript fallback for additional reliability
- User-friendly fallback link in case automatic redirection fails

## GitHub Pages Setup

To enable this redirect:
1. Ensure GitHub Pages is enabled for this repository
2. Set the source to deploy from the root directory
3. The `index.html` file will serve as the landing page that performs the redirect
