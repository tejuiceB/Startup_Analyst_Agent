# 📸 Screenshot Guide

## Required Screenshots

Please capture and save the following screenshots to the `screenshots` folder:

### 1. adk_ui.png
**What to capture:** The main ADK UI showing the agent list
- Open the ADK dev UI in browser
- Show the agent selector with "startup_investor_master_agent"
- Include the sidebar with all tools visible

### 2. document_upload.png
**What to capture:** Document upload process
- Show the chat interface
- Display the file paths for Jyoti documents
- Show the "process_uploaded_file" function calls
- Include checkmarks for successful uploads

### 3. auto_analysis.png
**What to capture:** Auto-analysis execution
- Show the "🔄 Running comprehensive analysis..." message
- Display the "auto_analyze_documents" function call
- Show the agent working on analysis

### 4. report_generated.png
**What to capture:** The complete report
- Show the formatted markdown report
- Include sections: Executive Summary, Scorecard, Key Metrics
- Display the comprehensive analysis output

### 5. agent_trace.png
**What to capture:** Agent trace visualization
- Click on "Trace" tab in ADK UI
- Show the visual graph of agent calls
- Display all 8 specialized agent tools being invoked

### 6. scorecard.png
**What to capture:** Investment scorecard section
- Zoom into the scorecard table
- Show the category scores and weights
- Display the rationale column

### 7. risk_matrix.png
**What to capture:** Risk assessment section
- Show the risk matrix table
- Display risk types, levels, and mitigation
- Include all risk categories

### 8. followup.png
**What to capture:** Follow-up question interaction
- Ask a question like "What's the market size?"
- Show the agent's response using memory
- Display context-aware answer

---

## Screenshot Instructions

### How to Take Screenshots:

**Windows:**
1. Press `Windows + Shift + S` to open Snipping Tool
2. Select area to capture
3. Screenshot copied to clipboard
4. Open Paint or any image editor
5. Paste (Ctrl+V)
6. Save as PNG with exact filename from above
7. Save to: `c:\Users\Tejas\OneDrive\Desktop\agents\startup_investor_agent\screenshots\`

**Alternative:**
- Use browser extension like "FireShot" for full-page screenshots
- Use OBS or ShareX for screen recording

### Screenshot Best Practices:
- ✅ Use high resolution (1920x1080 or higher)
- ✅ Crop to relevant content only
- ✅ Include enough context to understand what's shown
- ✅ Use PNG format (better quality than JPG)
- ✅ Name files exactly as shown above
- ✅ Ensure text is readable

---

## Video Recording Guide

### Required Videos

Save to `demo` folder:

#### 1. full_demo.mp4 (5 minutes)
**Content:**
- Introduction to the system (30s)
- Upload Jyoti documents (30s)
- Watch auto-analysis run (1min)
- Review generated report (1.5min)
- Ask follow-up questions (1min)
- Demonstrate memory system (30s)

#### 2. quick_start.mp4 (5 minutes)
**Content:**
- Quick intro (30s)
- Installation steps (1min)
- First document upload (1min)
- Understanding the report (1.5min)
- Q&A examples (1min)

### How to Record Videos:

**Windows (Built-in):**
1. Press `Windows + G` to open Game Bar
2. Click record button
3. Record your screen
4. Stop recording
5. Video saved to `Videos\Captures`
6. Move to demo folder and rename

**Professional Tools:**
- OBS Studio (Free): https://obsproject.com/
- Camtasia (Paid): Screen recording + editing
- ShareX (Free): Screenshots + video

### Video Best Practices:
- ✅ Record in 1080p or higher
- ✅ Use clear audio (explain what you're doing)
- ✅ Show cursor movements
- ✅ Zoom in on important details
- ✅ Keep each demo focused and concise
- ✅ Edit out long waits or errors
- ✅ Add captions if possible

---

## Thumbnail Creation

For video thumbnails:

### video_thumbnail.png
- Screenshot from the most interesting part of full demo
- Add text overlay: "Full Demo - 5 min"
- Show the report being generated

### quickstart_thumbnail.png
- Screenshot from quick start video
- Add text overlay: "Quick Start - 5 min"
- Show the agent interface

**Tools for thumbnails:**
- Canva (online, free)
- GIMP (free, desktop)
- Photoshop (paid)

---

## Checklist

Before finalizing README:

- [ ] All 8 screenshots captured and saved
- [ ] Screenshots named correctly
- [ ] Screenshots are clear and readable
- [ ] Full demo video recorded (5 min)
- [ ] Quick start video recorded (5 min)
- [ ] Video thumbnails created
- [ ] All files saved to correct folders
- [ ] README links verified
- [ ] File sizes reasonable (<10MB per image, <100MB per video)

---

## After Capturing

1. Verify all files exist:
```
screenshots/
├── adk_ui.png
├── document_upload.png
├── auto_analysis.png
├── report_generated.png
├── agent_trace.png
├── scorecard.png
├── risk_matrix.png
├── followup.png
├── video_thumbnail.png
└── quickstart_thumbnail.png

demo/
├── full_demo.mp4
└── quick_start.mp4
```

2. Test README by viewing it:
- Open README.md in VS Code
- Click "Open Preview" (Ctrl+Shift+V)
- Check that all images display
- Verify all links work

3. Compress files if needed:
- Images: Use TinyPNG.com or similar
- Videos: Use HandBrake or similar

---

**Need Help?**
- Screenshot not clear? Retake it!
- Video too large? Compress or reduce resolution
- Link broken? Check file paths and names

**Ready to share!** 🚀
