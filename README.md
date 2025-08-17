# 🌐 Website Cloner with AI

A powerful **AI-driven website cloning tool** that creates pixel-perfect replicas of any website using modern web technologies including **Tailwind CSS**, **Puppeteer**, and **Groq AI**.

## ✨ Features

### 🎯 **Pixel-Perfect Cloning**
- **Complete Visual Replication** - Captures exact appearance, layout, and styling
- **Deep CSS Analysis** - Extracts all computed styles and positioning data
- **Asset Management** - Downloads all images, CSS files, JavaScript, and fonts
- **Modern Tech Stack** - Built with Tailwind CSS for maintainable code

### 🤖 **AI-Powered Intelligence**
- **Groq AI Integration** - Uses Llama3-70B model for intelligent analysis
- **Automated Workflow** - AI orchestrates the entire cloning process
- **Smart Asset Organization** - Intelligent file naming and structure
- **Error Handling** - Robust error recovery and retry mechanisms

### 🛠️ **Advanced Web Technologies**
- **Puppeteer** - Headless Chrome for complete website rendering
- **Cheerio** - Server-side jQuery for HTML parsing
- **Tailwind CSS** - Utility-first CSS framework integration
- **Responsive Design** - Mobile-first approach with breakpoint support

## 🚀 Quick Start

### Prerequisites
- **Node.js** (v16 or higher)
- **npm** or **yarn**
- **Groq API Key** (free from [groq.com](https://groq.com))

### Installation

1. **Clone or Download** the script
```bash
# Save the script as website-cloner.js
```

2. **Install Dependencies**
```bash
npm init -y
npm install dotenv groq-sdk axios puppeteer cheerio
```

3. **Setup Environment Variables**
```bash
# Create .env file
echo "GROQ_API_KEY=your_groq_api_key_here" > .env
```

4. **Get Your Groq API Key**
   - Visit [console.groq.com](https://console.groq.com)
   - Sign up for a free account
   - Generate an API key
   - Add it to your `.env` file

### Usage

#### **Clone Any Website**
```bash
node website-cloner.js "Clone https://example.com"
```

#### **General AI Assistant**
```bash
node website-cloner.js "Get GitHub info for username torvalds"
node website-cloner.js "Execute command: ls -la"
```

#### **Custom Commands**
```bash
node website-cloner.js "Create a pixel-perfect clone of https://tailwindcss.com"
node website-cloner.js "Execute command: ls -la"
```

## 📁 Project Structure

After cloning a website, you'll get:

```
website-clone/
├── index.html          # Main HTML with Tailwind CSS setup
├── styles.css          # Pixel-perfect CSS + Tailwind utilities
├── script.js           # Enhanced JavaScript functionality
├── assets/             # All downloaded resources
│   ├── *.jpg, *.png    # Website images
│   ├── *.css           # External stylesheets
│   ├── *.js            # External JavaScript files
│   └── *.woff, *.ttf   # Web fonts
└── README.md           # Comprehensive project guide
```

## 🔧 Available Tools

### **Website Cloning Tools**
- `analyzeWebsiteWithPuppeteer(url)` - Deep website analysis with Puppeteer
- `fetchWebsiteContent(url)` - Raw HTML content retrieval
- `parseHTMLWithCheerio(html)` - HTML structure parsing
- `generateCompleteHTML(data)` - Complete HTML generation with Tailwind
- `generateCompleteCSS(data)` - Pixel-perfect CSS with utilities
- `extractAndDownloadAssets(data)` - Asset download and organization
- `createProjectREADME(data)` - Comprehensive documentation

### **General Utility Tools**
- `getGithubUserInfoByUsername(user)` - GitHub user data
- `executeCommand(cmd)` - System command execution
- `writeFile(path, content)` - File creation
- `createDirectory(path)` - Directory creation
- `downloadAsset(url, path)` - Asset downloading

## 🎨 Tailwind CSS Integration

### **Modern Development Approach**
- **Utility-First CSS** - Rapid development with utility classes
- **Responsive Design** - Mobile-first breakpoint system
- **Dark Mode Support** - Automatic theme detection
- **Custom Configuration** - Extended color palettes and fonts

### **Generated Features**
```html
<!-- Automatic Tailwind CSS setup -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Custom Tailwind configuration -->
<script>
tailwind.config = {
  darkMode: 'class',
  theme: {
    extend: {
      colors: {
        primary: 'var(--primary-color, #3b82f6)',
        secondary: 'var(--secondary-color, #64748b)'
      }
    }
  }
}
</script>
```

### **Responsive Utilities**
- `sm:` - 640px and up
- `md:` - 768px and up  
- `lg:` - 1024px and up
- `xl:` - 1280px and up

## 🤖 AI Workflow

The AI follows a structured process:

1. **START** - Acknowledges the request
2. **THINK** - Plans the approach
3. **TOOL** - Executes necessary tools
4. **OBSERVE** - Reviews results
5. **OUTPUT** - Provides final result

### **Website Cloning Process**
```
1. Deep analysis with Puppeteer
2. Extract all computed styles
3. Download all assets
4. Generate Tailwind-based HTML
5. Create pixel-perfect CSS
6. Enhance with JavaScript
7. Generate documentation
```

## 🔍 Technical Details

### **Deep Analysis Capabilities**
- **Complete DOM Inspection** - Every element analyzed
- **Computed Styles Extraction** - All CSS properties captured
- **Asset Discovery** - Images, fonts, scripts identified
- **Layout Preservation** - Exact positioning maintained
- **Interactive Elements** - Forms, buttons, navigation preserved

### **Browser Compatibility**
- **Modern Browsers** - Chrome 90+, Firefox 88+, Safari 14+
- **Mobile Support** - iOS Safari 14+, Chrome Mobile 90+
- **Progressive Enhancement** - Graceful degradation

### **Performance Optimizations**
- **CDN Integration** - Tailwind CSS from CDN
- **Asset Optimization** - Efficient loading strategies
- **Responsive Images** - Proper sizing and formats
- **Minimal JavaScript** - Clean, focused functionality

## 🛡️ Error Handling

### **Robust Recovery**
- **Network Timeouts** - Automatic retry mechanisms
- **Large Content** - Message truncation for API limits
- **Missing Assets** - Graceful fallback handling
- **Malformed HTML** - Parser error recovery

### **Debug Features**
- **Verbose Logging** - Detailed operation tracking
- **Progress Indicators** - Real-time status updates
- **Error Messages** - Clear problem identification
- **File Verification** - Creation success confirmation

## 📚 Examples

### **Clone a Modern Website**
```bash
node website-cloner.js "Create a pixel-perfect clone of https://stripe.com"
```

**Output:**
- Complete Stripe.com replica
- All animations and interactions
- Tailwind CSS utilities
- Mobile-responsive design
- Dark mode support

### **Clone a Portfolio Site**
```bash
node website-cloner.js "Clone https://portfolio-example.com with Tailwind"
```

**Features:**
- Exact visual replication
- All images downloaded
- Custom CSS preserved
- Modern code structure

### **General AI Tasks**
```bash
# GitHub user info
node website-cloner.js "Get GitHub stats for username octocat"

# System commands
node website-cloner.js "Execute command: pwd"
```

## 🚀 Viewing Your Clone

### **Option 1: Direct Browser**
```bash
cd website-clone
# Double-click index.html
```

### **Option 2: Local Server (Recommended)**
```bash
cd website-clone
python -m http.server 8000
# Visit: http://localhost:8000
```

### **Option 3: Live Server**
```bash
# Install globally
npm install -g live-server

cd website-clone
live-server
```

## 🎯 Advanced Usage

### **Custom Styling**
```html
<!-- Add custom Tailwind classes -->
<div class="bg-gradient-to-r from-blue-500 to-purple-600 p-8 rounded-xl shadow-2xl">
  <!-- Your content -->
</div>
```

### **Dark Mode Toggle**
```javascript
// Toggle dark mode
document.documentElement.classList.toggle('dark');
```

### **Responsive Customization**
```html
<!-- Mobile-first responsive design -->
<div class="text-sm md:text-base lg:text-lg xl:text-xl">
  Responsive text
</div>
```

## 🔒 Environment Variables

```bash
# .env file
GROQ_API_KEY=your_api_key_here

# Optional configurations
PUPPETEER_HEADLESS=true
DOWNLOAD_TIMEOUT=30000
MAX_CONCURRENT_DOWNLOADS=5
```

## 🐛 Troubleshooting

### **Common Issues**

**API Key Error:**
```bash
Error: GROQ_API_KEY not found
# Solution: Check your .env file
```

**Puppeteer Issues:**
```bash
npm install puppeteer
# Or use system Chrome
export PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true
```

**Memory Issues:**
```bash
node --max-old-space-size=4096 website-cloner.js "your command"
```

**Network Timeouts:**
- Check internet connection
- Try with simpler websites first
- Increase timeout values

### **Debug Mode**
```bash
DEBUG=* node website-cloner.js "your command"
```

## 📈 Performance Tips

### **Optimization Strategies**
- **Start with Simple Sites** - Test with basic websites first
- **Check Network Speed** - Faster internet = faster cloning
- **Use SSD Storage** - Faster file operations
- **Close Other Apps** - More RAM for processing

### **Best Practices**
- **Respect robots.txt** - Check site's crawling policies
- **Rate Limiting** - Don't overwhelm target servers
- **Legal Compliance** - Ensure proper usage rights
- **Attribution** - Credit original creators

## 🤝 Contributing

### **Feature Requests**
- Open GitHub issues
- Describe use cases
- Provide example URLs
- Suggest improvements

### **Bug Reports**
- Include full error messages
- Provide reproduction steps
- Share problematic URLs (if public)
- Mention your environment

## 📄 License

This project is for **educational and development purposes**. Please respect:
- Website terms of service
- Copyright restrictions
- Privacy policies
- Legal requirements

## 🌟 Acknowledgments

### **Technologies Used**
- **[Groq](https://groq.com)** - AI inference platform
- **[Puppeteer](https://pptr.dev)** - Browser automation
- **[Tailwind CSS](https://tailwindcss.com)** - Utility-first CSS
- **[Cheerio](https://cheerio.js.org)** - Server-side jQuery
- **[Axios](https://axios-http.com)** - HTTP client

### **Inspiration**
- Modern web development practices
- AI-assisted development workflows
- Pixel-perfect design replication
- Developer experience optimization

---

**Created with ❤️ using AI-powered automation**

**Happy Cloning! 🎉**
