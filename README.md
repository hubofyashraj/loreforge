
Lore Forge – Detailed Game Design Summary

Concept Overview:
Lore Forge is an innovative multiplayer storytelling game where two teams compete to influence the direction and tone of a shared narrative. Inspired by elements of Dungeons & Dragons and AI Dungeon, this game introduces structured, team-based storytelling with built-in scoring and evaluation mechanisms powered by AI. It blends creativity, competition, and intelligent judgment into a unique gameplay experience.

Core Game Mechanics:

1. Game Initialization
• AI generates an opening story prompt that defines the setting, characters, and tone.

• Two teams are formed (e.g., Hero Team vs Villain Team, or Emotional vs Logical themes).



2. Turn-Based Storytelling
◇ Teams alternate turns.

◇ Only one player per team submits a move per round.

◇ Each "move" is a short paragraph continuing the narrative from their team’s perspective.

◇ AI evaluates each move in real time based on:
▪ Narrative quality

▪ Creativity

▪ Emotional impact

▪ Logical coherence

▪ Role alignment





3. Role System (Optional but Powerful)
Each team member takes on a role such as:
◇ Plot Architect (keeps story structured)

◇ Dialogue Specialist (focuses on conversations)

◇ Emotional Anchor (adds depth and feels)

◇ Tactician/Strategist (plans twists or conflicts)


AI checks if a submission matches the intended function of that role.

4. Scoring
◇ Each turn receives a score in multiple categories:
▪ Creativity

▪ Logical consistency

▪ Role adherence

▪ Narrative flow

▪ Emotional impact



◇ Scores are tracked per team.

◇ Optionally, penalties may apply for moves that break immersion or feel rushed.



5. Ending the Story
◇ Fixed rounds (e.g., 8–12), or dynamically end when a climax/resolution is achieved.

◇ AI summarizes the full story and analyzes structure.

◇ The winning team is chosen based on:
▪ Total score

▪ How well they guided the story toward their goal

▪ Narrative balance and emotional payoff





Technology Stack

Frontend
◇ React + Next.js

◇ Components:
▪ Text editor for moves

▪ Story log viewer

▪ Scoreboard

▪ Role assignment UI





Backend (Optional in MVP)
◇ Node.js or Next.js API routes

◇ Redis or Firebase for session management

◇ JWT/Firebase Auth for user roles and multiplayer



AI
◇ GPT-3.5 / GPT-4 via OpenAI API for story generation and scoring

◇ Optionally: Host open-source models (e.g., Mistral, LLaMA 2) via Ollama or Hugging Face on Azure

◇ AI handles:
▪ Story continuation

▪ Input evaluation

▪ Feedback to users

▪ Climax/ending detection





Solo Developer Strategy (MVP First)

🔹 Phase 1: Mini Prototype
◇ Single-page app

◇ Submit move → AI continues story

◇ Display score + story log



🔹 Phase 2: Roles + Team System
◇ Let teams assign player roles

◇ AI checks move alignment with role



🔹 Phase 3: Smarter AI Judgment
◇ Feed model example movie scripts + critical reviews for better evaluation (later stage)

◇ Train or prompt-engineer to rate emotional payoff, logic, etc.



🔹 Phase 4: Full Game Loop
◇ Full session engine (rounds, scores, final summary)

◇ Game room system (for lobbies or multi-matches)



Stretch Features
◇ Multiplayer with lobbies

◇ Visual AI illustrations of story scenes

◇ Real-time sentiment tracking

◇ Spectator voting

◇ Leaderboards or persistent characters

◇ Branching storylines with side quests



Why It’s Unique
Unlike DnD or AI Dungeon:
◇ Structured scoring

◇ Opposing teams with roles

◇ AI enforces balance, avoids abrupt endings

◇ Mixes emotional storytelling (like The Martian) with action-driven arcs



Potential Use Cases
◇ Team-building games

◇ Creative writing practice

◇ Classroom storytelling activities

◇ Narrative prototyping for writers and filmmakers



Final Thoughts
Lore Forge combines AI creativity with game mechanics and storytelling. It's not about building another dungeon master — it's about building a competitive collaborative fiction playground where strategy, emotion, and narrative skill collide.
