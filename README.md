# Pairsona (MBTI-Based User Matching App)

## Overview

`Pairsona` matches users based on their Myers-Briggs Type Indicator (MBTI) personality types, providing compatibility insights and enabling user interactions such as connection requests and messaging. The goal is to foster meaningful new encounters and relationships.

---

### **Database Tables**

- **`users`**: Stores user profiles, MBTI types, locations (latitude/longitude), and other relevant details.
- **`matches`**: Manages connection requests, accepted connections, and match statuses.
- **`messages`**: Stores chat history between connected users.

---

### **Sensitive Information**

- User profiles (name, email, bio, profile picture).
- MBTI test results (viewable only by the user and their accepted matches).
- One-on-one messaging content.

---

### **Functionality**

- **Generate Compatible Users**: Recommend users based on MBTI compatibility and geographic proximity.
- **Compatibility Insights**: Display brief compatibility descriptions for different MBTI type pairings.
- **User Interactions**:
  - Send, accept, or decline connection requests.
  - One-on-one messaging for connected users.
  - Option to remove connections.

---

### **User Flow**

1. **Sign Up**: Users register with their basic details.
2. **MBTI Quiz**: Users complete a quiz to determine their MBTI type.
3. **View Matches**: Potential matches are shown based on:
   - MBTI compatibility.
   - Closest geographic proximity (using latitude and longitude).
4. **Connect & Chat**:
   - Send connection requests.
   - Accept or decline requests.
   - Message connected users.
   - Remove connections if desired.

---

### **Stretch Goals**

- **Enhanced Matching Algorithm**: Improve accuracy with additional factors like interests and communication styles.
- **Real-Time Messaging**: Use `socket.io` or Firebase for live chat functionality.
- **Additional Personality Tests**: Integrate other personality assessments (e.g., Big Five, Enneagram).
- **Profile Customization**: Allow users to add more profile details and images.

---

## Project Details

| **Instruction** | **Description** | **Pairsona** |
|-----------------|-----------------|--------------|
| **Stack**       | Tech stack used for the project. | Node.js/Express - PostgreSQL - React - JavaScript - HTML - CSS - OpenCage API - Google Places API |
| **Focus**       | Is the front-end UI or the back-end going to be the focus of your project? Or are you going to make an evenly focused full-stack application? | Full-stack application with an emphasis on personality matching and compatibility algorithms. |
| **Type**        | Will this be a website? A mobile app? Something else? | Website |
| **Goal**        | What goal will your project be designed to achieve? | To match users based on their MBTI personality types, helping them find friends, partners, or colleagues. |
| **Users**       | What kind of users will visit your app? In other words, what is the demographic of your users? | Individuals interested in personal growth, social development, and finding compatible connections based on MBTI types. |
| **Data**        | What data do you plan on using? How are you planning on collecting your data? | **Data Sources:** <br> - MBTI quiz data <br> - OpenCage API for latitude and longitude <br> - Google Places API for location suggestions <br><br> **Data to Collect:** <br> - MBTI types <br> - Compatibility insights <br> - User profiles (name, bio, profile picture) <br> - Connection requests and matches <br><br> **Collection Method:** <br> - Integrate an MBTI quiz <br> - Use `OpenCage API` and `Google Places API` to fetch location data <br> |

---
