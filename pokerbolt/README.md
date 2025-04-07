# PokerBolt

A sophisticated real-time multiplayer Texas Hold'em poker application that delivers an authentic poker experience through a modern tech stack.

![PokerBolt](https://images.unsplash.com/photo-1606167668584-78701c57f90d?q=80&w=2400&auto=format&fit=crop)

## 📋 Project Overview

PokerBolt combines a Node.js/Express backend with a Next.js frontend to create a seamless poker gaming platform where users can play Texas Hold'em against other players in real-time. The system features robust authentication, real-time gameplay mechanics via WebSockets, and a responsive interface designed for both desktop and mobile devices.

## 🎮 Key Features

### User Experience
- **Secure Authentication** - Register and login with JWT-based security
- **Live Poker Games** - Experience real-time gameplay with instant updates
- **Custom Table Creation** - Set up tables with personalized blinds and buy-in ranges
- **Flexible Table Joining** - Join existing games with your preferred buy-in amount
- **User Profiles** - Monitor your chip balance and gaming performance
- **Responsive Design** - Enjoy optimal gameplay on any device

### Gameplay Elements
- **Complete Poker Flow** - From blinds to showdown with proper betting rounds
- **Real-time Actions** - Fold, check, call, raise with immediate feedback
- **Community Cards** - Experience the authentic reveal of flop, turn, and river
- **Pot Management** - Accurate pot calculations and distributions
- **Hand Evaluation** - Precise poker hand rankings and winner determination


## 🛠️ Technology Foundation

### Backend Architecture
- **Node.js & Express** - Robust server framework for API handling
- **MongoDB & Mongoose** - Flexible document database for game state persistence
- **Socket.IO** - Real-time bidirectional event-based communication
- **JWT Authentication** - Secure user authentication and authorization
- **RESTful API Design** - Clean endpoint structure for game management

### Frontend Implementation
- **Next.js & React** - Modern framework for responsive UI development
- **Tailwind CSS** - Utility-first CSS for elegant, consistent styling
- **shadcn/ui Components** - Beautiful, accessible interface elements
- **Socket.IO Client** - Seamless real-time updates and interactions
- **Dark/Light Mode** - Adaptable UI for different lighting preferences

## 🏗️ System Architecture

The application follows a client-server architecture with:

- **REST API** - Handles authentication, table management, and user data
- **WebSocket Connections** - Manages real-time game actions and state updates
- **Database Layer** - Stores user profiles, game history, and current tables
- **Game Logic Engine** - Processes poker rules, hand evaluations, and action validation

## 🃏 Game Flow

- **Table Creation** - Tables established with specific blinds and buy-in parameters
- **Player Seating** - Users join tables with their selected chip amounts
- **Automated Dealing** - Cards distributed to players at appropriate moments
- **Betting Rounds** - Pre-flop, flop, turn, and river with proper action sequence
- **Hand Resolution** - Winner determination through showdown or by fold
- **Continuous Play** - Seamless transition to new hands with remaining players

## 🎯 Performance & Reliability

- **Real-time State Management** - Immediate synchronization across all connected clients
- **Game State Persistence** - Protection against disconnections and browser refreshes
- **Scalable Architecture** - Designed to handle multiple simultaneous games
- **Comprehensive Error Handling** - Graceful management of edge cases and invalid actions

## 🎨 Visual Experience

![Poker Table](https://images.unsplash.com/photo-1541278107931-e006523892df?q=80&w=2400&auto=format&fit=crop)

The interface features a sleek, modern design with:

- **Intuitive Poker Table** - Clear visualization of players, cards, and betting actions
- **Action Controls** - Context-aware buttons that display only valid options
- **Card Animations** - Smooth transitions for card dealing and reveals
- **Chip Visualizations** - Realistic representation of betting amounts
- **Player Status Indicators** - Clear display of current turn and player actions

## 📊 Analytics & Insights

- **Game History** - Review past hands and outcomes
- **Player Statistics** - Track performance metrics and playing patterns
- **Real-time Feedback** - Immediate information on game actions and results

## 📚 Documentation

- [Backend Documentation](./backend/README.md) - Detailed backend setup, API documentation, and architecture
- [Frontend Documentation](./frontend/README.md) - Frontend features, components, and development guidelines
- [API Documentation](./backend/API_DOCUMENTATION.md) - Complete API reference with endpoints and data models


## 📄 License

MIT License - See LICENSE file for details

## 🙏 Acknowledgements

- [Socket.IO](https://socket.io/)
- [MongoDB](https://www.mongodb.com/)
- [Next.js](https://nextjs.org/)
- [shadcn/ui](https://ui.shadcn.com/)
