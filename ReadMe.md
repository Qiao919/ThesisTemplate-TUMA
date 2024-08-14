# Master Thesis Template Instructions

This template is based on the Thesis Template from TUM Economics of Innovation, authored by Hanna Hottenrott.

## Project Structure

1. **main.tex**: 
   - Defines the overall structure of the thesis.

2. **Settings.tex**: 
   - Contains all preamble settings and new commands.
   - Essential `usepackage` commands and layout definitions are loaded here.

3. **Chapter and Appendix folders**: 
   - Store individual chapter and appendix files.

4. **DefaultTemplate folder**: 
   - Contains title page, statutory declaration, and logos.

5. **Images folder**: 
   - Stores all images used in the thesis.

6. **SignedTopic.pdf**: 
   - The thesis proposal topic signed by the supervisor.

7. **References.bib**: 
   - Contains all bibliographic references in BibTeX format.

## How to Use This Template
1. **Thesis information**
   - Avoid making changes to files in the `DefaultTemplate` folder unless absolutely necessary.
   - All thesis information adjustments, including those on the title page and Declaration, can be made in main.tex (lines 5 to 14).

2. **Signed Master Thesis Topic**: 
   - Upload the approved and signed Master Thesis topic file with the filename `SignedTopic.pdf` and overwrite the existing file.

3. **Write Main Body**: 
   - Write your thesis chapters separately in the Chapter folder.
   - Name each chapter file as `1.tex`, `2.tex`, and so on.
   - This naming convention ensures that chapters are automatically included in `main.tex` in the correct order.

4. **Comments and Instructions**: 
   - Pay attention to comments and instructions. They provide guidance on potential changes you can make to the code or offer important information.

5. **References**:
   - Add your references to `References.bib` or upload a file named `References.bib` containing your BibTeX entries.

6. **Compilation**
   - It is recommended to use Overleaf.com online editor to compile this document.
   - When using Overleaf:
     - No special steps are needed for initial compilation.
   - If compiling on your local machine:
     - Use following commands:
       pdflatex Glossary.tex
    -Remember to compile your LaTeX document regularly to check for any errors or formatting issues as you work on your thesis.