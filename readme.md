# Azure Confidential Computing: Verifying Microsoft Azure Attestation JWT tokens

## Description

A few weeks ago I got another excellent question from a community member, who had run into an issue while trying to validate a Confidential Virtual Machine's (CVM) Guest attestation token.

> _"We are using AMD SEV confidential VMs and are trying to validate a guest attestation token, which was signed by Microsoft Azure Attestation. For debugging purposes, we're using JWT.io to perform the validation, but it doesn't seem to work. Any ideas?"_

We managed to identify and fix the issue rather quickly! I figured that there may be other people who will bump into the same issue, so I decided to write down my reasoning in a couple of paragraphs.

## 🔗 Links

- [Azure Confidential Computing: Verifying Microsoft Azure Attestation JWT tokens](https://thomasvanlaere.com/posts/2023/03/azure-confidential-computing-verifying-microsoft-azure-attestation-jwt-tokens/)
