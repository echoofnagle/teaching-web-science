# Writing HW Reports

## General Guidelines

For each HW assignment, you are required to write a report. Reports are not just a list of questions and answers, but *must* include descriptions, screenshots, copy-paste of code output, references, as necessary.  For each question you address, you must provide a discussion of how you answered the question.  

You may use existing code, but you **must** document and reference where you adapted the code -- give credit where credit is due! *Use without attribution is plagiarism!*  **All reports must have a section labeled "References" for listing the outside resources you consulted.**

For an example of what I'm expecting, you can look at a [previous student's report](report_exemplar.pdf).

## Submitting Reports

Each assignments must uploaded into its [respective folder in your private Github repo](#).

Usually the new repo will only contain a `README.md` file with the assignment instructions.  For some assignments, the repo may also contain data files needed to complete the assignment.

Before you submit your assignment, make sure that your GitHub repo contains all scripts, code, output files, and images needed to complete the assignment and your report.

## Formatting Requirements

All reports must include your name, class (DATA 440), assignment number/title, and date.  You do not need a title page.

You *may* complete your reports in Markdown or may choose to use LaTeX instead (for 2 extra-credit points).

* I've provided a [Markdown report template](data440_report_template.md) for your modification and use.
* Your Markdown report and all images referenced in the report must be included in your GitHub repo.

To receive 2 extra-credit points, write your reports using LaTeX to generate to a PDF file.

* I've provided a [LaTeX report template in Overleaf](https://www.overleaf.com/read/vrfznvpgyrjc).  You can view the PDF that's generated there as well.
  * You should sign up for a free [Overleaf](https://overleaf.com) account.
* When you include an image in your report, *do not change the [aspect ratio](https://en.wikipedia.org/wiki/Aspect_ratio_(image)) of the image*.
* You must include your .tex source file and any images used along with your .pdf report in your GitHub repo.  There are a couple different ways to do this.
  * Download the source files from Overleaf and upload to your GitHub repo.  See [Downloading a Project](https://www.overleaf.com/learn/how-to/Downloading_a_Project) for instructions on how to download a .zip file of your Overleaf project source files.  You should unzip this file locally and only upload the .tex, .pdf, and image files needed for your report to your GitHub repo.  Do not directly upload the .zip file to GitHub.
  * Connect your Overleaf project to your GitHub repo.  See ["How do I connect an Overleaf project with a repo on GitHub"](https://www.overleaf.com/learn/how-to/How_do_I_connect_an_Overleaf_project_with_a_repo_on_GitHub,_GitLab_or_BitBucket%3F) for instructions on how to do this.

When you are asked to include a graph/chart in your report, they must be generated in R or using a Python plotting library.  *Excel graphs are not acceptable.* Although scientific graphs can be created in Excel, I want you to become familiar with common data science tools.