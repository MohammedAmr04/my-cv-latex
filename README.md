# Professional LaTeX CV

A clean, professional CV template built with LaTeX. This template is designed to be easily customizable and produces a polished, well-structured resume suitable for job applications in technical and professional fields.

## Features

- Clean, modern, and professional design
- Well-organized sections including Education, Experience, Projects, and Skills
- Responsive layout that works well in both digital and print formats
- Easy to customize with your personal information
- Uses standard LaTeX packages for maximum compatibility
- ATS-friendly formatting

## Prerequisites

To compile this CV, you'll need:

- A LaTeX distribution (e.g., [TeX Live](https://www.tug.org/texlive/), [MiKTeX](https://miktex.org/), or [MacTeX](https://www.tug.org/mactex/))
- Basic knowledge of LaTeX (for customization)

## Getting Started

1. Clone or download this repository
2. Edit the `.tex` files in the `src` directory with your personal information
3. Compile the document using:
   ```
   pdflatex resume.tex
   ```
4. Your compiled CV will be generated as `resume.pdf`

## Project Structure

- `resume.tex` - Main document file
- `custom-commands.tex` - Custom LaTeX commands and packages
- `src/` - Directory containing the CV sections:
  - `heading.tex` - Contact information and personal details
  - `summary.tex` - Professional summary/objective
  - `education.tex` - Educational background
  - `experience.tex` - Work experience
  - `projects.tex` - Relevant projects
  - `skills.tex` - Technical skills and competencies

## Customization

1. Update your personal information in the respective `.tex` files
2. Modify the styling in `custom-commands.tex` if needed
3. Add or remove sections as necessary by editing `resume.tex`

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Uses the Lato font for a clean, professional look
- Icons provided by `fontawesome5` package
- Built with standard LaTeX document classes and packages

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
