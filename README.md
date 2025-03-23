# Sobriety Streak Tracker

A simple, embeddable web app to track your sobriety streak that you can integrate with Notion.

## Features

- 🔢 Track days since your sobriety start date
- 🏆 Display milestones (1 day, 3 days, 1 week, etc.)
- 📊 Track your longest streak and total days clean
- 📝 Edit your start date or reset if needed
- 💾 Local storage for data persistence
- 📱 Mobile-friendly responsive design

## Setup Instructions

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account if needed)
2. Click the "+" icon in the top-right corner and select "New repository"
3. Name your repository (e.g., "sobriety-tracker")
4. Make sure the repository is set to "Public" (required for GitHub Pages)
5. Click "Create repository"

### 2. Upload the Files

1. Click "uploading an existing file" link on the repository page
2. Drag and drop the HTML file or click to select it from your computer
3. Enter a commit message like "Initial commit" 
4. Click "Commit changes"

### 3. Enable GitHub Pages

1. Go to your repository's "Settings" tab
2. Scroll down to the "GitHub Pages" section
3. Under "Source", select "main" branch
4. Click "Save"
5. GitHub will provide a URL where your site is published (usually https://yourusername.github.io/repository-name/)

### 4. Embed in Notion

There are two main ways to embed your tracker in Notion:

#### Option 1: Embed using the /embed command
1. In your Notion page, type `/embed` 
2. Select "Embed"
3. Paste the URL to your GitHub Pages site
4. Click "Embed link"

#### Option 2: Create an iframe (for more customization)
1. In your Notion page, type `/code` and select "Code"
2. Choose "HTML" as the language
3. Paste the following code, replacing `YOUR_URL` with your GitHub Pages URL:
   ```html
   <iframe
     src="YOUR_URL"
     style="border: none; width: 100%; height: 400px;"
   ></iframe>
   ```
4. Save the block

## Usage

- The tracker will automatically calculate your streak based on the start date
- Use the "Edit Start Date" button to set or change your sobriety start date
- If you need to reset your streak, use the "Reset Streak" button
- All data is stored locally in your browser (it won't sync between devices)

## Customization

You can customize the tracker by editing the HTML file:
- Change colors in the CSS section
- Add or modify milestone messages
- Adjust the layout and design

## Privacy Note

This tracker stores data only in your browser's local storage. No data is sent to any server, ensuring your privacy.
