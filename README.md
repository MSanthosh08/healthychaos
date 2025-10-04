# 🍎 Healthy Chaos – Gamified Nutrition Learning App

## 📌 Project Overview
**Healthy Chaos** is a fun, game-based app (built on Unity’s Kitchen Chaos open-source project) where students learn about **healthy eating habits, nutrition, and food sustainability** while playing interactive cooking challenges.  

Players prepare balanced meals, learn nutrition facts, and compete with friends on leaderboards.  
The game integrates **Firebase, Google AI tools, and Dialogflow/Gemini API** to provide real-time scoring, nutrition chatbots, and engaging learning experiences.  

---

## 🎯 Objectives
- Make learning about **balanced diets** fun and interactive.  
- Encourage **healthy food choices** through game mechanics.  
- Provide **nutrition facts** after each dish delivery.  
- Enable competition with friends using **Firebase leaderboards**.  
- Offer a **nutrition chatbot** for Q&A using AI tools.  

---

## 🛠️ Tech Stack
- **Game Engine**: Unity (Kitchen Chaos base project)  
- **Backend**: Firebase (Authentication, Firestore, Leaderboards)  
- **AI Tools**: Dialogflow / Gemini API (Nutrition Q&A chatbot)  
- **Cloud**: Google Cloud Platform (Compute, APIs)  
- **UI/UX**: Unity UI Toolkit, Custom Icons & Assets  

---

## 👥 Team Members & Responsibilities

### **1. Core Developer – Game Mechanics & Recipes**
- Learn: Unity basics, ScriptableObjects, prefabs, Kitchen Chaos workflow.  
- Tasks:  
  - Replace junk food prefabs with healthy food (fruits, veggies, proteins).  
  - Update `RecipeSO.cs` → define **balanced meal recipes**.  
  - Modify `DeliveryManager.cs` → only healthy recipes requested.  
  - Adjust scoring rules (balanced = high score, junk = penalty).  

---

### **2. Nutrition Developer – Facts & Learning Layer**
- Learn: Unity UI, Scriptable data fields, popup scripting.  
- Tasks:  
  - Extend `RecipeSO.cs` with nutrition info (calories, vitamins, tips).  
  - Create `NutritionFactsUI.cs` → popup after a recipe is delivered.  
  - Integrate with `DeliveryResultUI.cs` → display nutrition facts.  
  - Collect & prepare dataset of nutrition facts for each recipe.  

---

### **3. Cloud Developer – Firebase Leaderboard & Backend**
- Learn: Firebase Authentication, Firestore/Realtime DB, Unity Firebase SDK.  
- Tasks:  
  - Create `FirebaseManager.cs` → login, authentication, score upload.  
  - Connect scores to `GameManager.cs` → upload after each round.  
  - Create `LeaderboardUI.cs` → display global/top scores in-game.  
  - Test cross-device leaderboard functionality.  

---

### **4. AI/ML Developer – Chatbot Integration**
- Learn: Dialogflow basics OR Gemini API calls, UnityWebRequest.  
- Tasks:  
  - Build `NutritionChatbot.cs` → chatbot panel in Unity.  
  - Integrate with Dialogflow/Gemini API for nutrition Q&A.  
  - Ensure responses show in-game chat panel.  
  - Keep chatbot lightweight and student-friendly.  

---

### **5. UI/UX Designer – Branding & Presentation**
- Learn: Unity Canvas, layouts, buttons, sprite replacement.  
- Tasks:  
  - Update `MainMenuUI.cs` → rebrand to “Healthy Chaos” / “Nutrition Quest.”  
  - Replace junk food icons with fruits/veggies in UI.  
  - Design nutrition popup, leaderboard, chatbot UI panels.  
  - Polish menus, score screens, and transitions.  
  - Record final gameplay demo video.  

---

## 🗓️ Timeline (4 Days)
- **Day 1**: Setup & asset replacement, Firebase setup, chatbot test, nutrition dataset prep, UI mockups.  
- **Day 2**: Recipe & scoring updates, nutrition popup integration, Firebase login/score upload, chatbot test, UI updates.  
- **Day 3**: Firebase leaderboard in-game, chatbot fully working, nutrition facts polished, full UI branding.  
- **Day 4**: Bug fixes, integration testing, demo video recording, final presentation.  

---

## 🚀 Expected Outcome
- A rebranded **Kitchen Chaos → Healthy Chaos** game.  
- Players cook **healthy recipes** instead of junk food.  
- **Nutrition facts popup** after each dish delivered.  
- **Firebase leaderboard** to compete with friends.  
- **Nutrition chatbot** (AI-based) for interactive learning.  
- A polished, fun, and educational experience promoting **healthy eating habits**.  

---
