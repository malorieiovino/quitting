# 🌱 Sobriety Streak Tracker

A beautiful, interactive sobriety tracker that you can embed in Notion, personal websites, or other platforms to celebrate your journey.


## ✨ Features

- 🔢 Track days since your sobriety start date
- 📊 Visualize progress with an animated progress bar
- 🏆 Unlock achievement badges at key milestones
- 🎉 Celebration animations when you hit milestones
- 💬 Motivational quotes that change on each visit
- 📱 Fully responsive design for all devices
- 💾 Data saved locally in your browser

## 🚀 Quick Setup 

### 1. Fork This Repo

1. Click the "Fork" button at the top of this GitHub repository
2. This creates your own copy of the tracker that you can customize

### 2. Enable GitHub Pages

1. In your forked repository, go to "Settings" > "Pages"
2. Under "Source", select "Deploy from a branch"
3. Select the "main" branch and "/ (root)" folder
4. Click "Save"
5. Wait a minute or two for GitHub to publish your site
6. You'll see a message with your site URL (usually `https://yourusername.github.io/sobriety-tracker/`)

### 3. Embed in Notion

#### Method 1: Basic Embed
1. In your Notion page, type `/embed` 
2. Select "Embed" from the menu
3. Paste your GitHub Pages URL
4. Click "Embed link"

#### Method 2: Custom Size (More Advanced)
1. In your Notion page, type `/code` and select "Code"
2. Choose "HTML" as the language
3. Paste the following code (replace `YOUR_URL` with your GitHub Pages URL):
   ```html
   <iframe
     src="YOUR_URL"
     style="border: none; width: 100%; height: 500px;"
   ></iframe>
   ```
4. Adjust the height value (500px) as needed

### 4. Embed in Other Platforms

#### Personal Website
Add this HTML to any page on your website:
```html
<iframe
  src="YOUR_GITHUB_PAGES_URL"
  style="border: none; width: 100%; height: 500px;"
></iframe>
```

#### WordPress
1. Add a "Custom HTML" block
2. Paste the iframe code above
3. Replace `YOUR_GITHUB_PAGES_URL` with your tracker URL

#### Obsidian
Use the Obsidian "iFrame" plugin to embed your tracker.

## 🎨 Customization

Want to make the tracker your own? Here are some easy customizations:

### Changing Colors
In the HTML file, find the `:root` section at the top of the CSS and modify the color variables:
```css
:root {
    --primary: #8e44ad;    /* Main color */
    --secondary: #9b59b6;  /* Secondary color */
    --accent: #3498db;     /* Accent color */
    /* ... other colors ... */
}
```

### Adding More Milestones
Find the `milestones` array in the JavaScript and add your own:
```javascript
const milestones = [
    { days: 1, message: "First day complete! 🎉" },
    // Add your own milestones here
    { days: 100, message: "100 days! You're incredible! 🌟" },
];
```

### Adding More Quotes
Find the `quotes` array in the JavaScript to add your own motivational messages.

## 🔒 Privacy

All data is stored locally in your browser using localStorage. Nothing is transmitted to any server, ensuring your privacy.

## 🤝 Sharing

Feel free to share this tracker with friends, support groups, or anyone who might benefit from it. The more people we help, the better!

## 📱 Using on Multiple Devices

Since the data is stored locally in your browser, your streak won't automatically sync between devices. If you want to use the tracker on multiple devices:

1. Set the same start date on each device
2. Or consider setting up a simple backend if you're technical (beyond the scope of this README)

## 🙏 Support

If this tracker helps you on your journey, consider:
- Sharing it with others who might benefit
- Starring this repository on GitHub
- Contributing enhancements or reporting issues

Stay strong on your journey! 💪
