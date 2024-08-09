# Aana Examples

Welcome to the **Aana Examples** repository, a collection of example projects that demonstrate the powerful capabilities of the [Aana SDK](https://github.com/mobiusml/aana_sdk). The Aana SDK is a robust framework designed for building multimodal applications, enabling large-scale deployment of machine learning models for vision, audio, and language tasks. It also supports Retrieval-Augmented Generation (RAG) systems, facilitating the development of advanced applications such as search engines, recommendation systems, and data insights platforms.

## Example Applications

This repository contains example applications that showcase how to leverage the Aana SDK to create state-of-the-art multimodal applications.

### 1. [Chat with Video](./aana_chat_with_video/README.md)

A multimodal chat application that allows users to upload a video and ask questions about its content. The application processes both visual and audio information from the video to provide insightful answers. This example illustrates how to integrate video understanding with conversational AI.

- **Demo:** See the [Chat with Video Demo notebook](./aana_chat_with_video/notebooks/chat_with_video_demo.ipynb) for a step-by-step guide on using the application.

GitHub: [https://github.com/mobiusml/aana_chat_with_video](https://github.com/mobiusml/aana_chat_with_video)

### 2. [Summarize Video](./aana_summarize_video/README.md)

An application that summarizes the content of a video by extracting transcription from the audio and generating a concise summary using a Language Model (LLM). This example is part of the [Aana SDK tutorial](https://mobiusml.github.io/aana_sdk/pages/tutorial/) on building multimodal applications.

- **Tutorial:** Follow the [tutorial](https://mobiusml.github.io/aana_sdk/pages/tutorial/) for detailed instructions on how to build similar applications using the Aana SDK.

GitHub: [https://github.com/mobiusml/aana_summarize_video](https://github.com/mobiusml/aana_summarize_video)

## Getting Started

To explore these examples, clone this repository with the `--recurse-submodules` flag to ensure that the submodules are also cloned.

```bash
git clone --recurse-submodules https://github.com/mobiusml/aana_examples.git