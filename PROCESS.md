# Process

## Tools

- **Doubao**: Used during the early brainstorming phase to organize the initial idea, explore the website layout, and define the main vocabulary relationship categories. Later used with Trae AI Agent to modify and improve the website after the VS Code AI assistant reached its usage limit.
- **ChatGPT (GPT)**: Used to develop the initial concept into a PRD and generate detailed prompts for the VS Code AI assistant to build the website's basic architecture. Continued to assist with editing project documentation, refining text content, and preparing development instructions.
- **VS Code AI Assistant**: Used during the early development phase to build the website's basic structure and implement the initial features based on GPT-generated prompts. Development later moved to Trae AI Agent after the available usage quota was exhausted.
- **Trae AI Agent**: Used for subsequent code modifications, API research and integration, data monitoring, relationship management, debugging, and feature updates. After the Doubao usage quota was exhausted, Trae became the primary tool for all further code development.
- **GitHub**: Used to manage source code and track development changes through commits and pull requests.

## Development Process

- **Initial Development**: Started with the project concept and used GPT-generated prompts in VS Code to establish the website's basic architecture and core interactions.
- **AI Tool Transition**: Switched from the VS Code AI assistant to Trae AI Agent and Doubao when the VS Code usage quota was exhausted. After the Doubao quota was also exhausted, continued all code development with Trae.
- **API Integration**: Researched and integrated external vocabulary APIs to collect multilingual vocabulary and relationship data. One API became unavailable due to a remote service failure. After investigating possible solutions, the project stopped using that API and added 20 vocabulary relationship entries to maintain the available dataset and continue development.
- **Relationship Data Management**: Initially explored individual verification of vocabulary relationships. The large number of entries made manual verification impractical, so the approval status was changed in bulk to allow the complete relationship network to appear during development. This decision prioritized graph completeness over individual verification.

## Kept

- **Automatic Initial Word Display**: Kept the suggestion to display a starter word and its relationship graph when users first enter the website. This allows users to experience the main interaction immediately.
- **Random Word Discovery**: Kept the dice feature to display a random vocabulary entry. This provides another way to explore the available vocabulary when a search returns no results.
- **Separate Relationship Categories**: Kept the distinction between cross-language equivalents and semantic relationships to make the vocabulary network easier to understand.
- **Expanded Vocabulary Dataset**: Added 20 vocabulary relationship entries after an external API became unavailable. This helped maintain the available content for the interactive experience.

## Rejected

- **Gamified Learning Features**: Rejected daily streaks, score counters, and pop-up quizzes. The project focuses on visual vocabulary exploration rather than test-based language learning.
- **Individual Manual Verification of Every Relationship**: Changed the original verification approach because checking hundreds of vocabulary connections individually was beyond the available development time. All existing relationship entries were approved in bulk to display a more complete network. This was a development shortcut, and the accuracy of individual relationships remains a limitation.
- **Continued Use of the Unavailable API**: Rejected further attempts to integrate the API after its remote service failure. Switched to other available data sources and additional vocabulary entries instead.

## User Trial

- **Search Feedback**: During user testing, a tester found that some words could not be found through the search function. This was mainly related to the limited size of the current vocabulary dataset.
- **Design Response**: Retained the dice feature so users could discover randomly selected words even when they could not find a specific word.
- **Future Improvement**: The current dataset is still too small to support use as a comprehensive dictionary. Future development will focus on integrating more vocabulary APIs and expanding the dataset to improve search coverage and relationship diversity.