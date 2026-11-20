# PolicyBrief AI
### Governance Edition — Version 3.0

An independent educational prototype for AI-assisted policy analysis, risk documentation, red-team testing, and human-reviewed policy briefings.

## Project Overview

PolicyBrief AI helps users analyse public policy documents using a structured, source-grounded workflow. It encourages evidence-based analysis, identification of missing information, AI risk documentation, and human oversight.

## Key Features

### 1. Policy Analysis
- Generate structured prompts for policy analysis.
- Separate source evidence from interpretation.
- Identify missing information and uncertainty.
- Generate policy briefing drafts.

### 2. AI Risk Register
- Document five example AI-related risks.
- Record potential harms, likelihood and severity.
- Identify safeguards and responsible human owners.
- Export risk register as CSV.

### 3. Red-Team Testing
- Includes 10 test scenarios.
- Tests hallucinations, prompt injection, unsupported legal claims, fabricated citations, privacy risks and more.
- Records actual responses and reviewer assessments.
- Exports test results as CSV and Markdown.

### 4. Evaluation and Human Review
- Evaluate AI-generated policy analysis.
- Use a seven-point human evaluation checklist.
- Record reviewer decisions and notes.
- Generate downloadable policy briefing reports.

## Technology Stack

- Python
- Streamlit
- Pandas
- Notion and ChatGPT may be used in the wider project workflow.

## Installation

1. Clone or download this repository.
2. Open the project folder in a terminal.
3. Create a virtual environment:

```bash
python -m venv .venv
```

4. Activate it on Windows:

```bash
.venv\Scripts\activate
```

5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Run the application:

```bash
python -m streamlit run app.py
```

## Testing

The project includes 10 manually conducted red-team scenarios. Results are recorded in the application and exported for documentation.

Testing focuses on:
- Unsupported claims and hallucinations
- Prompt injection
- Publication date verification
- Unsupported legal claims
- Fabricated citations
- Sensitive information handling
- Missing information and uncertainty
- Unsupported recommendations
- Premature approval and automation bias

## Limitations

- This is an independent educational prototype.
- The application does not automatically call an AI model.
- Prompts are copied manually into an AI assistant.
- Responses are pasted back into the application for evaluation.
- Red-team tests are manually conducted, not automated.
- Human verification against original policy sources remains necessary.
- Test results may need to be downloaded to preserve them between sessions.

## Project Status

Version 3.0 — Educational prototype.

## Responsible Use

Use public policy documents only. Verify important claims against original sources. Do not enter confidential or personal information. AI-generated analysis should not replace professional policy or legal review.

## Author

Harsh

