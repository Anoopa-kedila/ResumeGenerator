# Resume Generator - JobHunt Agent

An intelligent job hunting assistant that automates resume customization, cover letter generation, and interview preparation for targeted job applications.

## Overview

This project is designed to streamline the job application process by automating analysis of job descriptions, identifying skills gaps, customizing resumes and cover letters, and generating interview preparation materials.

## Key Files

- **`jobhuntagent.md`** - Agent configuration and workflow definitions for VS Code Copilot integration
- **`MASTER CAREER PROFILE.txt`** - Your comprehensive work experience, skills, achievements, and background
- **`resume template.txt`** - Base resume template in LaTeX format for customization

## Workflow (6-Step Process)

### Step 1: Job Analysis
Analyzes job descriptions to identify:
- Top 15 keywords/skills by importance
- Required vs. preferred qualifications
- Experience level requirements
- Key responsibilities
- Company culture indicators
- ATS optimization keywords

### Step 2: Skills Gap Analysis
Evaluates your qualifications against job requirements:
- Skills match analysis
- Experience alignment
- Prioritized action plans
- Transferable skills mapping
- Competitive advantages
- Quick wins

### Step 3: Resume Customization
Creates ATS-optimized resume tailored to:
- Professional summary aligned with role
- Prioritized skills sections
- Keyword-optimized experience bullets
- Education and certifications
- LaTeX formatted for professional output

### Step 4: Resume Review & Optimization
Critical review covering:
- First impression analysis
- Content analysis
- ATS optimization score
- Readability assessment
- Improvement suggestions
- Competitive positioning

### Step 5: Cover Letter Generation
Personalized cover letter (250-300 words) including:
- Compelling opening with company knowledge
- Achievement-focused body paragraphs
- Cultural fit demonstration
- Clear call to action

### Step 6: Interview Preparation
Comprehensive interview prep materials:
- 10 behavioral questions with STAR method frameworks
- Technical questions if applicable
- Company research questions
- Negotiation strategies

## Usage

1. **Set up your profile**: Update `MASTER CAREER PROFILE.txt` with your current experience and skills
2. **Add job description**: Copy the job description you're targeting
3. **Run analysis**: Use the `jobhuntagent.md` workflow in VS Code Copilot Chat
4. **Follow 6-step process**: Execute each step sequentially to build your application package
5. **Output**: Files are generated with naming convention: `[output_type]_[company_name].txt/tex`

## Output Files

- `job_analysis_[company].txt` - Detailed job analysis
- `skills_gap_[company].txt` - Skills assessment report
- `resume_[company].tex` - Customized LaTeX resume
- `resume_review_[company].txt` - Resume optimization feedback
- `cover_letter_[company].txt` - Customized cover letter
- `interview_prep_[company].txt` - Interview preparation materials

## Integration with VS Code

1. Copy `jobhuntagent.md` to your `.vscode/` folder or use it as a custom agent
2. Reference your `MASTER CAREER PROFILE.txt` and `resume template.txt` in prompts
3. Follow the step-by-step prompts provided in the agent

## Customization

Edit the following files to personalize the workflow:
- `MASTER CAREER PROFILE.txt` - Your professional background
- `resume template.txt` - Your LaTeX resume template
- `jobhuntagent.md` - Workflow and prompt templates (if extending)

## Requirements

- VS Code with GitHub Copilot extension
- LaTeX knowledge (for resume customization)
- Job descriptions in text format

## Tips for Best Results

1. Keep your master career profile comprehensive and up-to-date
2. Use exact keywords from job descriptions in resume customization
3. Quantify all achievements when possible
4. Tailor cover letters to company-specific details
5. Practice STAR method answers before interviews

## Target Roles

Designed for targeting:
- **Domain**: AI-focused roles
- **Stack**: C++, WPF, Windows desktop systems  
- **Level**: Mid to Senior positions
- **Compensation**: 35-50 LPA

---

**Created by**: JobHunt Agent automated workflow  
**Last Updated**: June 2026
