<h1 align="center">Ask AI Paul Graham</h1>

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Didn't get into YC? Don't worry—now you can ask AI Paul Graham for personalized startup advice. Paul will be there whenever you need him.

<br>
<div align="center">
  <a href="https://youtu.be/QVYV4zZ90KU" target="_blank">
    <img src="./assets/pg_banner.png" width="700" alt="IMAGE ALT TEXT" style="cursor: pointer;">
  </a>
</div>
<br>

- 🔥🔥🔥 [Try Live Demo](https://pocket-pg-851564657364.us-east1.run.app/)
  
- Design Doc: [docs/design.md](docs/design.md), Flow Source Code: [flow.py](flow.py)

## I built this in just an hour, with this framework...

- The secret weapon is [Pocket Flow](https://github.com/The-Pocket/PocketFlow), a 100-line LLM framework that lets LLM Agents (e.g., Cursor AI) build Apps for you
  
- Step-by-step YouTube development tutorial:

<br>
<div align="center">
  <a href="https://youtu.be/Cf38Bi8U0Js" target="_blank">
    <img src="./assets/tutorial.png" width="500" alt="IMAGE ALT TEXT" style="cursor: pointer;">
  </a>
</div>
<br>

## How to Run

1. Implement functions in the `utils/` directory based on your chosen APIs.

2. Install dependencies and run the program:

    ```bash
    pip install -r requirements.txt
    python main.py
    ```

3. To run the application server:

    ```bash
    streamlit run app.py
    ```

4. If you change the data in the `data/` directory or the `meta.csv` file, ensure you run the offline processing script to generate the index and metadata:

    ```bash
    python offline_processing.py
    ```
