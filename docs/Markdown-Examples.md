# Documenting and Communicating Software Architecture

## PlantUML in Markdown

### Directly in file
* :heavy_check_mark: works nicely in preview in **Visual Studio Code** (using Markdown Preview Enhanced)
* :x: does not work on **GitHub**, because GitHub does not natively support PlantUML
* :heavy_check_mark: works on **GitLab**, because GitLab supports PlantUML (untested)
* :x: does not work using **GitHub action** with markdown-to-pdf

```plantuml
A -> B: abc
```

### Rendered using GitHub action
* (:heavy_check_mark:) works in preview in **Visual Studio Code** - but outdated!
* :heavy_check_mark: works nicely on **GitHub**
* :grey_question: requires different setup on **GitLab**
* :heavy_check_mark: works nicely with **GitHub action** with markdown-to-pdf
![C4 Context](../images/c4-1-context.png)


## Bonus: Mermaid in Markdown
* :heavy_check_mark: [Mermaid](https://mermaid.js.org/) is [natively supported in GitHub](https://github.blog/developer-skills/github/include-diagrams-markdown-files-mermaid/). So you can integrate Mermaid diagrams directly in Markdown and they will be rendered automatically
* :x: Does not work in **GitHub action** with Markdown-to-PDF rendering

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

