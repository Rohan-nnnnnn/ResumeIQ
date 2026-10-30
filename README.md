ResumeIQ — AI-Powered Resume Analysis & Improvement System

Overview

ResumeIQ is an AI-powered resume analysis and improvement system built using n8n and Large Language Models (LLMs). It evaluates resume content, identifies weaknesses, generates improvement suggestions, and verifies recommendations through a multi-stage AI workflow.

The system aims to improve resume quality while preserving factual accuracy and preventing unsupported claims.

Key Features

- Automated resume input through Google Drive.
- Resume content extraction and processing.
- AI-powered resume analysis.
- Identification of missing sections and content weaknesses.
- Context-aware resume improvement suggestions.
- Separate verification stage to review AI-generated recommendations.
- Final structured analysis and improvement output.

Workflow Architecture

1. Resume Submission — A resume is provided through the configured Google Drive input.
2. Text Extraction — Resume content is extracted for processing.
3. Resume Analysis — The AI evaluates structure, skills, experience and content quality.
4. Improvement Generation — The AI generates relevant suggestions based on the analysis.
5. Verification — A separate verification stage checks recommendations for unsupported or fabricated information.
6. Final Output — The verified results are combined into the final response.

Technology Stack

- n8n — Workflow orchestration and automation.
- Large Language Models — Resume analysis and improvement generation.
- Google Drive — Resume input and file management.
- AI verification — Validation of generated recommendations.

Project Structure

- README.md — Project overview and documentation.
- architecture.md — Workflow architecture and processing stages.
- setup-guide.md — Installation and configuration instructions.
- testresults.md — Workflow testing documentation.
- .env.example — Environment configuration template.
- .gitignore — Files excluded from version control.
- screenshots/ — Project workflow and execution screenshots.

Limitations

- Analysis quality depends on extracted resume content and the selected LLM.
- Complex resume formatting may affect text extraction.
- AI-generated recommendations require human review.
- ResumeIQ does not guarantee ATS selection or job placement.

Project Status

Completed prototype. Designed to demonstrate AI-powered document analysis, multi-stage LLM processing, workflow automation and output verification.

Author

Rohan Narlawar

- GitHub: https://github.com/Rohan-nnnnnn
- LinkedIn: [linkedin.com/in/rohan-narlawar-149291354](https://www.linkedin.com/in/rohan-narlawar-149291354)
- Email: [rohannarlawar31@gmail.com](mailto:rohannarlawar31@gmail.com)
