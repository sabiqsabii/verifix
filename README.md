VERIFIX — Digital File Forensics and Document Authenticity Verification System

VERIFIX is a browser-based application designed to analyze digital files, register document certificates, and verify document authenticity using cryptographic hashes and QR codes.

The system helps identify suspicious file characteristics and check whether a document matches a previously registered certificate.

Features

1. Digital File Forensics Analyzer

Upload files through file selection or drag and drop.

Generate SHA-256 and MD5 hashes.

Detect file types using magic bytes.

Perform file integrity and anomaly checks.

Analyze file entropy.

Extract available EXIF metadata.

2. Certificate Registration

Register certificates with document and holder details.

Validate registration inputs.

Generate unique certificate IDs.

Generate QR codes for registered certificates.

Detect duplicate document hashes.

Store registered records in browser storage.

3. Document Verification

Verify documents using uploaded files or hashes.

Compare document hashes against registered records.

Scan QR codes using a camera.

Upload QR code images for verification.

Display verification results.

4. History and Analytics

View registered certificates.

Search certificate records.

View file analysis sessions.

Track verification attempts.

Import and export certificate records.

Manage stored records.

Technologies Used

HTML5

CSS3

JavaScript

Web Crypto API

Browser Local Storage

QR code generation and scanning libraries

Project Structure

VERIFIX/
├── index.html
├── Member_1_Forensics_Analyzer.html
├── Member_2_Certificate_Registration_QR.html
├── Member_3_Document_Verification.html
├── Member_4_History_Analytics.html
└── README.md

The member HTML filenames above are examples. Replace them with your actual filenames if they are different.

Installation and Usage

Download or clone the repository.

Open the project folder.

Open index.html in a modern web browser.

Upload a file to analyze its characteristics.

Register a certificate and generate its QR code.

Use the verification section to check a document.

View records and verification history in the dashboard.

For camera-based QR scanning, run the application through localhost or HTTPS and grant camera permission when prompted.

Data Storage

VERIFIX uses browser Local Storage to maintain records. Data remains in the browser where it was created and is not automatically synchronized across devices.

Export important records regularly. Clearing browser data may remove stored records.

Limitations

The application operates primarily on the client side.

Verification depends on previously registered records being available.

A matching hash confirms that the file's bytes match the registered file; it does not independently prove the identity or legitimacy of the issuer.

File metadata and anomaly checks can provide indicators but cannot guarantee that a file is safe or authentic.

Local Storage is not a secure, centralized certificate database.

Team Contributions

The project is divided into four main modules:

Member 1: Digital File Forensics Analyzer

Member 2: Certificate Registration and QR Generation

Member 3: Document Verification Portal

Member 4: History, Analytics and Data Management

index.html is the main application entry point. The four member files are maintained separately for contribution and development purposes.

Future Enhancements

Integration with a secure centralized database.

User authentication and role-based access.

Digital signatures for certificate issuers.

Improved forensic analysis and reporting.

Secure cloud-based certificate verification.

Disclaimer

VERIFIX is an educational project developed for digital file analysis and document verification demonstrations. It should not be treated as a replacement for professional digital forensics or a trusted certificate authority.
