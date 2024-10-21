# Bsjhx CV repostiroy

* [Full CV (full career history)](https://bsjhx.github.io/cv-tex/full.pdf)
* [Java CV](https://bsjhx.github.io/cv-tex/java.pdf)

### Options

| Name          | Description                                                                | Default     |
| ------------- | -------------------------------------------------------------------------- | ----------- |
| `deploy_key`  | Deploy key used to deploy to GitHub Pages                                  |             |
| `files`       | Space-separated list of files that should be compiled                      |             |
| `handouts`    | Space-separated list of Beamer files that handouts should be generated for |             |
| `publish_dir` | The directory that should be published with GitHub Pages                   | `dist`      |
| `index_page`  | Path to the Markdown file that should be the main page                     | `README.md` |
| `pre_compile_command`  | Command to run before compiling LaTeX sources                     | `tlmgr update --self && tlmgr update --all` |
