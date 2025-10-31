# CV Builder - LaTeX Resume Generator 🚀

A simple repository for creating professional CV/Resume using LaTeX with AI automation.

## 📁 Project Structure

```
cv/
├── MYINFO.md          # Your personal information
├── INSTRUCTION.md     # Format and style guidelines
├── EXAMPLE.md         # CV template examples 
├── IMPLEMENT.md       # Implementation instructions
├── cv.tex             # Main LaTeX file
├── basecv.tex         # Basic LaTeX template you want to create in cv.tex
├── cv.pdf             # Final PDF output
└── README.md          # This file
```

## 🛠️ How to Use

### 1. Update Personal Information
Edit the `MYINFO.md` file with your information:
- Personal details (name, email, phone, LinkedIn, GitHub)
- Education
- Work experience
- Skills
- Projects (optional)

### 2. Customize Format (Optional)
- `INSTRUCTION.md`: Edit rules for format, tone, and layout
- `EXAMPLE.md`: Add template examples for structure

### 3. Generate CV
There are 2 ways to create your CV:

#### Method 1: Using AI Assistant (Recommended)
```bash
# In Trae AI or Claude Code
# Simply say: "implement IMPLEMENT.md"
```

#### Method 2: Manual LaTeX Compilation
```bash
# Install LaTeX (if not already installed)
sudo apt-get install texlive-full

# Compile CV
pdflatex cv.tex

# Output: cv.pdf
```

## 🎯 Features

- ✅ **ATS-Optimized**: Format optimized for Applicant Tracking Systems
- ✅ **Professional Layout**: Clean, modern design
- ✅ **AI-Powered**: Automatically extract and format information from MYINFO.md
- ✅ **Customizable**: Easy to change content and style
- ✅ **LaTeX Quality**: High-quality PDF output
- ✅ **Version Control**: Track changes with Git

## 🚀 Quick Start

1. **Clone this repository**
2. **Update `MYINFO.md`** with your information
3. **Run AI assistant** or compile manually
4. **Enjoy your professional CV!** 🎉

## 📝 Development Tips

### Efficient Workflow:
```bash
# 1. Update info
vim MYINFO.md

# 2. Quick compile check
pdflatex cv.tex

# 3. Preview
# Open cv.pdf to view results

# 4. Iterate
# Repeat until satisfied
```

### Customization Ideas:
- Add new sections in `cv.tex`
- Change color scheme
- Adjust spacing and margins
- Add icons or graphics

### AI Assistant Commands:
```
"Add Projects section"
"Remove Publications section" 
"Fix dates according to MYINFO"
"Compile CV to PDF"
"Open preview"
```

## 🎨 Customization

### Change Colors:
```latex
% In cv.tex, find and edit:
\definecolor{accent}{HTML}{0066CC}  % Primary color
```

### Add New Section:
```latex
\section{New Section}
\begin{onecolentry}
    Your content here
\end{onecolentry}
```

### Font and Spacing:
```latex
% Change font size
\documentclass[10pt]{article}

% Adjust margins
\geometry{margin=0.5in}
```

## 🔧 Troubleshooting

### LaTeX Errors:
```bash
# View log file
cat cv.log

# Clean build files
rm *.aux *.log *.out

# Rebuild
pdflatex cv.tex
```

### Missing Packages:
```bash
# Install missing LaTeX packages
sudo apt-get install texlive-latex-extra
sudo apt-get install texlive-fonts-recommended
```

## 📚 Resources

- [LaTeX Documentation](https://www.latex-project.org/help/documentation/)
- [Overleaf Templates](https://www.overleaf.com/latex/templates)
- [ATS Resume Tips](https://www.jobscan.co/ats-resume-guide)

## 🤝 Contributing

Feel free to:
- Add new templates
- Improve AI automation
- Fix bugs
- Share your customizations

## 📄 License

MIT License - Feel free to use and customize!

---

**Happy coding and good luck with job hunting! 🚀✨**