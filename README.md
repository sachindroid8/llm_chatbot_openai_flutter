# llm_chatbot_openai

A very simple chatbot application using OpenAI API that can be deployed to multiple platforms like web, desktop and mobile with Flutter. A Flutter project with chat ui and using OpenAI API service. 

## Complete Tutorial walkthrough to build from scratch
Refer the youtube video for a full walkthrough with key concepts on how to build a multi-platform chatbot with OpenAI and Flutter. 
[Video Tutorial: Build Your Own Multi-Platform Chatbot with OpenAI and Flutter | Easy Step-by-Step Guide](https://youtube.com/live/9m-HK9SiZoA)

## Configure API Key

Obtain your OpenAI API key and replace the key in openai_service.dart file. 
static const apiKey = '<PLACE YOUR API KEY HERE>'; 

## Modify the prompt to your use case

Modify the openai_service.ChatGPTAPI function to include your own prompt or context for the API. 

{
      "role": "user",
      "content":
          "<REPLACE THIS WITH YOUR CONTEXT ABOUT YOUR CHATBOT>.$prompt",
}

This project uses the following flutter packages https://pub.dev/packages/flutter_chat_ui
The package acts as a main source to design the chat interface. Credits to the developers for creating an amazing and simple package to easily build chat interfaces. 

This project is a starting point for a Chatbot Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
