# CV Analyzer

Resume Analyzer - A tool for analyzing resumes/CVs using Google Drive integration.

## Description

CV Analyzer is a Python-based application designed to analyze curriculum vitae (resumes) stored in Google Drive. The
application uses OAuth 2.0 authentication to securely access your Google Drive files.

## Features

- Google Drive authentication using OAuth 2.0
- Secure credential management with token persistence
- Support for reading and analyzing files from Google Drive
- Automatic token refresh for seamless authentication

## Prerequisites

- Python 3.14 or higher
- Google Cloud Project with Drive API enabled
- OAuth 2.0 credentials (credentials.json file)

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd cv-analyzer
```
2. Cadastro no google API

[APIs Google](https://console.cloud.google.com/apis/library?pli=1)
- Buscar API do google drive
- Criar um projeto

