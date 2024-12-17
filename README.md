Large Language Model Generation of Storylets

Description: This material contains LLM prompts and outputs, tree formatting information, and human-authored trees used to explore using LLMs in creating branching trees that can be used in storylet authoring. The purpose of this material is to enable the reproduction of prompting approaches, provide insight into iteration approaches, and see the results that were evaluated by interactive digital narrative authors. It also contains the survey released for the authors to respond to questions about the quality and usefulness of these prompting strategies in the context of their workflow. 

Size: 

Platform: All files are in .txt format and are human-readable, but can be used with an LLM system for reproduction.

Environment: Any computer with access to an API to a provider that hosts LLM models; alternatively, can be used on a user's self-hosted model.

Major Component Description: The major components of this data set consists of the prompts used for tree generation, which consist of story and character descriptions, authorial role information, tone and style directions, and a specific JSON output format. Supplementary files provided detail survey format, prior generation attempts, and the output used for evaluation in our studies.

Detailed Run Instructions: Prompts can be run using any LLM model, for which online access can be found at sites such as https://together.ai. The specific model used in our research was Llama-3.1-8B-Instruct, which can be found at https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct. We used a temperature of 0.9 and an automatic token output length.

Output Description: The desired output of all new prompts can be found in the file titled "Output_Format.txt". Examples of outputs from prompts can be found in files ending in "_output.txt".

Contact Information: Samuel Shields - samshiel@ucsc.edu
