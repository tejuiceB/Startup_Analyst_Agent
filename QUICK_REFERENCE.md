# 🚀 Quick Reference - Startup Investor Agent

## Installation
```bash
cd c:\Users\Tejas\OneDrive\Desktop\agents
pip install -r startup_investor_agent/requirements.txt
adk dev
```

## Basic Commands

### Upload Documents
```
"Process this file: C:\Docs\pitch_deck.pptx"
"Process this file: C:\Docs\financial_model.xlsx"
"Process this file: C:\Docs\business_plan.pdf"
```

### Common Questions
```
"What's the market size?"
"Tell me about the team"
"What are the main risks?"
"What's the revenue model?"
"How's the traction?"
"What's the valuation?"
"Show me the use of funds"
"What are the exit scenarios?"
```

### Request Specific Analysis
```
"Deep dive into market analysis"
"Analyze the competitive landscape"
"Review the financial projections"
"Assess the team quality"
"What are the risk factors?"
```

### Memory & History
```
"What did we discuss about revenue?"
"Show me all documents uploaded"
"What was the growth rate we talked about?"
```

## Supported File Formats

| Format | Extensions | Use Case |
|--------|-----------|----------|
| PowerPoint | .pptx, .ppt | Pitch decks |
| PDF | .pdf | Documents, reports |
| Word | .docx, .doc | Business plans |
| Excel | .xlsx, .xls, .csv | Financial models |
| JSON | .json | Structured data |
| Images | .jpg, .png, .gif | Screenshots (OCR) |
| Text | .txt, .md | Notes, docs |

## 9 AI Agents

1. **Master Orchestrator** - Workflow coordination
2. **Pitch Deck Analyst** - Business model evaluation
3. **Market Analysis** - Market size & competition
4. **Team Assessment** - Founder & team quality
5. **Financial Analysis** - Metrics & projections
6. **Competitive Analysis** - Moat & differentiation
7. **Risk Assessment** - Risk identification
8. **Due Diligence** - DD checklist
9. **Investment Thesis** - Final recommendation

## Report Sections

- 📋 Executive Summary
- 🎯 Investment Scorecard
- 💰 Key Metrics
- 📈 Detailed Analysis (8 sections)
- ⚠️ Risk Matrix
- 💼 Investment Structure
- 💡 Investment Thesis
- 🎯 Final Recommendation

## Troubleshooting

### File Upload Issues
```
❌ "Error: File not found"
✅ Use absolute path: C:\Users\...\file.pptx

❌ "Unsupported file type"
✅ Use supported formats (see table above)

❌ "Circular reference detected"
✅ Already fixed in current version
```

### Agent Issues
```
❌ "No analysis available"
✅ Upload documents first

❌ "Agent not responding"
✅ Restart ADK dev server

❌ "Report is empty"
✅ Check if documents were processed successfully
```

## Best Practices

### DO ✅
- Provide absolute file paths
- Upload all relevant documents
- Ask specific follow-up questions
- Reference previous discussions
- Use supported file formats

### DON'T ❌
- Upload files through chat interface (use paths)
- Assume data persists after session ends
- Upload very large files (>100MB)
- Expect analysis without documents

## Project Structure
```
startup_investor_agent/
├── __init__.py
├── agent.py                 # Main agent code
├── requirements.txt         # Dependencies
├── README.md               # Full documentation
├── SCREENSHOT_GUIDE.md     # Media capture guide
├── QUICK_REFERENCE.md      # This file
├── screenshots/            # Screenshots folder
│   ├── adk_ui.png
│   ├── document_upload.png
│   ├── auto_analysis.png
│   ├── report_generated.png
│   ├── agent_trace.png
│   ├── scorecard.png
│   ├── risk_matrix.png
│   └── followup.png
└── demo/                   # Video demos folder
    ├── full_demo.mp4
    └── quick_start.mp4
```

## Key Features

- ✅ Auto-analysis on document upload
- ✅ 10+ file format support
- ✅ Perfect memory system
- ✅ Real data extraction
- ✅ Professional reports
- ✅ Local memory storage
- ✅ Context-aware Q&A
- ✅ Risk assessment
- ✅ Investment recommendations

## Development Stats

- **Lines of Code:** 1,800+
- **Functions:** 50+
- **Agent Tools:** 20+
- **Supported Formats:** 10+
- **Specialized Agents:** 8
- **Development Time:** 5 hours

## Contact & Support

- **Developer:** Tejas
- **Built with:** Google ADK, Python 3.13, Gemini 2.0
- **Version:** 2.0
- **Status:** Production Ready ✅

---

*Quick Reference v2.0 - Last Updated: October 2, 2025*
