<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# KNA_AGENTICAI

<em>Empowering Intelligent Automation for Limitless Possibilities</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/license/sumitatwork/KNA_AgenticAI?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
<img src="https://img.shields.io/github/last-commit/sumitatwork/KNA_AgenticAI?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/sumitatwork/KNA_AgenticAI?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/sumitatwork/KNA_AgenticAI?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/Wikipedia-000000.svg?style=flat&logo=Wikipedia&logoColor=white" alt="Wikipedia">
<img src="https://img.shields.io/badge/arXiv-B31B1B.svg?style=flat&logo=arXiv&logoColor=white" alt="arXiv">
<img src="https://img.shields.io/badge/LangChain-1C3C3C.svg?style=flat&logo=LangChain&logoColor=white" alt="LangChain">
<img src="https://img.shields.io/badge/XML-005FAD.svg?style=flat&logo=XML&logoColor=white" alt="XML">
<img src="https://img.shields.io/badge/Pydantic-E92063.svg?style=flat&logo=Pydantic&logoColor=white" alt="Pydantic">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgment](#acknowledgment)

---

## Overview

KNA_AgenticAI is a versatile developer toolset crafted to facilitate intelligent agent interactions, automation, and scalable knowledge management within complex AI architectures. It seamlessly integrates diverse data sources, language models, and vector databases to enable advanced document analysis, semantic search, and reasoning.

**Why KNA_AgenticAI?**

This project aims to streamline the development of intelligent, scalable AI systems. The core features include:

- **🧩** *External Data Integration:* Connects with Wikipedia, YouTube, Tavily, and more for enriched information access.
- **🌐** *Graph-Based Language Modeling:* Constructs and manages interconnected language graphs for complex reasoning.
- **🚀** *High-Performance Vector Search:* Utilizes FAISS and Pinecone for fast, scalable similarity search.
- **🔒** *Robust Data Validation:* Implements data schemas with Pydantic to ensure data integrity.
- **⚙️** *Environment Management:* Simplifies setup with centralized environment configuration for consistent deployments.

---

## Features

|      | Component       | Details                                                                                                           |
| :--- | :-------------- | :-------------------------------------------------------------------------------------------------------------- |
| ⚙️  | **Architecture**  | <ul><li>Modular design leveraging LangChain components for NLP workflows</li><li>Supports multiple data sources and retrieval methods</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Uses `requirements.txt` for dependency management</li><li>Structured directory with clear separation of modules</li></ul> |
| 📄 | **Documentation** | <ul><li>Basic README with project overview</li><li>Potential for detailed docs via inline comments and markdown files</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Extensive use of LangChain integrations: OpenAI, Pinecone, Huggingface, Google GenAI</li><li>Supports FAISS for vector similarity search</li><li>Incorporates external APIs like Wikipedia, YouTube Search, Yahoo Finance</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Component-based architecture with separate modules for data ingestion, processing, and retrieval</li><li>Use of Pydantic for data validation</li></ul> |
| 🧪 | **Testing**       | <ul><li>Not explicitly detailed; likely relies on Jupyter notebooks for experimentation</li><li>Potential for unit tests via standard Python testing frameworks</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Utilizes FAISS (`index.faiss`, `faiss-cpu`) for fast vector similarity searches</li><li>Supports efficient retrieval over large datasets</li></ul> |
| 🛡️ | **Security**      | <ul><li>Uses `defusedxml` to mitigate XML vulnerabilities</li><li>Environment variables managed via `python-dotenv`</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Core dependencies include `langchain`, `faiss-cpu`, `pydantic`, `motor`, `pypdf`, `youtube_search`, `wikipedia`, `duckduckgo_search`</li><li>Additional integrations with `langchain-google-genai`, `langchain-huggingface`, `langchain-groq`</li></ul> |

---

## Project Structure

```sh
└── KNA_AgenticAI/
    ├── 1-Pydantic
    │   └── pydantic.ipynb
    ├── 2-Langchain Basics
    │   ├── 2.2-DataTransformer
    │   ├── 2.3-Embeddings
    │   ├── 2.4-VectorDatabase
    │   └── gettingstartedlangchain.ipynb
    ├── LICENSE
    ├── README.md
    ├── data
    │   └── usa.txt
    ├── langgraph
    │   ├── langgraph_1.ipynb
    │   ├── langgraph_2.ipynb
    │   ├── langgraph_3.ipynb
    │   ├── langgraph_4.ipynb
    │   ├── langgraph_5.ipynb
    │   ├── langgraph_6.ipynb
    │   └── tools.ipynb
    └── requirements.txt
```

---

### Project Index

<details open>
	<summary><b><code>KNA_AGENTICAI/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/README.md'>README.md</a></b></td>
					<td style='padding: 8px;'>- Provides an overview of the KNA_AgenticAI project, outlining its core purpose within the broader architecture<br>- It emphasizes the system’s role in enabling intelligent agent interactions and automation, facilitating seamless integration and communication across components<br>- This summary highlights how KNA_AgenticAI contributes to the overall functionality and scalability of the platform.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/LICENSE'>LICENSE</a></b></td>
					<td style='padding: 8px;'>- Provides the licensing terms for the project, establishing legal permissions and restrictions for software use, distribution, and modification within the overall architecture<br>- Ensures users understand their rights and responsibilities, supporting open-source collaboration and safeguarding intellectual property across the codebase.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/requirements.txt'>requirements.txt</a></b></td>
					<td style='padding: 8px;'>- Defines project dependencies essential for building a versatile AI-powered information retrieval and processing system<br>- Facilitates integration of various data sources, language models, and vector databases, enabling scalable document analysis, semantic search, and knowledge management within the broader architecture<br>- Supports seamless setup and consistent environment configuration for the entire codebase.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- 1-Pydantic Submodule -->
	<details>
		<summary><b>1-Pydantic</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ 1-Pydantic</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/1-Pydantic/pydantic.ipynb'>pydantic.ipynb</a></b></td>
					<td style='padding: 8px;'>- Pydantic/pydantic.ipynbThis notebook serves as an educational guide illustrating the core concepts of using Pydantic models for data validation within the project<br>- It demonstrates how to define data schemas using Python type annotations, ensuring data integrity and correctness across the codebase<br>- By establishing robust data validation practices, this component underpins the overall architectures reliability, facilitating seamless data handling and reducing runtime errors throughout the system.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- langgraph Submodule -->
	<details>
		<summary><b>langgraph</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ langgraph</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/langgraph/tools.ipynb'>tools.ipynb</a></b></td>
					<td style='padding: 8px;'>- Provides a suite of tools for integrating external data sources such as Wikipedia, YouTube, and Tavily into language models<br>- Facilitates querying, content retrieval, and search result processing to enhance information access and analysis within the broader application architecture<br>- Supports seamless extension with custom tools, enabling flexible and scalable data enrichment workflows.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/langgraph/langgraph_1.ipynb'>langgraph_1.ipynb</a></b></td>
					<td style='padding: 8px;'>- Summary of <code>langgraph_1.ipynb</code>This notebook serves as a foundational component within the LangGraph project, primarily focusing on constructing and managing graph-based representations of language models<br>- It provides mechanisms to define and manipulate graph structures, including nodes and edges, which encapsulate language states and their relationships<br>- The core functionalities—such as <code>graph()</code>, <code>state</code>, <code>edges</code>, <code>nodes</code>, and <code>invoke</code>—facilitate the creation, traversal, and invocation of language-related graph constructs<br>- Overall, this file plays a crucial role in enabling the architecture to model complex language interactions through interconnected graph components, supporting the projects goal of advanced language understanding and processing.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/langgraph/langgraph_2.ipynb'>langgraph_2.ipynb</a></b></td>
					<td style='padding: 8px;'>- Langgraph/langgraph_2.ipynbThis notebook serves as a core component within the LangGraph project, primarily focusing on advancing the language graphs capabilities<br>- It facilitates the processing, analysis, and enhancement of interconnected language data, enabling more sophisticated understanding and reasoning over language relationships<br>- Overall, this code contributes to building a more intelligent and interconnected language graph system, supporting tasks such as knowledge representation, semantic linking, and contextual understanding within the broader architecture.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/langgraph/langgraph_5.ipynb'>langgraph_5.ipynb</a></b></td>
					<td style='padding: 8px;'>- This code file initializes the environment for the project by loading configuration variables, specifically setting up access to the OpenAI API key<br>- It serves as a foundational setup step within the overall architecture, enabling subsequent components to interact securely with external AI services<br>- By managing environment variables centrally, it ensures that the system can reliably leverage language model capabilities for tasks such as natural language processing, understanding, or generation across the project.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/langgraph/langgraph_6.ipynb'>langgraph_6.ipynb</a></b></td>
					<td style='padding: 8px;'>- Summary of <code>langgraph/langgraph_6.ipynb</code>This notebook serves as an initial setup and configuration step within the larger LangGraph project<br>- Its primary purpose is to load environment variables, which are essential for configuring the applications runtime environment, such as API keys, database credentials, or other sensitive settings<br>- By establishing this foundational configuration, the notebook ensures that subsequent components of the codebase can operate securely and consistently, supporting the overall architecture's goal of building a scalable, environment-aware language graph system.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/langgraph/langgraph_4.ipynb'>langgraph_4.ipynb</a></b></td>
					<td style='padding: 8px;'>- The <code>langgraph/langgraph_4.ipynb</code> notebook serves as an experimental or development environment within the LangGraph project, primarily focusing on integrating and testing language model interactions with a graph-based knowledge structure<br>- It leverages the <code>langchain_groq</code> library to facilitate advanced querying capabilities, enabling natural language processing to interact seamlessly with the underlying graph data<br>- Overall, this file contributes to the projects goal of building intelligent, language-driven graph systems by providing a platform to prototype, validate, and refine language model integrations in the context of graph-based knowledge management.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/langgraph/langgraph_3.ipynb'>langgraph_3.ipynb</a></b></td>
					<td style='padding: 8px;'>- The <code>langgraph/langgraph_3.ipynb</code> file serves as a core component within the project, primarily responsible for demonstrating and validating the language graphs capabilities<br>- It functions as an experimental or testing notebook that executes code to verify the integrity and correctness of language graph operations<br>- Overall, this file contributes to the broader architecture by ensuring that language graph functionalities—such as understanding and processing language relationships—are working as intended, supporting the projects goal of building a robust, interconnected language understanding system.</td>
				</tr>
			</table>
		</blockquote>
	</details>
	<!-- 2-Langchain Basics Submodule -->
	<details>
		<summary><b>2-Langchain Basics</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ 2-Langchain Basics</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/gettingstartedlangchain.ipynb'>gettingstartedlangchain.ipynb</a></b></td>
					<td style='padding: 8px;'>- This code file serves as an introductory setup for leveraging Langchain within a broader AI application architecture<br>- Its primary purpose is to initialize environment variables and API keys necessary for integrating Langchains language model capabilities and tracking features<br>- By doing so, it facilitates seamless interaction with OpenAIs models and enables project-level monitoring and tracing of language processing workflows<br>- Overall, this file lays the foundational configuration that supports scalable, traceable, and efficient language-based functionalities within the larger codebase.</td>
				</tr>
			</table>
			<!-- 2.3-Embeddings Submodule -->
			<details>
				<summary><b>2.3-Embeddings</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ 2-Langchain Basics.2.3-Embeddings</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.3-Embeddings/2.3.2-huggingface.ipynb'>2.3.2-huggingface.ipynb</a></b></td>
							<td style='padding: 8px;'>- Provides an implementation of Hugging Face sentence-transformers within a Langchain-based architecture to generate high-quality text embeddings<br>- Facilitates converting textual data into vector representations for tasks like similarity search, clustering, or retrieval, enabling seamless integration of advanced NLP models into larger AI workflows and applications.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.3-Embeddings/speech.txt'>speech.txt</a></b></td>
							<td style='padding: 8px;'>- Facilitates the embedding of speech or textual data into a vector space to enable semantic search and retrieval within the broader language processing architecture<br>- It supports understanding and organizing large text corpora by transforming content into meaningful numerical representations, thereby enhancing the system’s ability to perform context-aware information retrieval and analysis.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.3-Embeddings/2.3.1-embeddings.ipynb'>2.3.1-embeddings.ipynb</a></b></td>
							<td style='padding: 8px;'>- Implements text embedding techniques to convert textual data into vector representations, facilitating semantic understanding and similarity searches within the larger language processing architecture<br>- It demonstrates how to generate embeddings using OpenAI models, load and process documents, and prepare data for downstream tasks such as retrieval or analysis in the overall NLP pipeline.</td>
						</tr>
					</table>
				</blockquote>
			</details>
			<!-- 2.2-DataTransformer Submodule -->
			<details>
				<summary><b>2.2-DataTransformer</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ 2-Langchain Basics.2.2-DataTransformer</b></code>
					<table style='width: 100%; border-collapse: collapse;'>
					<thead>
						<tr style='background-color: #f8f9fa;'>
							<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
							<th style='text-align: left; padding: 8px;'>Summary</th>
						</tr>
					</thead>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.2-DataTransformer/2.2.1-Recursivetextsplitter.ipynb'>2.2.1-Recursivetextsplitter.ipynb</a></b></td>
							<td style='padding: 8px;'>- Recursive Character Text SplitterThis code file implements a recursive text splitting mechanism designed to process documents into manageable, semantically coherent chunks<br>- It prioritizes splitting based on a prioritized list of characters (such as paragraph breaks, line breaks, or spaces), aiming to preserve meaningful units like paragraphs and sentences<br>- This functionality is essential within the larger architecture for preparing textual data—such as documents or transcripts—for downstream tasks like language modeling, information retrieval, or data transformation, ensuring that the text is segmented in a way that maintains context and enhances processing efficiency.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.2-DataTransformer/speech.txt'>speech.txt</a></b></td>
							<td style='padding: 8px;'>- Facilitates the transformation of raw textual data into structured, meaningful representations to support advanced language understanding tasks<br>- It integrates diverse data sources, enabling the system to process and analyze complex information efficiently within the broader architecture<br>- This component is essential for ensuring accurate, context-aware responses and insights in the overall language processing pipeline.</td>
						</tr>
						<tr style='border-bottom: 1px solid #eee;'>
							<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.2-DataTransformer/records.xml'>records.xml</a></b></td>
							<td style='padding: 8px;'>- Defines a structured dataset of records containing identifiers, names, and values, serving as foundational input for data transformation processes within the project<br>- Facilitates organized data handling and supports subsequent data processing tasks in the Langchain-based architecture, enabling efficient integration and manipulation of structured information for downstream applications.</td>
						</tr>
					</table>
				</blockquote>
			</details>
			<!-- 2.4-VectorDatabase Submodule -->
			<details>
				<summary><b>2.4-VectorDatabase</b></summary>
				<blockquote>
					<div class='directory-path' style='padding: 8px 0; color: #666;'>
						<code><b>⦿ 2-Langchain Basics.2.4-VectorDatabase</b></code>
					<!-- FAISS Submodule -->
					<details>
						<summary><b>FAISS</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ 2-Langchain Basics.2.4-VectorDatabase.FAISS</b></code>
							<table style='width: 100%; border-collapse: collapse;'>
							<thead>
								<tr style='background-color: #f8f9fa;'>
									<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
									<th style='text-align: left; padding: 8px;'>Summary</th>
								</tr>
							</thead>
								<tr style='border-bottom: 1px solid #eee;'>
									<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.4-VectorDatabase/FAISS/code.ipynb'>code.ipynb</a></b></td>
									<td style='padding: 8px;'>- This code file demonstrates how to utilize FAISS as a vector database within a Langchain-based application<br>- Its primary purpose is to enable efficient similarity search and retrieval of high-dimensional vector embeddings, facilitating advanced natural language processing tasks such as document retrieval and question-answering<br>- By integrating FAISS, the code enhances the systems ability to quickly and accurately find relevant information from large datasets, supporting scalable and performant AI-powered workflows within the overall architecture.</td>
								</tr>
							</table>
							<!-- today's class faiss index Submodule -->
							<details>
								<summary><b>today's class faiss index</b></summary>
								<blockquote>
									<div class='directory-path' style='padding: 8px 0; color: #666;'>
										<code><b>⦿ 2-Langchain Basics.2.4-VectorDatabase.FAISS.today's class faiss index</b></code>
									<table style='width: 100%; border-collapse: collapse;'>
									<thead>
										<tr style='background-color: #f8f9fa;'>
											<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
											<th style='text-align: left; padding: 8px;'>Summary</th>
										</tr>
									</thead>
										<tr style='border-bottom: 1px solid #eee;'>
											<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.4-VectorDatabase/FAISS/today's class faiss index/index.faiss'>index.faiss</a></b></td>
											<td style='padding: 8px;'>Certainly! Please provide the code file youd like me to summarize.</td>
										</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<!-- PineCone Submodule -->
					<details>
						<summary><b>PineCone</b></summary>
						<blockquote>
							<div class='directory-path' style='padding: 8px 0; color: #666;'>
								<code><b>⦿ 2-Langchain Basics.2.4-VectorDatabase.PineCone</b></code>
							<table style='width: 100%; border-collapse: collapse;'>
							<thead>
								<tr style='background-color: #f8f9fa;'>
									<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
									<th style='text-align: left; padding: 8px;'>Summary</th>
								</tr>
							</thead>
								<tr style='border-bottom: 1px solid #eee;'>
									<td style='padding: 8px;'><b><a href='https://github.com/sumitatwork/KNA_AgenticAI/blob/master/2-Langchain Basics/2.4-VectorDatabase/PineCone/code.ipynb'>code.ipynb</a></b></td>
									<td style='padding: 8px;'>- SummaryThis code file serves as a foundational component for integrating vector similarity search within the larger application architecture<br>- Specifically, it demonstrates how to utilize Pinecone as a vector database to store, index, and retrieve high-dimensional embeddings generated from language models<br>- By enabling efficient similarity-based querying, this module facilitates advanced natural language understanding and retrieval capabilities, which are essential for building intelligent, context-aware AI agents and applications within the overall system.</td>
								</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
		</blockquote>
	</details>
</details>

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** JupyterNotebook
- **Package Manager:** Pip

### Installation

Build KNA_AgenticAI from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/sumitatwork/KNA_AgenticAI
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd KNA_AgenticAI
    ```

3. **Install the dependencies:**

**Using [pip](https://pypi.org/project/pip/):**

```sh
❯ pip install -r requirements.txt
```

### Usage

Run the project with:

**Using [pip](https://pypi.org/project/pip/):**

```sh
python {entrypoint}
```

### Testing

Kna_agenticai uses the {__test_framework__} test framework. Run the test suite with:

**Using [pip](https://pypi.org/project/pip/):**

```sh
pytest
```

---

## Roadmap

- [X] **`Task 1`**: <strike>Implement feature one.</strike>
- [ ] **`Task 2`**: Implement feature two.
- [ ] **`Task 3`**: Implement feature three.

---

## Contributing

- **💬 [Join the Discussions](https://github.com/sumitatwork/KNA_AgenticAI/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/sumitatwork/KNA_AgenticAI/issues)**: Submit bugs found or log feature requests for the `KNA_AgenticAI` project.
- **💡 [Submit Pull Requests](https://github.com/sumitatwork/KNA_AgenticAI/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/sumitatwork/KNA_AgenticAI
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/sumitatwork/KNA_AgenticAI/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=sumitatwork/KNA_AgenticAI">
   </a>
</p>
</details>

---

## License

Kna_agenticai is protected under the [LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## Acknowledgments

- Credit `contributors`, `inspiration`, `references`, etc.

<div align="left"><a href="#top">⬆ Return</a></div>

---
