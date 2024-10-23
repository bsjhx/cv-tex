# My CVs

- [Full CV (full career history)](https://bsjhx.github.io/cv-tex/full.pdf)
- [Java CV](https://bsjhx.github.io/cv-tex/java.pdf)
- [Rust CV](https://bsjhx.github.io/cv-tex/rust.pdf)

## Versions

| Date       | Version | Changes                                         |
| ---------- | ------- | ----------------------------------------------- |
| 23.10.2024 | 0.1     | Initial release. Added full, Java and Rust CVs. |

# Useful links

- [reddit sources about creating resume](https://old.reddit.com/r/EngineeringResumes/wiki/index)
- [Resume checker](https://www.resumego.net/resume-checker/)

# Options

| Name                  | Description                                                                | Default                                     |
| --------------------- | -------------------------------------------------------------------------- | ------------------------------------------- |
| `deploy_key`          | Deploy key used to deploy to GitHub Pages                                  |                                             |
| `files`               | Space-separated list of files that should be compiled                      |                                             |
| `handouts`            | Space-separated list of Beamer files that handouts should be generated for |                                             |
| `publish_dir`         | The directory that should be published with GitHub Pages                   | `dist`                                      |
| `index_page`          | Path to the Markdown file that should be the main page                     | `README.md`                                 |
| `pre_compile_command` | Command to run before compiling LaTeX sources                              | `tlmgr update --self && tlmgr update --all` |
