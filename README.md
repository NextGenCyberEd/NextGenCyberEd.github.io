# Next Gen Cyber Ed Website

This repository contains the source code for the Next Gen Cyber Ed website, a nonprofit organization dedicated to bridging the gap between K-12 cybersecurity education and industry resources.

## About the Project

The Next Gen Cyber Ed website is built using [Jekyll](https://jekyllrb.com/), a static site generator, and is hosted on [GitHub Pages](https://pages.github.com/). The site serves as a hub for freely available resources for students and educators interested in cybersecurity.

## Site Structure

- Homepage: Overview and mission statement
- About: Information about the organization
- Mission: Detailed information about the organization's goals
- Resources: Collection of educational resources
  - Prompt Library: A collection of educational and technical prompts for large language models

## Setup Instructions

### Prerequisites

- Ruby (version 2.7.0 or higher)
- RubyGems
- GCC and Make

### Local Development

1. Clone the repository:
   ```
   git clone https://github.com/NextGenCyberEd/nextgencybered.github.io.git
   cd nextgencybered.github.io
   ```

2. Install dependencies:
   ```
   bundle install
   ```

3. Run the development server:
   ```
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

## Adding Content

### Creating a New Page

1. Create a new Markdown file in the root directory or in a subdirectory
2. Add the following front matter at the top of the file:
   ```yaml
   ---
   layout: page
   title: Your Page Title
   permalink: /your-page-url/
   ---
   ```
3. Add your content using Markdown

### Adding a New Prompt to the Library

1. Create a new directory in `resources/prompt-library/` for your prompt
2. Create an `index.md` file in the new directory with the following front matter:
   ```yaml
   ---
   layout: page
   title: Your Prompt Title
   permalink: /resources/prompt-library/your-prompt-url/
   ---
   ```
3. Add your prompt content following the existing format

## Deployment

The site is automatically deployed to GitHub Pages whenever changes are pushed to the main branch.

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For more information about Next Gen Cyber Ed, please contact us at contact@nextgencybered.org.