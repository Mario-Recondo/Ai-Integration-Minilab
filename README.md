Model & Implementation

Model Name: gemini-3-flash-preview

Source: Google Generative AI (GenAI) SDK

Selection Rationale
I chose Gemini 3 Flash for its optimization toward speed and efficiency. In a document-based chat application low latency was preferred. Furthermore, its large context window allows it to allow for entire PDFs without losing track of information, providing a better experience compared to smaller-scale models.

Reflection on Responsible Ai use:
Developing an AI Document Assistant requires a "safety-first" mindset regarding data and accuracy. My primary focus was preventing hallucinations. By implementing strict system instructions ("Answer ONLY using the uploaded files"), I anchored the model to the provided text, ensuring it stays focused on the subject matter. I also made sure that users could not bypass the intended use of the application by prompting the Ai without adding a document. 

From a privacy standpoint, using cloud-based APIs necessitates transparency; users must know their data is processed externally. To promote responsible use, this assistant is designed as a productivity aid for verification, not a definitive source of truth for critical decision-making. 
