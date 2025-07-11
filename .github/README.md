# GitHub Copilot Customization Template

This repository serves as a template for GitHub Copilot customizations across all projects. It provides a modular and reusable structure for instructions, prompts, and chat modes.

## 📁 Structure

```
.github/
├── copilot-instructions.md          # Main instructions file
├── prompts/                         # Reusable prompt templates
│   ├── code-review.prompt.md
│   ├── testing-strategy.prompt.md
│   ├── documentation.prompt.md
│   ├── project-specific.prompt.md
│   ├── frontend/
│   │   ├── react.prompt.md
│   │   └── nextjs.prompt.md
│   ├── backend/
│   │   ├── nodejs.prompt.md
│   │   └── dotnet.prompt.md
│   ├── cloud/
│   │   └── azure.prompt.md
│   └── mobile/
│       └── react-native.prompt.md
├── chatmodes/                       # Custom chat modes
└── instructions/                    # Additional instruction files
```

## 🚀 Usage

### 1. Copy to New Repository
When creating a new repository, copy the entire `.github` folder structure.

### 2. Customize for Project
- Update `project-specific.prompt.md` with project details
- Include only relevant technology prompts
- Add custom chat modes if needed

### 3. Maintain Consistency
- Keep base instructions consistent across projects
- Update template when adding new patterns
- Share improvements back to this template

## 🎯 Features

### Modular Design
- **Base Instructions**: Core principles and workflows
- **Technology Prompts**: Specific guidelines for different tech stacks
- **Project Overrides**: Customizations for specific projects

### Comprehensive Coverage
- **Languages**: JavaScript, TypeScript, C#, Python, Java, Go
- **Frameworks**: React, Next.js, Node.js, .NET, React Native
- **Cloud**: Azure, AWS, GCP
- **Practices**: Testing, Security, Performance, Documentation

### Production-Ready
- Security best practices
- Performance optimization
- Code quality standards
- Testing strategies

## 📚 Resources

- [GitHub Copilot Customization Docs](https://code.visualstudio.com/docs/copilot/copilot-customization)
- [Awesome Copilot Repository](https://github.com/github/awesome-copilot)
- [VS Code Chat Modes](https://code.visualstudio.com/docs/copilot/chat/chat-modes)

## 🔄 Updates

This template should be regularly updated with:
- New technology patterns
- Improved best practices
- Community feedback
- Latest GitHub Copilot features

## 💡 Tips

1. **Start Simple**: Begin with base instructions and add technology-specific prompts as needed
2. **Stay Current**: Regular updates ensure best practices remain relevant
3. **Share Learnings**: Contribute improvements back to the template
4. **Test Thoroughly**: Validate customizations with real development scenarios
