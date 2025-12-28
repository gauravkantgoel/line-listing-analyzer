# line-listing-analyzer
A powerful, browser-based tool for analyzing pharmacovigilance (PV) line listings. Built for drug safety professionals who work with case data in Excel format.

**Privacy First:**
All data processing happens locally in your browser. No data is ever uploaded to any server.
This tool is designed with pharmaceutical data privacy in mind. Your sensitive case data never leaves your computer.

**Features**

📤 File Upload: Support for Excel (.xlsx, .xls) and CSV files
🔍 Global Search: Search across all columns instantly
📊 Advanced Filtering: Multi-select filters with smart date range detection
↕️ Sorting: Click any column header to sort ascending/descending
📥 Export: Download filtered results back to Excel

**Column Management**

👁️ Show/Hide Columns: Toggle column visibility
🔒 Freeze Columns: Keep important columns visible while scrolling
↔️ Reorder Columns: Drag and drop to rearrange
💾 Saved Views: Save and restore column configurations

**Data Quality (QC) Checks**

Built-in Rules: Pre-configured validation rules for common PV data issues
Custom Rules: Create your own validation rules with 12+ operators
Auto-Mapping: Automatically maps rules to your column names
Results View: See all flagged rows with one click

**Analysis Tools**

📈 Column Statistics: View data distribution, fill rates, top values with percentages
🔄 Duplicate Detection: Find duplicate rows based on selected columns
⚖️ Version Comparison: Compare two file versions to see added, removed, and modified cases

**Smart Date Filtering**

Auto-Detection: Automatically identifies date columns
Range Picker: Filter by date range instead of individual values
Quick Presets: Last 7/30/90 days, This year
Blank Handling: Option to include/exclude empty dates


**🚀 Quick Start**
Option 1: Use Online (Recommended)
Visit: https://yourusername.github.io/pv-line-listing-analyzer

Option 2: Run Locally
Download index.html from this repository
Open it in any modern web browser
That's it! No installation required.

Option 3: Self-Host
Clone this repository
Host the index.html file on any web server
Access via your server URL


**📖 User Guide**
Uploading Data

Click "Select Excel/CSV File" on the landing page
Choose your line listing file
Data loads instantly in the browser

Filtering Data

Text Columns: Click the filter icon (🔽) to see all unique values and select/deselect
Date Columns: Use the date range picker with From/To fields
Quick Presets: Use "Last 7 days", "Last 30 days", etc. for common ranges
Clear Filters: Click "Clear filters" button in the toolbar

Using QC Rules

Click "QC Rules" in the toolbar
Review built-in rules and enable/disable as needed
Map unmapped rules to your column names
Click "Run" to execute checks
Click "Show" to highlight flagged rows

Creating Custom QC Rules

Open QC Rules → Click "New"
Enter rule name and category
Select field, operator, and value
Save and run

Comparing Versions

Click "Compare" in the toolbar
Upload the previous version of your file
Select the key column (e.g., Case Number)
Click "Compare" to see:

Added: New cases in current file
Removed: Cases deleted from previous
Modified: Cases with changed values
Unchanged: Identical cases

Saving Views

Configure columns (show/hide, freeze, reorder)
Click "Views" → "Save Current"
Enter a name (e.g., "QC Review", "Medical Review")
Load saved views anytime from the Views menu


**🖥️ Browser Requirements**
BrowserMinimum VersionStatusChrome80+✅ Fully SupportedFirefox75+✅ Fully SupportedSafari13+✅ Fully SupportedEdge80+✅ Fully SupportedInternet ExplorerAny❌ Not Supported

**Requirements:**

JavaScript must be enabled
Internet connection required on first load (for CDN libraries)
Recommended: Desktop or tablet (mobile has limited support)



**Architecture**

Single HTML file (~30KB)
No build process required
All dependencies loaded from CDN
Zero server-side processing




**⚠️ Disclaimer**
This tool is for internal analysis purposes.

Not validated for regulated pharmacovigilance activities
Not intended for official regulatory submissions
Always use validated systems for compliance-critical work
Verify results independently before making decisions


**🤝 Contributing**
Contributions are welcome! Please feel free to submit issues or pull requests.


📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

**👤 Author**
Gaurav Kant Goel

LinkedIn: [https://www.linkedin.com/in/gauravkantgoel/]
GitHub: @gauravkantgoel


**🙏 Acknowledgments**

Built for the pharmacovigilance community
Inspired by daily challenges of working with Excel line listings
Thanks to all drug safety professionals working to keep patients safe


