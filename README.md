## 🚀 Overview

Welcome to my **CV**, a collection of LaTeX templates designed to streamline the job application process. Accompanied by a **Custom GPT Assistant**, to tailor the CV and cover letter to target each job listing.


### File Descriptions

- **cv_skills.txt**: A text file where you list your skills and experiences.
- **preamble.tex**: Contains common configurations and header info used across different LaTeX documents.
- **cv.tex**: LaTeX template for your CV. Utilizes the skills listed in `cv_skills.txt`.
- **cover_letter.tex**: LaTeX template for your cover letter.
- **references.tex**: Template for listing your professional references.


## 📋 Getting Started

### 📑 Prerequisites

Ensure you have the following installed on your system:

- **LaTeX Distribution**: [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/) recommended.
- **Git**: For version control and repository management.
- **XeLaTeX**: Required for compiling the provided LaTeX templates.

### 📝 Usage Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ENLinden/cv.git
   cd cv

2. **Update Info in Files**

   - **Update `cv_skills.txt`**: List your relevant skills and experiences.
   - **Update `preamble.tex`**: Adjust settings such as fonts, colors, and personal information to match your preferences.
   - **Update `references.tex`**: Add or modify your professional references.

3. **Regenerate Documents with Updated Info**

   - **Start a Conversation**: [👉 Try the Custom GPT](https://chatgpt.com/g/g-brdIFXKqk-job-application-tailor)
   - **Instructions**:
     1. **Paste `cv_skills.txt` and `cv.tex`** into the GPT conversation.
     2. **Request Updates**: Ask the GPT to align your CV with the listed skills.
     3. **Commit Changes**: Replace the existing `cv.tex` with the updated code from GPT and commit your changes.

4. **Target Specific Job Listings**

   - **Create a New Branch**: For each job application, create a new branch.
   - **Start a New GPT Conversation**: Use the first prompt suggestion button to initiate a job listing targeting session. 
   - **Update Documents**: Paste the GPT-generated code snippets into the relevant files and commit your changes after each interaction.


## 📌 Additional Information

- **Editing Instructions**: Users should edit `cv_skills.txt` and `preamble.tex` to match their CV details. After making these changes, they can utilize the Custom GPT to update `cv.tex` accordingly.
- **Branching Strategy**: For each job application, create a new branch to manage changes without affecting the main templates.
- **Commit Practices**: After each interaction with the GPT assistant, commit the updated `.tex` files to maintain a clear history of changes.

---

### Example CV
[![CV Thumbnail](cv_colorful_thumbnail.png)](cv_colorful.pdf)
