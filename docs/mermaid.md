---
icon: lucide/chevrons-left-right
title: Mermaid
---

# Mermaid diagram

!!! About mermaid

    Mermaid is blablabla

    Web site :[mermaid.ai](https://www.mermaidchart.com/)

## Diagrams

=== "Code"

    ````markdown
    ```mermaid
    graph LR
    A[Alpha] --> B[Beta];
    A --> F[Foxtrot];
    B --> C[Charlie];
    B --> D[Delat];
    D --> E([Echo]);
    ```
    ````

=== ":right_arrow: Result"

    ```mermaid
    graph LR
    A[Alpha] --> B[Beta];
    A --> F[Foxtrot];
    B --> C[Charlie];
    B --> D[Delat];
    D --> E([Echo]);
    ```

## Pie chart

=== "Code"

    ````markdown
    ```mermaid
    pie
    accTitle: My Pie Chart Accessibility Title
    accDescr: My Pie Chart Accessibility Description

        title Key elements in Product X
        "Calcium" : 42.96
        "Potassium" : 50.05
        "Magnesium" : 10.01
        "Iron" :  5
    ```
    ````

=== ":right_arrow: Result"

    ```mermaid
    pie
    accTitle: My Pie Chart Accessibility Title
    accDescr: My Pie Chart Accessibility Description

        title Key elements in Product X
        "Calcium" : 42.96
        "Potassium" : 50.05
        "Magnesium" : 10.01
        "Iron" :  5
    ```
