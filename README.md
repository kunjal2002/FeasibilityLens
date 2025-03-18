# FeasibilityLens
FeasibilityLens : AI-driven agent assessing research feasibility by analyzing theory, practicality, and computational constraints with RAG


<h2>Overview</h2>

FeasibilityLens is an AI-powered agent designed to assess the feasibility of implementing novel approaches described in research papers. It leverages Retrieval-Augmented Generation (RAG) to extract relevant methodologies from related papers and uses a Large Language Model (LLM) to evaluate the feasibility and novelty of a given research methodology.

<h2>Features</h2>

Automated Feasibility Assessment: Analyzes research methodologies for feasibility, reproducibility, and improvement over existing approaches.

RAG-based Information Retrieval: Retrieves relevant research papers and extracts key methodological details.

LLM-powered Evaluation: Uses a Large Language Model (e.g., GPT-4) to assess feasibility and provide structured feedback.

Vector Database & Similarity Search: Stores research embeddings and performs efficient similarity searches using Facebook AI Similarity Search (FAISS).

Iterative Refinement: Allows researchers to refine methodologies based on AI-generated insights.

<h2>Workflow</h2>
<ul>
<li>Input Research Papers: User provides the current research paper and related papers for comparison.</li>

<li>RAG-based Retrieval & Extraction:<ul>

<li>Embeds and retrieves related papers using T5.</li>

<li>Stores embeddings in a vector database (FAISS) for efficient similarity searches.</li>
</ul></li></ul>

<H2>Feasibility Analysis via LLM:</H2>

Evaluates the methodology for feasibility, practicality, and improvements.

Compares with retrieved methodologies to assess novelty.

Results:

✅ Feasible & Novel

⚠️ Feasible but Not Novel

❌ Not Feasible


<h2>Technical Details</h2>

<h3>Technologies Used:</h3>

<li>RAG for information retrieval (using T5 for embedding)</li>

<li>Vector Database (FAISS) for similarity searches</li>

<li>LLM for feasibility evaluation (GPT-4 or similar models)</li>

<h3>Implementation Stack:</h3>

<li>Python</li>

<li>FAISS for efficient vector search and retrieval</li>

