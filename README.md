# Interactive Bedtime Story Generator

## Overview

This project uses **GPT-4o**, a cutting-edge AI model from OpenAI, to craft **personalized and interactive bedtime stories** for children. Parents can provide details about their child’s day, favorite characters, and story preferences, and the AI generates unique, engaging, and calming bedtime stories with interactive elements.

---

## Key Features

- **Personalization**: Stories are customized based on the child’s activities, mood, and interests.
- **Interactivity**: Includes choices that guide the story's progression, making it an engaging experience.
- **Flexibility**: Parents can specify story themes, length, and tone (e.g., adventurous, calming, funny).
- **Continuous Improvement**: Feedback from parents helps improve story quality over time.

---

## Workflow

### Step 1: Input Collection

Parents provide:

- **Child's Name**: Used to make the story relatable.
- **Favorite Characters**: Central figures in the story.
- **Day's Activities**: Themes and settings derived from daily events.
- **Story Mood**: (e.g., calming, adventurous).
- **Story Length**: Short (5 minutes) or longer narratives.

### Step 2: Story Generation

- **GPT-4o** model is used to create the story based on the input.
- **Dynamic Prompts** are used to generate interactive sections where children can make choices to guide the story.

### Step 3: Interactivity

The story includes moments like:

- “Does [character] follow the glowing path or climb the tree?”
- Choices affect the subsequent story sections.

---

## Technical Stack

- **AI Model**: GPT-4o
- **Platform**: Mira Flows for workflow automation
- **API Integration**: OpenAI API for story generation
- **Conditional Logic**: For branching interactive storylines

---

## Installation

### Prerequisites

- Python 3.8 or above

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/shri29s/bedtime-story-generator-flow.git
   ```
2. Install dependencies:
   ```bash
   pip install .
   ```
