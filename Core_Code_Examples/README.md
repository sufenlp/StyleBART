# Core Code Examples for StyleBART

Here, we provide the core code examples for StyleBART, corresponding to Stages 1, 2, and 3:

- **Stage 1:** We train adapters (including humor, romance, clickbait, and nonstyle) on inverse paraphrasing tasks.
- **Stage 2:** We incorporate the nonstyle adapter into the base model and train the encoder on headline generation tasks.
- **Stage 3:** We replace the nonstyle adapter with a specific style adapter (humor, romance, or clickbait). The model is then ready to generate stylistic headlines.

- **Framework of StyleBART.**
<p align="center">
    <img src="../Assets/Framework_of_StyleBART.pdf" width="96%" height="96%">
</p>
