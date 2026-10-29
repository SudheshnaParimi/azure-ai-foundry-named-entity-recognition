# azure-ai-foundry-named-entity-recognition
Exploring Named Entity Recognition (NER) using Azure AI Foundry Language Playground, focusing on entity extraction and confidence score analysis with Travel and Banking samples.


Named Entity Recognition Using Azure AI Foundry

Overview

This experiment explores Named Entity Recognition (NER) using Microsoft Azure AI Foundry’s Language Playground.

The objective is to understand how Azure AI Language identifies and extracts information such as names, dates, locations, and products from unstructured text.

Tools Used

* Platform: Microsoft Azure AI Foundry
* Tool: Language Playground
* Feature: Extract Named Entities
* API Version: 2025-05-15-preview
* Model Version: latest (GA)
* Language: English

Experiment Procedure

1. Opened Azure AI Foundry and navigated to the Language Playground.
2. Selected Extract Information → Extract Named Entities.
3. Used the Travel sample to observe entity extraction.
4. Used the Banking sample to identify additional entities.
5. Examined the extracted entities and their confidence scores.
6. Captured screenshots of the results.

Observations

Sample 1: Travel

The model identified entities such as:

* Los Angeles – City (100% confidence)
* wife – PersonType (98% confidence)
* August 17th, 2019 – Date
* Hollywood Boulevard – Location

Sample 2: Banking

The model identified entities such as:

* Mateo Gomez – Person (100% confidence)
* August 17th – Date (80% confidence)
* Chicken parmigiana – Product
* Contoso Restaurant – Location

Results

Azure AI Foundry successfully identified multiple named entities from the provided sample texts.

The experiment demonstrated how confidence scores indicate the model’s certainty about individual entity classifications.

Conclusion

This experiment provided practical experience with Named Entity Recognition using Azure AI Foundry.

It demonstrated how AI can extract structured information from unstructured text, forming a foundation for applications such as chatbots, virtual assistants, and AI agents.

Experiment Documentation

The complete experiment report, including screenshots and detailed observations, is available in the project documentation.
