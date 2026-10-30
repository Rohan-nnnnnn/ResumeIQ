RESUMEIQ – SETUP GUIDE

Overview

This guide explains how to configure and run ResumeIQ using n8n, Google Drive, and an AI language model.

Prerequisites

Ensure you have:

- n8n installed and running.
- Google Drive credentials configured in n8n.
- Access to the configured LLM service.
- Required AI model or API credentials.
- The document extraction or conversion mechanism configured.
- The ResumeIQ workflow imported or created in n8n.

1. Configure Google Drive

Connect your Google Drive account through n8n credentials.

Verify that:
- The correct Google Drive account is connected.
- The resume input location is configured.
- The workflow has permission to retrieve uploaded documents.
- Any configured output location is accessible.

2. Configure AI Services

Open the AI-related nodes in the ResumeIQ workflow.

Verify that:
- The required LLM service is accessible.
- The correct model is configured.
- API credentials are valid, if required.
- Each AI processing stage has its appropriate prompt.
- The expected output format is configured correctly.

3. Configure Document Extraction

Verify the document retrieval and extraction stages.

Ensure that:
- Uploaded resumes can be retrieved.
- The configured extraction or conversion path supports the intended document type.
- Extracted text is passed correctly to the AI analysis stage.
- Empty or unreadable document content is handled appropriately.

4. Verify AI Processing Stages

Inspect the analysis, correction, and verification stages.

Confirm that:

- Analysis receives the extracted resume content.
- Correction receives the required analysis results.
- Verification receives the generated corrections and relevant original information.
- The Merge stage combines the intended outputs.
- The final result follows the expected structure.

5. Run the Workflow

1. Start n8n.
2. Verify Google Drive and AI service connections.
3. Upload a resume to the configured Google Drive location.
4. Execute or activate the ResumeIQ workflow.
5. Monitor document retrieval and extraction.
6. Check the AI analysis and correction stages.
7. Verify the output from the verification stage.
8. Inspect the final merged result.

Troubleshooting

Google Drive Connection Error

- Verify Google Drive credentials.
- Check folder permissions.
- Confirm the correct file or folder ID is being used.

Document Extraction Failure

- Verify that the uploaded document is supported.
- Check the document extraction or conversion node.
- Ensure the extracted text is not empty.
- Inspect the node execution output.

AI Processing Failure

- Verify the AI service connection.
- Check model availability and credentials.
- Inspect the prompt and input data.
- Review the failed AI node's execution output.

Incorrect Resume Suggestions

- Check the extracted resume content.
- Verify that the analysis stage receives complete information.
- Inspect the correction and verification prompts.
- Ensure the workflow does not introduce unsupported candidate details.

Merge or Output Failure

- Verify the inputs connected to the Merge stage.
- Check the output structure of previous AI stages.
- Confirm that the final output contains the expected fields.

Important Notes

- ResumeIQ depends on the configured document extraction method and supported file types.
- AI output quality depends on the source resume and model configuration.
- Generated suggestions should be reviewed before being used in an actual job application.
- Never include fabricated qualifications, skills, achievements, or employment history in the final resume.
