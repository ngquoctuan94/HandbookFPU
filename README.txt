UN project - PDF externalization

The original embedded PDF Base64 blocks were extracted into pdf/*.pdf.
index.html was updated so the PDF viewer fetches the corresponding external PDF.

Run with VS Code Live Server. Do not open index.html directly with file:// because
browser fetch restrictions can prevent loading external PDFs.
