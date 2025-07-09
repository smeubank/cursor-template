# Cursor AI Assistant Rules Template

A comprehensive template for configuring AI assistants in Cursor IDE with modern web development best practices.

## 🎯 Overview

This template provides a structured set of rules and guidelines for AI assistants working with modern web development projects. It includes coding standards, business logic patterns, feature development workflows, and comprehensive documentation organization.

**Perfect for:** TypeScript/Next.js projects, but adaptable to any modern web development stack.

## ⚙️ Cursor Configuration

This template uses Cursor's frontmatter configuration system to control when rules are applied:

### Always Applied Rules (`alwaysApply: true`)
These core rules are automatically loaded in every conversation:
- **`guidelines.mdc`** - Core LLM persona and project guidelines
- **`cursor.mdc`** - Main project navigation and context
- **`coding-guidelines.mdc`** - TypeScript and Next.js coding standards
- **`common-patterns.mdc`** - Reusable code patterns and conventions
- **`architecture.mdc`** - Project architecture and technology stack
- **`monitoring.mdc`** - Error tracking and performance monitoring

### Contextual Rules (Reference Documentation)
These files are loaded on-demand when relevant:
- **`feature-development.mdc`** - PRFAQ → PRD → GTM workflow
- **`business-logic.mdc`** - Domain-specific business rules
- **`llms/document-scopes.mdc`** - Documentation organization guide
- **`llms/documentation-style-guide.mdc`** - Writing standards

### 🔧 Customizing Configuration

To modify which rules are always applied:

1. **Edit frontmatter** in any `.mdc` file:
   ```markdown
   ---
   alwaysApply: true    # Always load this file
   ---
   ```
   or
   ```markdown
   ---
   title: [File Title]  # Load on-demand only
   ---
   ```

2. **Restart Cursor** for changes to take effect

3. **Consider context window** - too many always-applied files may impact performance

## 🚀 Quick Start

1. **Copy the template** to your project:
   ```bash
   # Option 1: Clone this repository
   git clone https://github.com/your-username/cursor-template.git
   cd cursor-template
   
   # Option 2: Download as ZIP and extract to your project
   ```

2. **Customize for your project**:
   ```bash
   # Copy the .cursor directory to your project root
   cp -r .cursor /path/to/your/project/
   ```

3. **Replace placeholder content**:
   - Update `[Your Project Name]` with your actual project name
   - Replace `[Your Company]` with your organization name
   - Update `[Your Name]` in LICENSE file with your name
   - Customize technology stack references
   - Update business logic examples with your domain

4. **Configure rule loading** (optional):
   - Review `alwaysApply` settings in `.cursor/rules/*.mdc` files
   - Adjust based on your project size and context window preferences

5. **Test with your AI assistant** in Cursor IDE

## 📂 Template Structure

```
.cursor/
├── rules/                     # Core AI assistant rules
│   ├── README.md             # Template overview and customization guide
│   ├── coding-guidelines.md  # TypeScript and framework standards
│   ├── business-logic.md     # Domain-specific business rules template
│   └── project-context.md    # Project-specific information template
└── project/                  # Project organization and documentation
    ├── README.md             # Project documentation guide
    ├── dir-name/             # Flexible documentation collection space
    │   └── README.md         # Organization instructions
    └── features/             # Feature development templates
        └── 001-template/     # PRFAQ → PRD → GTM → Implementation workflow
            ├── PRFAQ.md      # Problem definition and solution validation
            ├── PRD.md        # Product requirements document
            ├── GTM.md        # Go-to-market strategy
            └── IMPLEMENTATION.md # Technical implementation and PR description
```

## 🔧 Customization Guide

### 1. Project Information
Replace these placeholders throughout the files:
- `[Your Project Name]` → Your actual project name
- `[Your Company/Organization]` → Your organization name
- `[Your Backend Choice]` → Your database/backend technology
- `[Your UI Library]` → Your component library choice
- `[Your Monitoring Solution]` → Your error tracking service

### 2. Technology Stack
Update technology references in:
- `.cursor/rules/coding-guidelines.md` - Framework and language standards
- `.cursor/rules/project-context.md` - Development environment and tools
- `.cursor/rules/business-logic.md` - Database and API patterns

### 3. Business Logic
Customize the business logic template:
- Replace generic examples with your domain-specific patterns
- Update validation schemas with your data structures
- Modify workflow examples to match your business processes

### 4. Feature Development
Use the feature development templates:
- Copy `001-template/` to create new features: `002-your-feature-name/`
- Follow the PRFAQ → PRD → Implementation → GTM workflow
- Customize the templates with your specific processes

## 🎯 What's Included

### Core Features
- **TypeScript-first** coding standards and patterns
- **Next.js App Router** best practices and conventions
- **Database patterns** with error handling and monitoring
- **Component architecture** guidelines for scalable UI
- **Testing strategies** for comprehensive coverage
- **Performance optimization** patterns and monitoring
- **Security standards** for web applications
- **Accessibility compliance** guidelines (WCAG 2.1 AA)

### Development Workflow
- **Feature development** structured workflow (PRFAQ → PRD → GTM)
- **Code review** guidelines and checklists
- **Documentation standards** for maintainable projects
- **Error tracking** and performance monitoring setup
- **Deployment patterns** and environment management

### Project Organization
- **Monorepo support** with clear directory structures
- **Documentation organization** for complex projects
- **Team collaboration** guidelines and processes
- **Quality assurance** checklists and standards

## 🛠️ Supported Technologies

### Primary Stack (Template Default)
- **Framework:** Next.js 14+ with App Router
- **Language:** TypeScript with strict configuration
- **Database:** Supabase (PostgreSQL)
- **Styling:** Tailwind CSS
- **UI Library:** ShadCN/UI
- **Monitoring:** Sentry
- **Deployment:** Vercel

### Easily Adaptable To
- **Frontend:** React, Vue, Angular, Svelte
- **Backend:** Node.js, Python, Go, .NET
- **Database:** PostgreSQL, MySQL, MongoDB, Prisma
- **Styling:** CSS Modules, Styled Components, Emotion
- **Deployment:** AWS, GCP, Azure, Netlify

## 📋 Usage Examples

### For a SaaS Application
```bash
# Copy template
cp -r .cursor /path/to/saas-app/

# Customize for SaaS context
# - Update business logic for subscription management
# - Modify user roles and permissions
# - Add billing and payment processing patterns
```

### For an E-commerce Site
```bash
# Copy template
cp -r .cursor /path/to/ecommerce-site/

# Customize for e-commerce context
# - Update business logic for inventory management
# - Modify user flows for shopping and checkout
# - Add product catalog and order processing patterns
```

### For a Content Management System
```bash
# Copy template
cp -r .cursor /path/to/cms-project/

# Customize for CMS context
# - Update business logic for content workflows
# - Modify user roles for editors and admins
# - Add publishing and content approval patterns
```

## 🎨 Features

### Intelligent Code Assistance
- Context-aware suggestions based on your project patterns
- Consistent coding standards enforcement
- Business logic validation and best practices
- Performance optimization recommendations

### Comprehensive Documentation
- Clear guidelines for every aspect of development
- Feature development workflow templates
- Project organization and team collaboration guides
- Quality assurance and testing strategies

### Scalable Architecture
- Patterns that grow with your project
- Monorepo organization support
- Modular component architecture
- Performance and monitoring built-in

## 🤝 Contributing

We welcome contributions to improve this template!

### How to Contribute
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/improvement-name`
3. Make your changes (follow the existing documentation style)
4. Test with your AI assistant to ensure functionality
5. Submit a pull request with a clear description of improvements

### Areas for Contribution
- Additional technology stack templates
- More business domain examples
- Enhanced development workflow patterns
- Documentation improvements
- Bug fixes and optimizations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by modern web development best practices
- Built for the Cursor IDE AI assistant ecosystem
- Thanks to the developer community for feedback and contributions

## 📞 Support

- **Issues:** Use GitHub issues for bug reports and feature requests
- **Discussions:** Use GitHub discussions for questions and community support
- **Documentation:** Check the `.cursor/rules/README.md` for detailed customization instructions

---

**Happy coding with AI assistance!** 🚀 