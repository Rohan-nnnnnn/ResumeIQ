# ResumeIQ – AI-Powered Resume Analyzer and Builder

ResumeIQ is an AI-powered resume analysis and improvement system built using **n8n, LLMs, and Google Drive**. It processes uploaded resumes, evaluates their content, identifies improvement areas, generates suggested corrections, and verifies the results through dedicated AI processing stages.

The system is designed to support general resume improvement rather than relying on a fixed candidate profile.

## Features

- **Resume Upload:** Uses Google Drive as the resume input source.
- **Resume Content Extraction:** Processes uploaded resume documents to make their content available for analysis.
- **AI-Powered Analysis:** Evaluates resume content and identifies areas that need improvement.
- **Correction Generation:** Generates suggestions to improve resume wording, clarity, and presentation.
- **AI Verification:** Uses a dedicated verification stage to review generated corrections.
- **Resume Building Support:** Helps produce improved resume content based on the available candidate information.
- **Workflow Automation:** Coordinates the complete process through n8n.

## Technology Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| LLM Integration | Resume analysis and content generation |
| Google Drive | Resume input and file management |
| Document Processing | Resume content extraction |
| AI Verification | Review of generated improvements |

## Workflow

1. A resume is uploaded to the configured Google Drive location.
2. n8n retrieves the uploaded resume.
3. The document is processed to extract its content.
4. The extracted information is passed to the AI analysis stage.
5. The analysis identifies strengths and improvement areas.
6. The correction stage generates improved resume content.
7. The verifier reviews the generated output.
8. The workflow combines the relevant results.
9. The final resume improvement output is returned.

## AI Processing Pipeline

ResumeIQ uses multiple AI processing stages to separate different responsibilities:

- Resume Analysis: Evaluates the original resume.
- Correction: Generates suggested improvements.
- Verification: Reviews the generated corrections.
- Result Merging: Combines the relevant outputs into the final result.

## Setup Requirements

Before running ResumeIQ, ensure you have:

- n8n installed and running.
- Google Drive credentials configured in n8n.
- The required LLM service and model configured.
- The required document extraction or conversion path configured.
- The ResumeIQ workflow imported or created in n8n.

## How to Use

1. Open the configured Google Drive input location.
2. Upload the resume you want to analyze.
3. Execute or activate the ResumeIQ workflow.
4. Allow the document extraction and AI processing stages to complete.
5. Review the analysis and suggested corrections.
6. Check the final verified output.

## Important Note

ResumeIQ generates AI-assisted resume improvements. Users should review all suggestions for factual accuracy before using the resulting resume. The system should not introduce qualifications, skills, achievements, or experience that the candidate does not possess.

## Project Objective

The objective of ResumeIQ is to demonstrate how multiple AI processing stages and workflow automation can be combined to analyze resumes, generate improvements, and verify AI-generated content.

## Author

**Rohan Narlawar**

- GitHub: [Rohan-nnnnnn](https://github.com/Rohan-nnnnnn)
- LinkedIn: [linkedin.com/in/rohan-narlawar-149291354](https://www.linkedin.com/in/rohan-narlawar-149291354)
- Email: [rohannarlawar31@gmail.com](mailto:rohannarlawar31@gmail.com)
