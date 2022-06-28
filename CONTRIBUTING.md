# Contributing Guidelines

Create a branch off of master for your task. After completing your notebook(s) and content review, make the recommended changes and open a pull request from your branch to master. 

We consider it a best practice to clear all cell outputs before commiting. This can be done with 'Kernel > Restart & Clear Output' (or 'Edit > Clear All Outputs' in JupyterLab) from the top menu bar. 

## Naming Conventions

Your notebook name should be kebab-case and it should not contain a Jira task identifier.  If your notebook is in a directory, your directory should have the same name as your notebook but in UpperCamelCase. All files should have descriptive names and refer to the notebooks to which they relate.

## Organization

The purpose of this repository is to store supporting files and visualizations for notebooks that exist in other Callysto repositories, (such as [`data-viz-of-the-week`](https://github.com/callysto/data-viz-of-the-week)) to reduce the size of the original repository. To that end, supporting files < 1 MB in size are exempt from the below policy.

Supporting files are data files that are the focus of the analysis in the notebook. Examples include:
- CSVs/tabular data
- Image files (if the image is the focus of the analysis)

Also included are visualizations, such as:
- Static graphics (i.e., PNG, JPEG files)
- Interactive plots (i.e., HTML)

Files NOT required to be moved to `data-files`:
- Embedded images
- Small files (<1 MB)


## Folder names
Supporting files should be placed in a folder named `data`, and visualizations in a folder named `visualizations`

## General Considerations

Similar to [Zen of Python](https://en.wikipedia.org/wiki/Zen_of_Python), your descriptions and code should be readable and easy to explain, and simple is better than complex.

Aim for concise wording and short notebooks, and check that the reading level is appropriate for your audience. Assume that your readers have access to other resources on the topic, or explicitly link to other learning resources.
