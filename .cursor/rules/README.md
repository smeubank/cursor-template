# Cursor AI Assistant Rules Template

This template provides a comprehensive set of rules and guidelines for AI assistants working with modern web development projects.

To be honest a lot of it is still probably better suited to a JS meta framework type project, and entirely overkill. But it is fairly comprehensive based on setups I have seen in different projects, and my own experimentation.

## 🎯 Template Structure

This template is designed to be customized for your specific project. Replace placeholder values and examples with your actual project details.

### Key Files to Customize:

- `always_applied_workspace_rules.md` - Core coding standards and patterns
- `project-context.md` - Your specific project information
- `business-logic.md` - Your domain-specific business rules
- `feature-development.md` - Your feature development workflow

## 🔧 Customization Instructions

### 1. Replace Project-Specific Information
- Update company/project names throughout
- Replace example business logic with your domain
- Update technology stack references
- Customize color schemes and branding

### 2. Configure Development Environment
- Update environment variable examples
- Modify deployment configuration
- Adjust monitoring and error tracking setup
- Customize database schema examples

### 3. Adapt Business Logic
- Replace example business rules with your domain logic
- Update API integration patterns
- Modify validation schemas
- Customize user workflows

## 🛠️ Technology Stack (Template)

The template assumes:
- **Framework**: Next.js 14+ with TypeScript
- **Database**: Supabase (PostgreSQL)
- **Monitoring**: Sentry
- **UI Library**: ShadCN/UI
- **Styling**: Tailwind CSS

Modify these based on your actual stack.

## 📚 Documentation Structure

The template includes:
- **Coding Guidelines** - TypeScript and framework standards
- **Common Patterns** - Reusable code patterns
- **Business Logic** - Domain-specific rules (customize this)
- **Feature Development** - PRFAQ → PRD → Implementation workflow
- **Monitoring** - Error tracking and performance monitoring

## 🚀 Getting Started

1. Copy this template to your project's `.cursor/rules/` directory
2. Customize the files with your project-specific information
3. Remove or replace all placeholder content
4. Test the rules with your AI assistant

## 📋 Customization Checklist

- [ ] Replace all company/project names
- [ ] Update technology stack references
- [ ] Customize business logic examples
- [ ] Update environment variable examples
- [ ] Modify color schemes and branding
- [ ] Adjust file paths and directory structures
- [ ] Update API integration examples
- [ ] Customize database schema examples
- [ ] Test AI assistant behavior with your customizations

## 🔒 Security Notes

- Remove any sensitive information before committing
- Use environment variables for secrets
- Avoid hardcoding API keys or personal information
- Review all examples for business-sensitive details 