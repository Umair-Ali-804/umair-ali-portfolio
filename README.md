# Umair Ali · AI Engineer Portfolio

Personal portfolio of Umair Ali, AI Engineer (RAG, AI agents, LLM applications) and researcher in medical hallucination detection.

**Live site:** https://umair-ali-portfolio.onrender.com

## Featured work
- **ClinHallu**: research on source-to-benchmark shift in medical hallucination detection ([code](https://github.com/Umair-Ali-804/ClinHallu))
- **AAXIS AI RAG Assistant**: company chatbot over live PDFs ([demo](https://aaxis-ai-rag-assistant.onrender.com) · [code](https://github.com/Umair-Ali-804/AAXIS_AI_RAG_ASSISTANT))
- **AAXIS InvoiceFlow**: invoice capture with human review and QuickBooks posting ([demo](https://aaxis-invoiceflow.onrender.com) · [code](https://github.com/Umair-Ali-804/AAXIS_InvoiceFlow))
- **Medical Coding AI**: evidence-backed ICD-10-CM/CPT/HCPCS coding assistant ([code](https://github.com/Umair-Ali-804/Medical-Coding-AI-Application))

## Structure
```
index.html            the whole site (HTML + CSS + JS, no build step)
assets/               photo, paper page 1, resume PDF
render.yaml           Render static-site blueprint
```

## Run locally
```
python -m http.server 8000
# open http://localhost:8000
```

## Deploy
Hosted on Render as a static site. Every push to `main` redeploys automatically.
