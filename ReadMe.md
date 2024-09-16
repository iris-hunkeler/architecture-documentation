# Documenting and Communicating Software Architecture


## PlantUML in Markdown

--> Directly in file
```plantuml
A -> B: abc
```

--> Link to other file
```plantuml
!include ../C4/c4-1-context.puml
```


rendering an external file
![C4 context diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/iris-hunkeler/architecture-documentation/main/C4/c4-1-context.puml)


![system overview](//www.plantuml.com/plantuml/png/7SqxhW8n34RX_gxYie34GfgAQYHM4XoBM2JEoFajM3wFwdJdsnUA8qR_EwbnZohX_Ry1nxeGUNdckwB5BPOuJuCOCiz1whfI2tj85wVYt1J229TK9ySGGu5Eer7KwBeHR-cSVeSNyl45Tx7wwHi0)


<!--[Example With Only Link](./C4/c4-1-context.puml)-->


## Mermaid in Markdown
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


