## Rotation

0,- Music
1,    - Offended
2,    - Krystal
3,- Code
4,    - Check
5,        - Set up the data
6,            - [X] Scaffold in markdown
7,            - [X] Mock this in JSON
8,            - [] Given json data (entities + relationships) render the page
9,                - [] Render the node 
10                - [] render its child
11                - [] render its sibling
12        - Structure the page
13            - [X] Scaffold out html
14        - Implement the logic
            - [] Update
            - [] Add
            - [] Delete
          - Server (node + mongodb for the actual data layer)
15        - [X] Recording/Editing process
16    - Personal Site
17- Activities
18    - Go to cafe
19    - Go for a walk
20- Admin
21    - Contact local ISKF chapter to meet and see if I can train/instruct
22    - Set up a free trial at one competitive



let relationships = [
    { "target": 0, "child": 1, "sibling": 3},
    { "target": 1, "child": null, "sibling": 2},
    { "target": 2, "child": null, "sibling": null},
    { "target": 3, "child": 4, "sibling": 16},
    { "target": 4, "child": 5, "sibling": 17},
    { "target": 5, "child": 6, "sibling": 7},
    { "target": 6, "child": null, "sibling": 8},
    { "target": 7, "child": null, "sibling": null},
    { "target": 8, "child": 9, "sibling": null},
    { "target": 9, "child": null, "sibling": null},
    { "target": 10, "child": null, "sibling": null},
    { "target": 11, "child": null, "sibling": null},
    { "target": 12, "child": 13, "sibling": 14},
    { "target": 13, "child": null, "sibling": 15},
    { "target": 14, "child": null, "sibling": null},
    { "target": 15, "child": null, "sibling": null},
    { "target": 16, "child": null, "sibling": null},
    { "target": 17, "child": 18, "sibling": 20},
    { "target": 18, "child": null, "sibling": 19},
    { "target": 19, "child": null, "sibling": null},
    { "target": 20, "child": 21, "sibling": null},
    { "target": 21, "child": null, "sibling": 22},
    { "target": 22, "child": null, "sibling": null},
]

let checklistNodes = [
    {"id": 0, "title": "Music" },
    {"id": 1, "title": "Offended" },
    {"id": 2, "title": "Krystal" },
    {"id": 3, "title": "Code" },
    {"id": 4, "title": "Check" },
    {"id": 5, "title": "Set up the data" },
    {"id": 6, "title": "Scaffold in markdown" },
    {"id": 7, "title": "Mock this in JSON" },
    {"id": 8, "title": "Given json data (entities + relationships) render the page" },
    {"id": 9, "title": "Render the node " },
    {"id": 10, "title": "render its child" },
    {"id": 11, "title": "render its sibling" },
    {"id": 12, "title": "Structure the page" },
    {"id": 13, "title": "Scaffold out html" },
    {"id": 14, "title": "Implement the logic" },
    {"id": 15, "title": "Recording/Editing process" },
    {"id": 16, "title": "Personal Site" },
    {"id": 17, "title": "Activities" },
    {"id": 18, "title": "Go to cafe" },
    {"id": 19, "title": "Go for a walk" },
    {"id": 20, "title": "Admin" },
    {"id": 21, "title": "Contact local ISKF chapter to meet and see if I can train/instruct" },
    {"id": 22, "title": "Set up a free trial at one competitive" }
]