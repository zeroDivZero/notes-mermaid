# JUPYTER NOTEBOOK/LAB

In modern JupyterLab or Notebook (7+), Mermaid rendering is directly supported in Markdown cell.

Steps:

1. Create Markdown cell (in top dropdown, change cell type, usually `Code`, to `Markdown`).

2. Add Mermaid syntax within fenced `mermaid` block:

    ````text
    ```mermaid
    graph TD
        A[Jupyter Notebook] --> B(Render Mermaid);
        B --> C{Success?};
        C -- Yes --> D[Display Diagram];
        C -- No --> E[Error Handling];
    ```
    ````

3. Run cell to render diagram.
