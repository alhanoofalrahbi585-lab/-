AI-powered educational platform with role-based access.
Comprehensive Blueprint: AI-Powered Arabic Educational Platform
Core Objective: Build a production-ready Web Application in Full Arabic (RTL). The app must be a "Clean Slate" (No dummy data) and use a role-based access system.
1. Enhanced Authentication Logic:
• Role Trigger: System must parse the first character of the password:
• 'S': Student dashboard + AI Tutor.
• 'T': Teacher dashboard + AI Grading/Planning Assistant.
• 'P': Parent dashboard + Attendance/Progress tracking.
• Security: Use secure hashing for passwords and persistent sessions.
2. Deep Service Details:
• Teacher Module: Includes a "Lesson Generator" where AI suggests lesson plans based on a title. Also, a "Student List" with a button to send auto-generated progress reports to parents.
• Student Module: Includes a "Homework Help" chat sidebar where the AI explains steps without giving final answers immediately.
• Parent Module: A visual "Success Map" showing the child's strengths and weaknesses via AI analysis of grades.
3. Advanced Communication (The Chat):
• Real-time Messaging: Build a chat interface using WebSockets (or Supabase Realtime).
• Permissions: Students can only message their teachers; Parents can message teachers but not other students.
4. Three Main Structural Sections:
• Smart Workspace: A rich-text editor (like Notion) that supports Arabic fonts and an "AI Rewrite" button to improve text.
• Digital Archive: A grid-view library to store PDF files and saved notes with a search bar.
• Settings: Profile photo upload, password reset, and a "Dark Mode/Light Mode" toggle.
5. Technical Requirements & UI:
• UI/UX: Use a modern "Glassmorphism" or "Clean Material" design.
• Navigation: Fixed Sidebar (Desktop) and a floating Bottom Dock (Mobile).
• Stack: Use React/Next.js for Frontend and Supabase for Auth/Database/Storage.
• AI Integration: Securely connect Gemini or GPT-4o API for all AI features.
