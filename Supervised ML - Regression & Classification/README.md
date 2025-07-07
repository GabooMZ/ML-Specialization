# Supervised Machine Learning: Regression & Classification
### Course Materials and Practical Implementations

Repository containing my notes, code implementations, and practice labs for the Supervised Machine Learning course, focusing on Regression and Classification algorithms.

---

## Supervised Learning: Regression vs. Classification
```mermaid
graph TD
    A[<b>📊 Supervised Learning</b>] --> B[<b>📈 Regression</b>]
    A --> C[<b>🔍 Classification</b>]

    %% Regression Branch (Highlighted)
    B --> D["<b>🚀 Goal:</b> Predict continuous values<br><b>📌 Example:</b> House price prediction"]
    D --> E["<b>🔷 Key Algorithms:</b><br> - Linear Regression<br> - Polynomial Regression<br> - Gradient Descent Optimization"]
    D --> F["<b>💡 Course Labs:</b><br> - Cost Function Implementation<br> - Feature Scaling<br> - Sklearn OLS/SGD"]

    %% Classification Branch (Highlighted)
    C --> G["<b>🎯 Goal:</b> Predict discrete labels<br><b>📌 Example:</b> Spam detection"]
    G --> H["<b>🔷 Key Algorithms:</b><br> - Logistic Regression<br> - Decision Boundary Analysis<br> - Regularization"]
    G --> I["<b>💡 Course Labs:</b><br> - Logistic Loss Function<br> - Overfitting Mitigation<br> - Scikit-Learn Implementation"]

    %% Styling
    classDef highlight fill:#e6f3ff,stroke:#0066cc,stroke-width:4px,color:#003366,font-weight:bold
    classDef def fill:#f0f7f4,stroke:#2e856e,stroke-width:2px
    classDef algo fill:#e6f9ff,stroke:#0086b3,stroke-width:1.5px
    classDef labs fill:#fff0e6,stroke:#cc5200,stroke-width:1.5px

    class B,C highlight
    class D,G def
    class E,H algo
    class F,I labs