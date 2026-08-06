# Giovanni Sullutrone

**I do stuff that I like, pretty much.**

If you want my unprofessional opinion on what I do, I simply keep up with papers, get excited, and try to break or find new stuff.

If you want the more professional summary of my CV, you can find it down here. It is LLM-generated and reviewed by me, sorry but there is never enough time...

I am a PhD researcher in Information and Communication Technologies at the [University of Modena and Reggio Emilia](https://www.unimore.it/). My research examines how LLM systems behave when a request involves safety boundaries, incomplete information, sensitive data, or external evidence. I am particularly interested in evaluations that expose behaviour that are commonly given less attention: whether a refusal is justified, whether retrieval changes the model's decision, and whether an agent can recognize what it needs from a user before acting.

My PhD is supervised by Prof. Sonia Bergamaschi and is expected to conclude on **31 October 2026**. I have also worked with Dr. Georgia Koutrika at the [DARE Lab](https://darelab.athenarc.gr/) on the evaluation of Text-to-SQL systems.

## Selected research

- **[COVER: Context-Driven Over-Refusal Verification in LLMs](https://aclanthology.org/2025.findings-acl.1243/)** — Introduces context-driven over-refusal: cases in which a model rejects a benign task because of the documents supplied with it. The study shows that refusals depend on both the requested task and the evidence, with translation and summarization affected more strongly than question answering. *Findings of ACL 2025.*

- **[Text-to-Refused-SQL: A Comprehensive Evaluation of LLMs Refusal in Text-to-SQL](https://ceur-ws.org/Vol-4182/paper32.pdf)** — Studies refusal when a database schema contains personal or sensitive fields. Across models and prompting conditions, legitimate requests can be misread as attempts to bypass safeguards, revealing a tension between privacy protection and usable database access. *SEBD 2025.*

- **[Sensitive Topics Retrieval in Digital Libraries: A Case Study of ḥadīṯ Collections](https://link.springer.com/chapter/10.1007/978-3-031-72440-4_5)** — Evaluates retrieval over historically sensitive religious documents through questions generated from the collection itself. The results show that modern embedding models can rank sensitive passages lower than comparable non-sensitive ones, making parts of a digital library less visible to researchers. *TPDL 2024.*

- **[ABISS: Evaluating Text-to-SQL Systems Through Agent Interaction](https://arxiv.org/abs/2607.23340)** — Unifies the reasons why a database question may be ambiguous or impossible to answer, then evaluates complete interactions with simulated users. The benchmark shows that agents often recognize that a request is problematic without identifying why, and still struggle to translate useful clarification into the correct SQL query. [Code and benchmark](https://github.com/giosullutrone/ABISS-Evaluating-Text-to-SQL-Systems-Through-Agent-Interaction).

## Research methods and tools

My work combines LLM evaluation, benchmarking, multi-agent data generation and validation, retrieval-augmented generation, Text-to-SQL, and synthetic data. 

I mainly work with **Python, PyTorch, Hugging Face, vLLM, TRL, Docker, and SQL**.

## Contact

[Email](mailto:giovanni.sullutrone@unimore.it) · [ORCID](https://orcid.org/0009-0006-5556-1827) · [ACL Anthology](https://aclanthology.org/people/giovanni-sullutrone/) · [LinkedIn](https://www.linkedin.com/in/giovanni-sullutrone/) · [DARE Lab profile](https://darelab.athenarc.gr/people/giosullutrone/)
