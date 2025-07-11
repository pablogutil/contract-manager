# 📑 Contract Manager

A lightweight dashboard to upload, tag, and extract metadata from contracts using AI. Useful for legal teams, startup ops, and internal document organization.

## 🔍 Features

- Upload PDF or DOCX
- Manual tagging (type, client, jurisdiction)
- Optional LLM-based metadata extraction
- View parsed fields:
  - Parties involved
  - Start/End date
  - Jurisdiction
  - Key clauses
- Search + filter by tag or date

## 🧱 Tech Stack

- React (Vite + TypeScript)
- TailwindCSS
- PDF parsing with client tools
- LLM integration pluggable

## 📁 Folder Highlights

src/
├── components/
│ └── UploadPanel, MetadataViewer, ContractCard
├── lib/
│ └── extractContractMetadata.ts

markdown
Copy
Edit

## ⚙️ Use Cases

- Legal contract search tools  
- Internal CRM or client portals  
- Document workflows for compliance/legal ops

## 💡 Future Ideas

- E-signature integration  
- Smart clause highlighting  
- Comparison view for versions
