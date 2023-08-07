# FlowChartGenerationNLP

In this mini project, i have built a tool that generates a flowchart from natural language using Generative AI.

MermaidJS is an online tool that converts a well-formatted text to a flowchart. You can play around with mermaidjs over here – https://mermaid.live

Here is an example that converts structured text into flowchart flowchart TD

A[Christmas] -->|Get money|
B(Go shopping)
B --> C{Let me think}
C -->|One| D[Laptop]
C -->|Two| E[iPhone]
C -->|Three| F[fa:fa-car Car]


For example, the user could provide the following natural language prompt:
For christmas shopping, we need first need to have some money. Then we go shopping, and 
then think what we want to buy. The things we can buy are iPhone, car or laptop.


My tool should be doing the following:

1. Converted user’s natural language to structured mermaidjs markup using OpenAI API
   
2. Used mermaidjs library or service to generate the flowchart as a PNG file

3. contexts are being maintained at each stage for better results.

Tools: Python, Langchain, redis ,openai ,prompt engineering

  
