# Awesome-Document-Intelligence

## Top Document Intelligence Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Intelligent Document Processing, Data Extraction & AI-Powered Document Automation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Intelligence**. These tools enable organizations to automatically classify, extract, and process data from structured, semi-structured, and unstructured documents—invoices, receipts, contracts, forms, and identity documents—using OCR, machine learning, and generative AI to power downstream automation.



**Examples** include ServiceNow Document Intelligence, ABBYY Vantage, AWS Textract, Google Cloud Document AI, Rossum, Hyperscience, Kofax TotalAgility, Infrrd, Ocrolus, and Automation Anywhere IDP (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted document parsing, OCR pipelines, and LLM-ready document conversion—ideal for organizations building sovereign document intelligence without per-page API pricing or data leaving their infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Document Intelligence](https://www.servicenow.com/)**  

  Now Assist in Document Intelligence (NADI) is the GenAI-powered successor to Classic Document Intelligence, using LLM-based zero-shot extraction guided by plain-language key descriptions—no model training or templates required; supports key information extraction, Q&A, and summarization across structured, semi-structured, and unstructured documents; requires Generative AI Controller with an approved LLM provider; Classic use cases cannot be auto-migrated and must be rebuilt in NADI .



- **[ABBYY Vantage](https://www.abbyy.com/)**  

  Vantage 3.0 combines purpose-built document AI with generative AI for enterprise document processing; features 150+ pre-trained models (invoices, purchase orders, tax forms, mortgage documents), prompt-based extraction with citation templates and continuous validation, integrated redaction, and SOC 2/ISO certifications; positioned as the intelligence layer for agentic automation .



- **[AWS Textract](https://aws.amazon.com/textract/)**  

  Managed OCR and document analysis service with APIs for forms (key-value pairs), tables, signatures, queries, and specialized extraction via AnalyzeExpense (invoices/receipts) and AnalyzeID (identity documents); supports synchronous processing up to 10 MB and asynchronous processing up to 500 MB PDFs .



- **[Google Cloud Document AI](https://cloud.google.com/document-ai)**  

  Document processing platform with the Layout Parser now generally available for transforming documents into structured representations; offers pre-trained and custom extractors for common document types.



- **[Rossum](https://rossum.ai/)**  

  AI-native document automation platform with SAP Certified Integration for S/4HANA Cloud; processes invoices, purchase orders, sales orders, and trade documents in 276+ languages with template-free AI that learns from feedback; claims 98% extraction accuracy and 70% touchless order processing; side-by-side architecture preserves SAP Clean Core compliance without Z-modifications .



- **[Hyperscience](https://hyperscience.com/)**  

  Intelligent document processing platform with ML-based extraction and human-in-the-loop review; recent releases focus on training data management, submission filtering, and PostgreSQL 18.4 support; available as SaaS or on-premises Kubernetes deployment .



- **[Kofax TotalAgility](https://www.kofax.com/)**  

  Integrated intelligent automation platform combining low-code process design, AI-driven document processing, RPA, and case management; the TotalAgility-Azure OpenAI connector adds generative AI for unstructured text analysis, sentiment detection, and content generation within workflows; deployment options include Kofax-hosted cloud and customer-hosted on-premises .



- **[Infrrd](https://www.infrrd.ai/)**  

  Document intelligence platform with Doc Studio, a no-code environment for building custom extraction models from a single document without training or configuration; features Smart Doc Q&A for querying documents directly and extracting answers as new fields; pre-trained on millions of documents for invoices, handwritten notes, and engineering diagrams .



- **[Ocrolus](https://www.ocrolus.com/)**  

  Document AI platform focused on lending and financial intake workflows; provides classification across 2,100+ document types, bank statement analysis, income verification (pay stubs, W-2s), tax form extraction (1099s, 1040s), identity document extraction, and Detect for document tampering forensics—all at 99%+ claimed accuracy .



- **[Automation Anywhere IDP](https://www.automationanywhere.com/)**  

  Intelligent document processing integrated into Automation Anywhere's agentic process automation platform; combines traditional ML models with LLM and generative AI for extraction from complex unstructured documents; positions IDP as the data layer feeding AI agents that validate, reconcile, and act on extracted content .



## Open-Source GitHub Projects



- **[Docling](https://github.com/docling-project/docling)**  

  MIT-licensed IBM Research toolkit for parsing PDF, DOCX, PPTX, images, HTML, and more into structured JSON/Markdown; uses DocLayNet for layout analysis and TableFormer for table structure recognition, with native LangChain/LlamaIndex integration and efficient CPU execution .



- **[Unstructured](https://github.com/Unstructured-IO/unstructured)**  

  Open-source library for partitioning and extracting structured content from raw documents (PDF, HTML, Word, images); provides chunking by document elements and cleaning functions optimized for LLM/RAG pipelines (open-source version is for prototyping, not production-scale) .



- **[Apache Tika](https://github.com/apache/tika)**  

  Foundational content detection and extraction toolkit supporting 1,600+ file formats; the `tikara` Python wrapper provides JNI-based integration with streaming, language detection, MIME detection, and recursive document unpacking .



- **[Docext (Nanonets)](https://github.com/Nanonets/docext)**  

  On-premises, OCR-free unstructured data extraction and markdown conversion toolkit with benchmarking; positioned as an open-source alternative for document intelligence .



- **[TWIX](https://github.com/ucbepic/TWIX)**  

  Open-source data extraction tool that reconstructs structured data from documents at scale by inferring shared visual templates across documents; suitable for high-volume, low-cost extraction pipelines .



- **[DocSlight](https://github.com/ComPDFKit/docslight)**  

  Open-source AI document parsing and extraction project from ComPDF (KDAN ecosystem); supports PDF, scans, images, and Office files with PaddleOCR/VLM OCR, layout analysis, field extraction with BBox traceability, and outputs Markdown/JSON/Text for RAG and IDP workflows .



- **[docket](https://pypi.org/project/docket-idp/)**  

  Local document AI pipeline with hybrid OCR (text layer → Tesseract → VLM), classification, and Pydantic-schema extraction; includes deterministic validation (IBAN, VAT, arithmetic), human-in-the-loop review queue, FastAPI REST API, and support for invoices, receipts, contracts, and CLM analysis .



- **[ocrguru](https://pypi.org/project/ocrguru/)**  

  Lightweight CLI wrapper around the Docling OCR pipeline; supports RapidOCR, EasyOCR, and Tesseract engines with output to Markdown, JSON (with coordinates), or hOCR; MIT-licensed and cross-platform .



- **[pyonb](https://github.com/SAFEHR-data/pyonb)**  

  Open-source Python SDK bundling multiple OCR tools (Marker, Sparrow, PaddleOCR) behind a unified forwarding API for automated document-to-text conversion; containerized services suitable for clinical and large-scale archival processing .



### Additional Strong Open-Source Options



- **PaddleOCR** — Multilingual OCR toolkit with layout analysis and table recognition; widely used as an extraction engine in larger pipelines.

- **Tesseract** — The classic open-source OCR engine; still the default fallback in many extraction stacks.

- **Marker** — Fast PDF-to-Markdown conversion with table and equation support, often paired with OCR engines.

- **MinerU** — Document extraction toolkit with layout and formula recognition for scientific PDFs.

- **olmOCR** — OCR-focused toolkit for converting PDFs to clean text for LLM training pipelines.



**Frameworks for building custom systems**: Combine **Docling** for structured document conversion, **Tesseract** or **PaddleOCR** for OCR, **docket** for schema-validated field extraction, **Unstructured** for RAG-ready chunking, and **DocSlight** for BBox-traceable field extraction in a fully self-hosted document intelligence pipeline.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Document intelligence systems handling business documents and personal data must comply with applicable privacy regulations (GDPR, HIPAA, etc.) and industry-specific requirements; extraction accuracy validation and human-in-the-loop review are essential for financial and regulated document workflows.

- Self-hosted open-source solutions vary significantly in scope—Docling and Unstructured provide strong parsing foundations, but full IDP platforms with pre-trained models, business-rule validation, and SAP/ERP integrations typically require commercial platforms like ABBYY, Rossum, or Kofax.

- Verify license terms for commercial use; Docling uses MIT, and other projects have varying licenses (check individual repositories).



---



**Made for document AI engineers, finance operations teams, automation architects, and intelligent document processing practitioners.**  

Let's make document intelligence more open, accurate, and automation-ready.
