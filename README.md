<table>
<tr>
<td>

<h1>Max Sun</h1>

<p><strong>Student interested in Software, ML &amp; Chip Design</strong></p>

</td>
<td>

<img src="profile.png"
     alt="Profile Photo"
     width="200"
     height="200"
     style="border-radius:50%; object-fit:cover;">

</td>
</tr>
</table>

## Work
Built a Python-based financial automation system for the Birdfeeder, a concessions business at Cincinnati Country Day School. The application ingests Square API transaction data, calculates revenue, cost of goods sold, processing fees, and net income, and generates KPI dashboards for business analysts. Used by the Birdfeeder to automate financial reporting workflows.

[Financial Automation for the Birdfeeder](https://github.com/Max-sm-yc/BirdfeederFinancialData)

## Tech Stack
Languages:
Python, C++, Java

ML & GPU:
PyTorch, CUDA

Tools:
Git, Github, VSCode

Concepts:
OOP, Data Structures, Transformers, Agents & Tools, GPU Programming

## Projects

[Artifact Chat Agent](https://github.com/Max-sm-yc/artifact-agent)

Created an agentic chatbot capable of modifying code and text outputs without needing to regenerate entire sequences. The agent creates, modifies, copies artifacts, preventing transcription mistakes that standard chat interfaces can introduce.

[Gated Convolution Kernel (CUDA/CUTLASS)](https://github.com/Max-sm-yc/ConvolutionGate)

Developed a custom CUDA implementation of a Gated Convolution kernel using CUTLASS that outperformed PyTorch eager execution and torch.compile on medium-length workloads. Peak outperformance of 42% vs torch.compile and 67.6% vs PyTorch eager. 

[Tensor C++](https://github.com/Max-sm-yc/tensorcpp)

An ongoing project recreating deep learning functionalities in C++. Intended to be executed on CPU (SIMD Hardware). All dimensions must be multiples of 8 for SIMD execution.

Current features: tensor matadd matmul linear

The main.cpp currently contains an example usage of the linear class.

    \tensorcpp> ./test                                           
    program start
    tensor initialized
    linear layer initialized
    layer forward
    rows=1 cols=8 size=8
    [3.97522, 5.76335, 4.50937, 4.6029, 3.82836, 4.83475, 5.97096, 5.11077, ]
    
Upcoming features: Autograd ReLU, non-linearities

### Foundational Projects

[Vector Database & Search (C++)](https://github.com/Max-sm-yc/embeddingDB)

A C++ embedding database that allows vector insertion and search. Searching is conducted by cosine similarity (handled by normalizing all vectors inserted in to the database and finding the dot product). A min heap is used to preserve the top k tokens that are returned.

fillDB creates a vectors.bin with random character combinations and embedding vectors. main ingests data in vectors.bin, conducts a search (and can be modified to insert new embeddings) before writing data back into vectors.bin

    \embeddingDB> ./search                                                          
    Program started           
    Reading complete          
    Searching across 100000
    Searching complete with size 10 returned 
    1 osjxapwnyz
    0.37292 shdjppnlkp
    0.360166 futiyoqwes
    0.358401 dxositnnah
    0.356896 vxaebytozi
    0.346819 bbnpkqgtqd
    0.341851 bczmqfioct
    0.340948 garshtabum
    0.340268 abgitjetvk
    0.338501 cfnwtcdfje
    Writing data back
    Done!

[Inventory Manager (C++)](https://github.com/Max-sm-yc/inventory_manager)

A C++ project using header and source files, file-based data persistence, dependencies between classes, and CMAKE to create a terminal-based store inventory manager.

## Awards and Programs

• Leaf Course AI Safety Cohort (Summer 2026, ~10% acceptance rate)
• Citadel Securities High School Terminal Competition:
  Team placed 7th of 29
• HiMCM Meritorious

## Education

Cincinnati Country Day School
High School Senior | GPA: 4.0

• Highest weighted GPA in class for three years
• SAT: 1570 (800 Math, 770 EBRW)
• Coursework: Linear Algebra, Differential Equations,
  AP Calculus BC, AP Computer Science A

## [Resume](https://raw.githubusercontent.com/Max-sm-yc/max-sm-yc.github.io/main/MaxResume.pdf)

## Contact
Email: max-sm-yc@gmail.com
