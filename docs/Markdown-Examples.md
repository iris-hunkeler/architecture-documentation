# Documenting and Communicating Software Architecture

## PlantUML in Markdown

### Directly in file
* works nicely in preview in Visual Studio Code (using Markdown Preview Enhanced)
* does **not** work on Github, because Github does not natively support PlantUML
* *should* work on GitLab, because GitLab supports PlantUML (untested)

```plantuml
A -> B: abc
```

### rendering using GitHub Action
* works in Visual Studio Code preview - but outdated!
* works nicely on Github with Github actions to update the image
![C4 Context](../images/c4-1-context.png)


## Mermaid in Markdown
[Mermaid](https://mermaid.js.org/) is [natively supported in Github](https://github.blog/developer-skills/github/include-diagrams-markdown-files-mermaid/). So you can integrate Mermaid diagrams directly in Markdown and they will be rendered automatically

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

