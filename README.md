# ResumeMatch - AI Resume Customizer

A free, AI-powered web application that automatically customizes your resume to match any job description in seconds.

## Features

- **⚡ Instant Optimization** - Match any job description in 10 seconds with no manual editing needed
- **🎯 ATS-Friendly** - Optimized for applicant tracking systems to ensure your resume reaches human reviewers
- **🔒 Privacy Focused** - End-to-end encrypted with no data storage or selling
- **📊 Match Scoring** - See your compatibility score and which skills stand out most
- **📄 Multiple Formats** - Upload resume in PDF, Word, or text format

## How It Works

1. Upload your resume (PDF, Word, or text file)
2. Paste the job description you're applying for
3. Click "Optimize my resume" and let AI do the work
4. Review your customized resume with match score
5. Download your optimized resume

## Getting Started

### Requirements
- Modern web browser
- Anthropic API key (for Claude AI integration)

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/inamigos.git
cd inamigos
```

2. Open `index.html` in your web browser
```bash
# On macOS
open index.html

# On Windows
start index.html

# Or simply drag and drop index.html into your browser
```

3. The application requires an API key for the Claude AI service. You'll need to configure this in the application.

## API Integration

This application uses the Anthropic Claude API for AI-powered resume optimization. 

To set up:
1. Get your API key from [Anthropic](https://console.anthropic.com/)
2. The application will prompt you for the API key when needed

## How Resume Optimization Works

The AI analyzer:
- Extracts key requirements and skills from the job description
- Identifies relevant experience from your resume
- Reorders content to highlight most relevant experience first
- Tailors language to match the job posting
- Generates a match score showing alignment with the position

## Privacy & Security

- ✅ No server-side storage of your data
- ✅ Encrypted communication with AI service
- ✅ No tracking or analytics
- ✅ Your resume is never stored or sold

## File Structure

```
inamigos/
├── index.html          # Main application file
├── README.md           # This file
├── LICENSE             # MIT License
└── .gitignore          # Git ignore rules
```

## Technologies Used

- HTML5
- CSS3 (Modern Grid & Flexbox)
- Vanilla JavaScript
- Anthropic Claude AI API

## License

MIT License - see LICENSE file for details

## Support

For issues, questions, or suggestions, please open an issue on GitHub.

## Roadmap

- [ ] Add multiple resume format templates
- [ ] Batch optimization for multiple job applications
- [ ] Resume analytics and improvement suggestions
- [ ] Integration with LinkedIn profiles
- [ ] Cover letter generation

---

Made with ❤️ for job seekers everywhere
