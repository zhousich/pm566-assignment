# Example Assignment

This repository includes a GitHub Actions workflow that will automatically look for a file named `submit.qmd` and render it to an HTML document. You can include as many other files as you want, but only `submit.qmd` will trigger the workflow.

When the workflow runs successfully, you can view the final HTML product by going to the "Actions" tab, clicking on the most recent run, and downloading the `submit-html` file under "Artifacts."

If you want to track whether or not your assignment has rendered successfully, add the below line of code to the `README.md` file. Just change the URL to include your GitHub username and the name of your repository:

```md
![status](https://github.com/<USERNAME>/<REPOSITORY>/actions/workflows/render.yml/badge.svg)
```
