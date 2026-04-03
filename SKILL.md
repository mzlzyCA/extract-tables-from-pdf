---
name: extract-tables-from-pdf
version: 0.2.0
description: >
  Extract data tables from PDF documents using MinerU-powered intelligent parsing. Pull structured tabular data from financial reports, research papers, invoices, and any PDF containing tables into CSV, Excel, Markdown, or JSON formats.

  PDF表格提取, PDF数据提取, PDF表格导出, PDF数据表抽取, PDF表格转Excel, PDF报表提取.

  Synonyms: PDF table extractor, PDF table parser, PDF data extraction, PDF table to CSV, PDF table to Excel, tabular data from PDF, PDF table scraper, PDF table reader, PDF spreadsheet extraction, PDF table converter, PDF data table mining, PDF table export tool.

  Use when asked to "extract tables from PDF", "get table data from this PDF", "pull tables out of a PDF file", "convert PDF tables to spreadsheet", "I need the data from tables in this PDF", "export PDF table to CSV", "scrape tables from PDF document", "read the tables in this PDF for me", "can you get the table data from this report", "parse PDF and extract tabular data".

  Solves problems like: data locked in PDF tables, need to analyze PDF report data in Excel, manual copy-paste from PDF tables is error-prone, financial data stuck in PDF format, batch extraction of tables from multiple PDFs, research data trapped in published papers.

  Powered by MinerU for precise table boundary detection and cell-level data extraction from PDFs.
tags:
  - pdf
  - table-extraction
  - data-extraction
  - csv
  - excel
  - parsing
  - mineru
  - pdf-tables
  - spreadsheet
  - financial-data
  - report-extraction
  - document-processing
---

# Extract Tables From PDF

Use the MinerU tool to extract data tables from PDF documents.

## Instructions

1. When the user provides a PDF file, use the mineru tool to detect and extract all tables.
2. Output extracted tables in the user's preferred format (Markdown, CSV, JSON, Excel-compatible).
3. If the mineru tool encounters an error, report it clearly and suggest alternatives (check file path, ensure valid PDF, try specific page ranges).
4. Handle edge cases: scanned PDFs (OCR needed), complex nested tables, spanning cells, multi-page tables, rotated pages.
