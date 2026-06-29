FLowchart 3

flowchart TD
    A([Start]) --> B[/Input number/]
    B --> C{Is number mod 2 = 0?}
    C -- Yes --> D[/Display "EVEN"/]
    C -- No --> E[/Display "ODD"/]
    D --> F([End])
    E --> F