# Professional Curriculum Vitae

Welcome to my GitHub repository dedicated to my professional CV, a comprehensive document written and typeset in LaTeX. This repository offers an in-depth overview of my academic qualifications, professional journey, technical prowess, and publications so far.

## Table of Contents
- [Structure](#structure)
- [LaTeX Document Structure](#latex-document-structure)
- [Getting Started](#getting-started)
- [Why LaTeX?](#why-latex)
- [Updates and Versioning](#updates-and-versioning)
- [Feedback and Suggestions](#feedback-and-suggestions)

## Structure
The CV encapsulates my professional journey and is structured in the following manner:

1. **Personal Information:** My contact details and a quick reference to social and professional networking platforms.
2. **Education:** An account of my educational background, detailing the degrees I've earned, institutions I've attended, and years of graduation.
3. **Professional Experience:** A chronological recounting of my professional journey, detailing the roles I've undertaken, responsibilities shouldered, and significant achievements.
4. **Skills:** A synopsis of my technical skills, including the technologies, languages, and tools I'm proficient in and those I'm familiar with.
5. **Publications:** A compilation of my research publications, papers presented, and significant academic contributions.

## LaTeX Document Structure

The main document `Minimal-CV.tex` is the root LaTeX file. It pulls in data from separate `.tex` files located in the `sections` directory. Each section is self-contained, making the CV easier to maintain and update.

## Getting Started

If you're interested in compiling the LaTeX document into a PDF, ensure you have a LaTeX distribution installed on your system. Following this, execute the following command:

```bash
pdflatex Minimal-CV.tex
