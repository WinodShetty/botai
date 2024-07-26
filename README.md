# AI Chat Feedback Application

## Overview

This project is a ReactJS web application that allows users to chat with a mock AI model and provide feedback on the AI's responses. Users can like or dislike individual responses, rate the overall conversation, and provide subjective feedback. Past conversations are saved and can be revisited, along with the feedback provided. Additionally, users can view all feedback across conversations and filter them based on ratings. The application also supports toggling between light and dark modes.



## Features

- Chat with a mock AI model.
- Like/dislike AI responses using thumbs up/thumbs down buttons.
- Provide a rating out of 5 at the end of the conversation.
- Provide subjective feedback at the end of the conversation.
- Save and revisit past conversations along with feedback.
- View all feedback across conversations with filtering options.
- Toggle between light and dark modes.

## Technologies Used

- ReactJS
- Material-UI (for UI components)
- JSON (for mocking AI responses)
- Vercel (for deployment)


Usage
Chat with the AI: Type your message in the input box and press Enter to send. The AI will respond with a pre-defined response from the JSON file.
Like/Dislike Responses: Hover over an AI response to reveal thumbs up and thumbs down buttons. Click to like or dislike the response.
Rate Conversation: At the end of the conversation, provide a rating out of 5 using the star rating component.
Provide Feedback: Enter your subjective feedback in the provided text area.
View Past Conversations: Click on the past conversations panel to revisit previous chats and see the feedback provided.
View All Feedback: Navigate to the feedback view to see all feedback points across conversations with filtering options.
Toggle Light/Dark Mode: Use the toggle switch to switch between light and dark modes.
Design Decisions
UI Library: Material-UI was chosen for its rich set of pre-built components and ease of customization, which helped in building a polished UI quickly.
State Management: React's built-in state management was used for simplicity and ease of use in a small-scale application.
Feedback Storage: Feedback is stored in a local state to keep the implementation simple. In a real-world scenario, this would be replaced with a backend service.
