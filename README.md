# JUMP Cell Painting dataset: morphological impact of 136,000 chemical and genetic perturbations

This repo contains the notebooks for generating figures in the JUMP data production paper (Chandrasekaran et al. 2023). It also contains the profiles from the ORF subset of JUMP dataset (https://github.com/jump-cellpainting/dataset.git) as a submodule.

To run the Jupyter notebooks in this repository, install the `conda` environment using the `0.visualize-orf-data/environment.yml` file.

## Contributing

### Commit Message Template

This repository includes a commit template (`.gitmessage`) to ensure all commits include proper attribution to contributors.

After cloning the repository, configure Git to use the template:

```bash
git config --local commit.template .gitmessage
```

To use the template when committing:

1. Make and stage your changes as usual: `git add .`
2. Commit without the `-m` flag: `git commit`
3. Your text editor will open with the template pre-populated with co-authors
4. Write your commit message at the top of the file (above the comments)
5. Save and close the editor to complete the commit

### Important Notes

- The template only works when you use `git commit` without the `-m` flag
- All project contributors are already included in the template
- Feel free to add additional co-authors for specific commits as needed
- The blank line between the commit message and co-authors is required for GitHub to recognize co-authorship

# License 
We use a dual license in this repository. We license the source code as [BSD 3-Clause](https://github.com/jump-cellpainting/jump-data-production-paper/blob/main/LICENSE_BSD3.md), and license the data, results, and figures as [CC0 1.0](https://github.com/jump-cellpainting/jump-data-production-paper/blob/main/LICENSE_CC0.md).
