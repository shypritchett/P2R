```mermaid
flowchart TD
    A[Managing P2R HoW]
    B[Is HoW for each P2R floor >= 2?]
    C[Review RPPP at current wall count. Is risk >= 70 percent NNC on any floor over the planning horizon?]
    D[Consider increasing wall count to reduce NNC risk to <= 70 percent according to OM/CF direction to mitigate NNC risk.]
    E[Maintain wall count. DO NOT increase unless external barriers are foreseen.]
    F[Reduce wall count as there is minimal risk across the planning horizon.]
    
    A --> B
    B --> C
    C -- Yes --> D
    C -- No --> E
    B -- No --> F
    
    G[Managing P2R PPW]
    H[Which direction is PPW trending?]
    I[Towards picker - PPW is above 25 on a wall. How many packers are staffed to that wall?]
    J[Towards picker - PPW is below 18 on a wall. How many packers are staffed to that wall?]
    K[Towards packer - PPW is above 25]
    L[Towards packer - PPW is below 18]
    
    G --> H
    H -- Towards picker --> I
    I -- 1 --> J
    I -- 2 --> K
    H -- Towards packer --> L
    
    M[Towards packer - Do not add packer. Allow PPW to build and monitor if it breaches 25. By 35 PPW another packer should be added.]
    N[Towards packers - Do not remove packers. Picker is outperforming packers. Consider a replan to improve floor balance.]
    O[Towards packer - Consider a replan to improve wall balance and equalize performance between pickers and packers.]
    P[Towards picker - Remove 1 packer and move to a wall with out of standard PPW.]
    
    K --> M
    L --> N
    K -- By 35 PPW --> O
    L -- Once PPW is in compliance --> P
```

This flowchart covers the key decision points for managing P2R HoW and PPW based on the information provided. The symbols used are:

- Rectangles for process steps
- Diamonds for decision points
- Arrows to connect the steps

Let me know if you have any other questions or need further clarification on the flowchart.