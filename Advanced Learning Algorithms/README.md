# Advanced Learning Algorithms: Neural Networks and Decision Trees
### Course Materials and Practical Implementations

Repository containing my notes, code implementations, and practice labs for the Advanced Learning Algorithms course, focusing on key topics for neural networks as well as theory on decision trees and ensemble methods.

---
## Advanced Learning Algorithms: Neural Networks and Decision Trees
```mermaid
graph TD

    A[<b>🧠 Advanced Learning Algorithms</b>] --> B[<b>🤖 Neural Networks</b>]
    A --> C[<b>🌳 Decision Trees & Ensembles</b>]

    %% Neural Networks Branch
    B --> D["<b>🚀 Core Concepts:</b><br> - TensorFlow/Keras Intro<br> - Forward Propagation<br> - Activation Functions"]
    D --> E["<b>🔷 Key Topics:</b><br> - Binary Classification<br> - Multiclass (SoftMax)<br> - Backpropagation<br> - Bias/Variance"]
    D --> F["<b>💡 Labs & Exercises:</b><br> - Coffee Roast NN<br> - Manual NumPy Implementation<br> - NN Diagnostics<br> - Week 1-3 Labs"]

    %% Decision Trees Branch
    C --> G["<b>🎯 Core Concepts:</b><br> - Decision Tree Theory<br> - Ensemble Methods<br> - Random Forests"]
    G --> H["<b>🔷 Key Topics:</b><br> - Splitting Criteria<br> - Feature Importance<br> - Boosting Techniques"]
    G --> I["<b>💡 Labs & Exercises:</b><br> - Decision Tree Implementation<br> - Tree Ensemble Practice<br> - Week 4 Lab"]

    %% Styling
    classDef highlight fill:#e6f3ff,stroke:#0066cc,stroke-width:4px,color:#003366,font-weight:bold
    classDef def fill:#f0f7f4,stroke:#2e856e,stroke-width:2px
    classDef algo fill:#e6f9ff,stroke:#0086b3,stroke-width:1.5px
    classDef labs fill:#fff0e6,stroke:#cc5200,stroke-width:1.5px

    class B,C highlight
    class D,G def
    class E,H algo
    class F,I labs