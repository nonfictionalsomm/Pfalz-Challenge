README: The Pfalz Wine Master's Challenge
1. Overview
"The Pfalz: A Wine Master's Challenge" is a single-file HTML web application designed as a comprehensive, data-driven study game for advanced wine students. The application's content is based exclusively on an in-depth research document covering the Pfalz wine region of Germany.

The core objective is to transform rote memorization into an interactive and engaging learning experience that teaches the "why" behind the facts, connecting geography, history, law, and gastronomy into a holistic understanding of the region.

2. Features
Seven In-Depth Modules: The game is divided into distinct modules covering every critical aspect of the Pfalz:

The Historian's Scroll (Interactive Timeline)

The Terroir Architect

The Ampelographer's Challenge

The Lawmaker's Desk

The Gastronome's Table

The Critic's Corner

Flashcard Study (Customizable)

Advanced Question Database: Each module features a robust bank of ~50 questions designed to test deep theoretical knowledge beyond simple recall.

Educational-First Design: The game is built on a "Teach, Don't Just Test" philosophy.

Immediate Factual Explanations: After answering a question in the Gastronome's module, a concise, accurate explanation sourced from the master research document is immediately displayed.

Context-Aware AI Tutor: An optional, integrated AI feature allows players to explore topics in greater depth.

Dynamic AI Prompting: The AI's role adapts to the player's performance.

A correct answer prompts the player to "Dive Deeper" into the topic.

An incorrect answer prompts the player to "Learn More," offering a chance to build foundational knowledge.

Fully Responsive: The application features a premium, dark-themed design using Tailwind CSS and is fully responsive for seamless use on desktop, tablet, and mobile devices.

Self-Contained: The entire game runs from a single index.html file, requiring no complex setup or dependencies.

3. Setup and Configuration
Running the Game
Save the application code as index.html.

Open the index.html file in any modern web browser (e.g., Chrome, Firefox, Safari, Edge).

Configuring the AI Features
The AI-powered educational features require a Google AI Studio API key.

Obtain an API Key: Visit https://aistudio.google.com/app/apikey to generate your free API key.

Enter the Key:

On the game's main menu, click the "⚙️ AI Settings" button.

Enter your API key into the input field in the modal.

Click "Save." The key will be stored in your browser's local storage for future sessions.

Security: Treat your API key like a password. Do not share it or commit it to public code repositories.

4. Gameplay Flow
Main Menu: Select from any of the six core quiz modules or the Flashcard Study tool.

Instructional Modals: Before each module begins, a pop-up will explain the objective and rules for that specific challenge.

Multiple-Choice Modules:

A quiz of 10 random questions is generated from the module's bank.

Select an answer. Immediate visual feedback (green for correct, red for incorrect) is provided.

For "The Gastronome's Table," an explanation panel will appear.

An optional AI button will appear, allowing you to explore the topic further.

Click "Next Question" to proceed.

The Historian's Scroll:

A set of historical events is displayed in a random order.

Tap the events to move them into your timeline in what you believe is the correct chronological order.

Click "Submit" to see your attempt compared side-by-side with the correct, dated timeline.

Flashcard Study:

First, select the topics you wish to include in your study deck.

Click to flip the flashcard and reveal the answer.

Use the "Previous" and "Next" buttons to navigate through your custom deck.

5. AI Prompting Strategy
The AI integration is guided by the principles outlined in the project's "Addendum: AI-Powered Educational & Contextual Features."

Specialist Persona: The AI is always prompted to act as a master sommelier, critic, or ampelographer specializing specifically in the Pfalz region.

Pyramid of Importance: The AI's analysis is structured to prioritize regional context above all else, ensuring all generated content is relevant to the game's subject.

Authoritative Synthesis: The AI is instructed to synthesize information from expert-level sources (e.g., JancisRobinson.com, Vinous) but to frame the response as its own expert opinion, creating unique and insightful content.

This approach ensures that every AI-generated response is accurate, relevant, and enhances the player's learning journey.
