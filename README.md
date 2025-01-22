# Obsidian Persian Font and Smart RTL/LTR Toggle

This repository provides a solution for handling dynamic Right-to-Left (RTL) and Left-to-Right (LTR) text directions in Obsidian. By default, Obsidian either supports a fixed language (English or Persian) or enforces a single text direction (RTL or LTR). However, with this solution, the text direction will automatically adjust based on the language content in a single note. Additionally, it applies different fonts for English and Persian content.

---

## How to Implement Smart RTL and LTR Text Direction:

1. **Locate the Snippets Folder**: Navigate to the following directory:
    
    php
    
    CopyEdit
    
    `<LOCATIONVALUT>\.obsidian\snippets`
    
2. **Clone the Repository**: Clone the contents of this repository:
    
    arduino
    
    CopyEdit
    
    `https://github.com/sepehr-safaeian/Obsidian-PersianFont/`
    
3. **Refresh Snippets**: Go to: `Settings > Appearance > CSS Snippets` Click the **Refresh** button to ensure the new snippets are loaded.
    

---

## How to Apply Font Customization:

1. **Access Font Settings**: Go to: `Settings > Appearance > Fonts`
    
2. **Manage Fonts**: Click **Manage** for both the `Interface Font` and `Text Font`.
    
3. **Select Fonts**:
    
    - Choose an **English font** (e.g., "Arial", "Times New Roman").
    - Choose a **Persian font** (e.g., "Vazir").

By following these steps, the system will intelligently apply the appropriate text direction (RTL for Persian and LTR for English) and use the correct fonts for each language.

---

## Explanation

This customization ensures seamless support for both Persian and English content within Obsidian, optimizing the reading and editing experience. Persian text will automatically be aligned to the right (RTL), while English text will be left-aligned (LTR), without requiring manual adjustments.