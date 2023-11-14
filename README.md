# Fiction Generator: Attempts for fictional content generation

Edited by Muyang Li, Qinwen Ge

## Background & Ideas

Wi

## General structure

## Models and Datasets

## Our methods

### Design with ChatGPT API

#### Overview
In our Fiction Generator project, we leverage OpenAI's GPT API to enable the generation of detailed and creative fictional content. This integration is central to transforming user inputs on various aspects of fiction – such as background, characters, and plot – into rich narrative elements.

#### Implementation Process

##### API Integration

##### Function Design
- **Centralized Function for Description Generation**: Instead of creating multiple functions for different aspects of fiction generation, we designed a versatile function dynamically constructs prompts for the GPT model based on user inputs across various categories (like world type, character identity, plot development, etc.).
- **Iterative Refinement Function**: To enhance the depth and quality of the generated content, we implemented an function iteratively expands on the narrative, adding layers of detail with each iteration.
- **Combination and Refinement of Descriptions**: In the end, we aggregate the outputs from different categories and refines them collectively, ensuring a more cohesive and comprehensive narrative.

##### Gradio Interface and GPT-3 Interaction
- **Tab-Based User Interface**: Our Gradio interface is organized into tabs corresponding to different elements of storytelling. This design facilitates user interaction and organizes the input process logically.
- **Dynamic Prompt Construction**: Our fiction generator can construct prompts tailored to the user's inputs, which are then passed to the GPT model for content generation.
- **Adaptive Output Generation**: The integration of GPT with our function allows for flexible and context-sensitive generation of narrative content, adapting to the diverse and creative inputs provided by users.

### Design with Chatgpt builder

### Design with finetuned model

 

## Demo

## Limitations and Critical Analysis

## Resources

## Links

## Reference

