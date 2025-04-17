# CLAUDE.md for Next Gen Cyber Ed Website

## Project Overview

Create a GitHub Pages website using Jekyll with the Just the Docs theme for a nonprofit organization called "Next Gen Cyber Ed" that focuses on bridging the gap between K-12 cybersecurity education and industry resources. The site will primarily document freely available resources for students and educators, starting with a Prompt Library for Large Language Models.

## Organization Details

**Mission**: At Next Gen Cyber Ed, we bridge the gap between K-12 cybersecurity education and industry resources, creating pathways for students to explore and succeed in cybersecurity careers.

We strengthen cybersecurity education by connecting educators and students with trusted resources, hands-on experiences, and industry partnerships. Our role as a facilitator ensures that both teachers and students have access to the best available tools and opportunities in the cybersecurity field.

## Site Structure Requirements

1. Create a Jekyll site with the Just the Docs theme with the following structure:
   - Homepage with mission statement and overview
   - About page
   - Mission page with detailed information
   - Resources section that includes the Prompt Library

2. For the Prompt Library, create a structure that documents:
   - Educational prompts (Study Guide Generator, Lesson Plan Creator, Feedback Formulator, Study Crew System)
   - Technical prompts (Code Explainer for Beginners and placeholders for future additions)

## Technical Requirements

1. Set up Jekyll with the Just the Docs theme
2. Configure the site appropriately for GitHub Pages deployment
3. Create a responsive navigation menu
4. Optimize the site for accessibility
5. Include appropriate metadata for SEO

## Specific Tasks

1. **Initialize and configure Jekyll with Just the Docs**:
   - Create a new Jekyll site
   - Install and configure the Just the Docs theme
   - Update _config.yml with appropriate site information
   - Configure for GitHub Pages deployment

2. **Create basic site structure**:
   - Set up navigation using Just the Docs' built-in navigation system
   - Create the main menu structure
   - Implement proper page hierarchy for easy navigation

3. **Develop content pages**:
   - Create index.md for homepage
   - Create about.md, mission.md, and resources.md pages
   - Develop prompt library content with necessary subpages

4. **Styling and customization**:
   - Customize the Just the Docs theme to match Next Gen Cyber Ed branding
   - Set appropriate theme colors (consider cybersecurity-themed blues and greens)
   - Ensure mobile-friendly design

5. **Implement search and navigation features**:
   - Enable the built-in search functionality from Just the Docs
   - Set up proper page hierarchy for navigation
   - Create a logical content structure for easy information finding

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

## Just the Docs Theme Implementation

1. **Installation**:
   - Add the theme to your site's Gemfile: `gem "just-the-docs"`
   - Run `bundle install` to install the theme
   - Add the theme to your _config.yml: `theme: just-the-docs`

2. **Configuration**:
   - Set up the theme with appropriate color schemes and branding
   - Configure the search functionality
   - Set up navigation structure as per Just the Docs documentation

3. **Customization**:
   - Create a custom stylesheet in the _sass directory for any overrides
   - Set up appropriate callouts for important information
   - Use the theme's built-in features for code blocks, tables, and other elements

4. **Navigation Structure**:
   - Use the theme's parent/child page relationships for hierarchical navigation
   - Set proper page ordering using the `nav_order` front matter
   - Create appropriate categories for content organization

## Additional Notes

- Keep the design clean and focused on content readability
- Take advantage of Just the Docs' excellent documentation structure features
- Use the theme's built-in search functionality to make resources easily findable
- Ensure proper use of headings and structure for accessibility
- Include a contact option or link to the organization's GitHub repository
- Consider adding a callout on the homepage for quick access to key resources