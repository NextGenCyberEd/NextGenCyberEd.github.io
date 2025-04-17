# CLAUDE.md for Next Gen Cyber Ed Website

## Project Overview

Create a GitHub Pages website using Jekyll for a nonprofit organization called "Next Gen Cyber Ed" that focuses on bridging the gap between K-12 cybersecurity education and industry resources. The site will primarily document freely available resources for students and educators, starting with a Prompt Library for Large Language Models.

## Organization Details

**Mission**: At Next Gen Cyber Ed, we bridge the gap between K-12 cybersecurity education and industry resources, creating pathways for students to explore and succeed in cybersecurity careers.

We strengthen cybersecurity education by connecting educators and students with trusted resources, hands-on experiences, and industry partnerships. Our role as a facilitator ensures that both teachers and students have access to the best available tools and opportunities in the cybersecurity field.

## Site Structure Requirements

1. Create a Jekyll site with the following structure:
   - Homepage with mission statement and overview
   - About page
   - Mission page with detailed information
   - Resources section that includes the Prompt Library

2. For the Prompt Library, create a structure that documents:
   - Educational prompts (Study Guide Generator, Lesson Plan Creator, Feedback Formulator, Study Crew System)
   - Technical prompts (Code Explainer for Beginners and placeholders for future additions)

## Technical Requirements

1. Set up a basic Jekyll site with the Minima theme
2. Configure the site appropriately for GitHub Pages deployment
3. Create responsive navigation that works on mobile and desktop
4. Optimize the site for accessibility
5. Include appropriate metadata for SEO

## Specific Tasks

1. **Initialize and configure Jekyll**:
   - Create a new Jekyll site
   - Update _config.yml with appropriate site information
   - Configure for GitHub Pages deployment

2. **Create basic site structure**:
   - Create necessary directories (_layouts, _includes, _data, pages, resources, assets)
   - Set up navigation in _data/navigation.yml
   - Implement default layout templates

3. **Develop content pages**:
   - Create index.md for homepage
   - Create about.md, mission.md, and resources.md pages
   - Develop prompt library content with necessary subpages

4. **Styling and branding**:
   - Use a clean, professional design suitable for an educational nonprofit
   - Implement a color scheme focused on cybersecurity themes (blues, greens)
   - Create simple but effective CSS using SCSS in the _sass directory

5. **Implement basic SEO**:
   - Add appropriate meta tags
   - Create a sitemap.xml
   - Ensure proper heading structure for accessibility

## Content Details

### Prompt Library

The Prompt Library should be organized as follows:

**Educational Prompts**:
- Study Guide Generator: Creates detailed study guides with memory techniques, practice questions, and visual learning tools for any subject
- Lesson Plan Creator: Generates complete lesson plans with differentiated activities and assessment strategies for teachers
- Feedback Formulator: Helps educators create constructive, balanced feedback on student work with specific improvement strategies
- Study Crew System: Creates an interactive multi-agent learning experience with specialized coaches to help students with assignments

**Technical Prompts**:
- Code Explainer for Beginners: Transforms complex code into beginner-friendly explanations with visual metaphors and real-world examples

For each prompt, include:
1. A title
2. A description
3. The actual prompt template in a code block
4. Optional usage notes or examples

## Deployment Instructions

After building the site:
1. Initialize Git in the directory
2. Create a GitHub repository (either organization or user-based)
3. Push the code to GitHub
4. Configure GitHub Pages in the repository settings

## Additional Notes

- Keep the design clean and focused on content readability
- Add placeholder sections for future expansion
- Ensure all pages have proper navigation paths
- Include a contact option or link to the organization's GitHub repository
- Consider adding a blog section for future announcements about new resources