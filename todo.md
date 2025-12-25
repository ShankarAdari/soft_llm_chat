# Soft Tone LLM Chat - Project TODO

## Database & Schema
- [x] Design and implement chat_conversations table for storing conversation sessions
- [x] Design and implement chat_messages table for storing individual messages
- [x] Design and implement user_preferences table for storing theme and background selections
- [x] Create database migrations

## Backend API
- [x] Implement LLM integration with soft, warm system prompt
- [x] Create chat.createConversation procedure
- [x] Create chat.sendMessage procedure with streaming support
- [x] Create chat.getConversationHistory procedure
- [x] Create chat.deleteConversation procedure
- [ ] Implement voice transcription integration
- [ ] Create voice.transcribeAudio procedure
- [ ] Implement image generation integration
- [ ] Create image.generateImage procedure
- [x] Create preferences.getTheme procedure
- [x] Create preferences.updateTheme procedure
- [x] Create preferences.updateBackground procedure
- [ ] Write vitest tests for all procedures

## Frontend - Chat Interface
- [x] Create responsive chat container layout
- [x] Implement message list with auto-scroll to latest
- [x] Create message input area with send button
- [x] Implement message rendering with markdown support
- [x] Add loading states and message streaming animation
- [x] Create conversation sidebar with history list
- [x] Implement new conversation button
- [x] Add delete conversation functionality

## Frontend - Theme System
- [x] Create theme context and hook
- [x] Implement theme switcher component (light/dark/custom)
- [x] Design color palette for light theme
- [x] Design color palette for dark theme
- [x] Add custom theme color picker
- [x] Update global CSS with theme variables

## Frontend - Animated Backgrounds
- [x] Create animated background component library
- [x] Implement gradient animation background
- [x] Implement particle animation background
- [x] Implement wave animation background
- [x] Implement floating shapes animation background
- [x] Create background selector component
- [x] Implement background customization options
- [x] Add smooth transitions between backgrounds

## Frontend - Voice Input
- [x] Create voice input button component
- [x] Implement audio recording functionality
- [ ] Add audio playback for recorded messages
- [ ] Integrate transcription API call
- [ ] Display transcription status and results
- [x] Handle microphone permission requests
- [x] Add visual feedback during recording

## Frontend - Image Generation
- [x] Create image generation trigger in chat interface
- [x] Display generated images in chat messages
- [ ] Add image download functionality
- [x] Show generation status and loading states
- [x] Handle image generation errors gracefully

## Frontend - Responsive Design
- [ ] Test mobile layout (< 640px)
- [ ] Test tablet layout (640px - 1024px)
- [ ] Test desktop layout (> 1024px)
- [ ] Optimize touch interactions for mobile
- [ ] Test keyboard navigation and accessibility
- [ ] Ensure proper spacing and readability on all devices

## Frontend - Chat History
- [x] Implement conversation persistence to database
- [x] Load chat history on page load
- [x] Display conversation list in sidebar
- [x] Implement conversation switching
- [ ] Add search/filter for conversations
- [x] Implement conversation deletion with confirmation

## Styling & Polish
- [x] Create consistent color scheme for warm, approachable feel
- [x] Design and implement custom UI components
- [x] Add micro-interactions and transitions
- [x] Implement proper loading and empty states
- [x] Add error handling and user feedback
- [x] Optimize performance and animations

## Testing & Deployment
- [ ] Test all features end-to-end
- [ ] Test theme switching and persistence
- [ ] Test voice input and transcription
- [ ] Test image generation
- [ ] Test chat history persistence
- [ ] Test responsive design on multiple devices
- [ ] Create checkpoint for deployment
