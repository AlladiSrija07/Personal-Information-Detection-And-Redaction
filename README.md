# Personal-Information-Detection-And-Redaction
Personal Information Detection And Redaction Description
## Personally Identifiable Information (PII)

Personally Identifiable Information (PII) refers to any information that can identify an individual directly or, in some cases, when combined with other information. Examples include Aadhaar numbers, PAN numbers, phone numbers, and email addresses.

### Why Is PII Protection Important?

Protecting PII helps prevent identity theft, unauthorized access, privacy violations, and the misuse of sensitive personal information. Documents shared in sectors such as banking, healthcare, education, and real estate may contain confidential information that must be protected.

### PII Detection and Redaction

This project is designed to detect sensitive personal information in PDF documents using Python, Flask, PyMuPDF, and regular expressions (Regex). It extracts text and its coordinates from uploaded PDFs, identifies potential PII patterns, and allows users to select sensitive information for redaction. The processed PDF can then be downloaded with the selected information permanently obscured using appropriate PDF redaction operations.

### Types of PII Detected

- **Aadhaar Number:** A 12-digit Indian identification number.
- **PAN Number:** An Indian Permanent Account Number used for tax-related identification.
- **Phone Number:** An individual's contact number.
- **Email Address:** An individual's electronic mail address.

### Project Workflow

1. Upload a PDF document.
2. Extract text and coordinates using PyMuPDF.
3. Detect potential PII using regular expressions and applicable validation checks.
4. Display detected information for user review and selection.
5. Apply redaction to the selected sensitive information.
6. Download the redacted PDF.

### Objective

The main objective is to improve document privacy by helping users identify and remove sensitive personal information before sharing PDF files. The project demonstrates the practical application of text extraction, pattern matching, web development, and privacy protection.
