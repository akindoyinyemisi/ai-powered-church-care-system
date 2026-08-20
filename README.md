# AI-Powered Church Care & Member Engagement System

An intelligent church member engagement workflow built with n8n, Google Gemini, Google Sheets, and Gmail.

## Project Overview

This project automates how a church receives, understands, records, and responds to member requests submitted through an online form.

Instead of manually reviewing every submission, the workflow uses AI to analyse each request, classify it, determine its priority, generate an appropriate response, and support follow-up.

## How It Works

1. A member submits the Church Connect & Care Form.
2. Google Gemini analyses the submitted message.
3. The request is classified into an appropriate category.
4. A priority level is assigned based on the request.
5. The submission and AI-generated information are stored in Google Sheets.
6. The workflow routes the request based on its classification and priority.
7. Gmail automatically sends the appropriate response or notification.

## Key Features

- Online church care and engagement form
- AI-powered message analysis
- Automatic request categorisation
- Priority identification for member requests
- Google Sheets database integration
- Automated personalised email responses
- Conditional routing using n8n
- Support for pastoral care, prayer requests, membership enquiries, first-time visitors, and general enquiries
- Automated internal alerts for requests requiring attention

## Technologies Used

- n8n – Workflow automation
- Google Gemini – AI analysis and response generation
- Google Sheets – Member request database
- Gmail – Automated email communication

## Workflow Architecture

Form Submission → Google Gemini AI → Google Sheets → Conditional Routing → Gmail Response / Church Team Alert

## Use Case

This system demonstrates how AI and automation can support church administration and member care by reducing repetitive manual work, improving response time, and helping important requests receive appropriate attention.

## Security

Credentials, API keys, OAuth tokens, and other sensitive authentication information are not included in the public version of this workflow.

## Author

Yemisi Blessing Akindoyin

AI Automation | Administrative Support | Community Management | Growth & Partnerships
