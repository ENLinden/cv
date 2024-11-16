![Last Commit](https://img.shields.io/github/last-commit/ERLindeman/cv)
![License](https://img.shields.io/github/license/ERLindeman/cv)

## 🚀 Overview

Welcome to my **CV**, a collection of LaTeX templates designed to streamline the job application process. Accompanied by a **Custom GPT Assistant**, to tailor the CV and cover letter to target each job listing.


### File Descriptions

- **cover_letter.tex**: LaTeX template for your cover letter. Incorporates customizations for your application.
- **cv_skills.txt**: A text file where you list your skills and experiences. Editable to match your unique profile.
- **cv.tex**: LaTeX template for your CV. Utilizes the skills listed in `cv_skills.txt`.
- **preamble.tex**: Contains common configurations and header info used across different LaTeX documents.
- **references.tex**: Template for listing your professional references.


## 📋 Getting Started

### 📑 Prerequisites

Ensure you have the following installed on your system:

- **LaTeX Distribution**: [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/) recommended.
- **Git**: For version control and repository management.
- **XeLaTeX**: Required for compiling the provided LaTeX templates.


### 🔧 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ERLindeman/cv.git
   cd cv

2. **Install Dependencies**

   Ensure all required LaTeX packages are installed. You can typically do this via your LaTeX distribution's package manager.


### 📝 Usage Instructions

Follow these steps to customize your job application documents:

1. **Edit Your Skills and References**

   - **Update `cv_skills.txt`**: List your relevant skills and experiences.
   - **Update `references.tex`**: Add or modify your professional references.

2. **Customize the Preamble**

   - **Edit `preamble.tex`**: Adjust settings such as fonts, colors, and personal information to match your preferences.

3. **Generate Your CV and Cover Letter**

   - **CV (`cv.tex`)**: Incorporates your skills from `cv_skills.txt`.
   - **Cover Letter (`cover_letter.tex`)**: Tailored to your job application needs.

4. **Use the Custom GPT Assistant**

   Enhance your documents with AI assistance:

   - **Start a Conversation**: [👉 Try the Custom GPT](https://chatgpt.com/g/g-brdIFXKqk-job-application-tailor)
   - **Instructions**:
     1. **Paste `cv_skills.txt` and `cv.tex`** into the GPT conversation.
     2. **Request Updates**: Ask the GPT to align your CV with the listed skills.
     3. **Commit Changes**: Replace the existing `cv.tex` with the updated code from GPT and commit your changes.

5. **Target Specific Job Listings**

   - **Create a New Branch**: For each job application, create a new branch.
   - **Start a New GPT Conversation**: Use the first prompt suggestion button to initiate a job listing targeting session.
   - **Update Documents**: After each interaction, paste the GPT-generated code snippets into the relevant files and commit your changes.


### 📈 Example Workflow

1. **Initial Setup**

   ```bash
   git clone https://github.com/ERLindeman/cv.git
   cd cv

### 2. **Edit Skills and Preamble**

- **Update `cv_skills.txt`**: List your relevant skills and experiences.
- **Update `references.tex`**: Add or modify your professional references.

### 3. **Customize the Preamble**

- **Edit `preamble.tex`**: Adjust settings such as fonts, colors, and personal information to match your preferences.

### 4. **Generate Your CV and Cover Letter**

- **CV (`cv.tex`)**: Incorporates your skills from `cv_skills.txt`.
- **Cover Letter (`cover_letter.tex`)**: Tailored to your job application needs.

### 5. **Use the Custom GPT Assistant**

Enhance your documents with AI assistance:

- **Start a Conversation**: [👉 Try the Custom GPT](https://chatgpt.com/g/g-brdIFXKqk-job-application-tailor)
- **Instructions**:
  1. **Paste `cv_skills.txt` and `cv.tex`** into the GPT conversation.
  2. **Request Updates**: Ask the GPT to align your CV with the listed skills.
  3. **Commit Changes**: Replace the existing `cv.tex` with the updated code from GPT and commit your changes.

### 6. **Target Specific Job Listings**

- **Create a New Branch**: For each job application, create a new branch.
- **Start a New GPT Conversation**: Use the first prompt suggestion button to initiate a job listing targeting session.
- **Update Documents**: After each interaction, paste the GPT-generated code snippets into the relevant files and commit your changes.

## 📌 Additional Information

- **Editing Instructions**: Users should edit `cv_skills.txt` and `preamble.tex` to match their CV details. After making these changes, they can utilize the Custom GPT to update `cv.tex` accordingly.
- **Branching Strategy**: For each job application, create a new branch to manage changes without affecting the main templates.
- **Commit Practices**: After each interaction with the GPT assistant, commit the updated `.tex` files to maintain a clear history of changes.

---

### Example CV
[![CV Thumbnail](cv_colorful_thumbnail.png)](cv_colorful.pdf)
