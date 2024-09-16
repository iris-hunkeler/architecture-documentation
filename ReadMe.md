# Documenting and Communicating Software Architecture


## PlantUML in Markdown

--> Directly in file
```plantuml
A -> B: abc
```


--> rendering first
![C4 Context](C4/c4-context-diagram.svg)


## Mermaid in Markdown
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


