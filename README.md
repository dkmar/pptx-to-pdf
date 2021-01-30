> Looks like some people used the docx converter I made a few years ago, so I'm finally getting around to uploading the equivalent for Powerpoint files.

# Convert Powerpoint files to PDF on macOS 
Finder "Quick Action" to convert powerpoint files to pdf using Automator and a bit of AppleScript
![](demo.gif)
## Installing
### Option 1:
1. Download the zip
2. Double-click on the zip in Finder to unzip it. This should yield the workflow.
3. Double-click the workflow and click "Install" on the pop-up dialog.
### Option 2:
```bash
cd ~/Library/Services
wget https://github.com/dkmar/pptx-to-pdf/raw/main/PptxToPDF.workflow.zip
tar xf PptxToPDF.workflow.zip && rm -r PptxToPDF.workflow.zip
```
## Basic Automator Workflow
![](PptxToPDF.workflow/Contents/QuickLook/Preview.png?raw=true)
Note: tested on macOS 10.15 
