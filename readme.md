# Chad – A Volatile Web-Based Messaging Application

## Overview

Chad is a web-based volatile messaging application built using Flask and real-time communication technologies. The primary purpose of the application is to provide temporary, session-based communication where messages are not permanently stored.

Users authenticate using a one-time password (OTP) system and can join chat rooms to send and receive messages in real time.

The system is designed around volatility and privacy. Messages are cleared when users disconnect, and the server memory is periodically reset based on a scheduled wipe cycle. This design simulates lightweight, walkie-talkie-style communication that prioritizes immediacy over permanence.

The application can be deployed on cloud container platforms for public access, while development and testing may also be performed on lightweight hardware such as a Raspberry Pi Zero 2 W.

---

## What Does the Application Do?

Chad allows users to:

* Log in using OTP-based authentication
* Join chat rooms
* Send and receive real-time messages
* View currently online users
* Experience temporary communication where messages are not persistently stored

Real-time messaging is implemented using Flask-SocketIO to enable instant broadcasting of messages between connected clients.

The system is intentionally designed to avoid long-term message storage. Messages exist only during active sessions, reinforcing the volatile communication model.

---

## Why Is It Worth Doing?

This project integrates several foundational web development concepts into a single application, including authentication systems, routing, template rendering, session management, and real-time communication.

Building Chad provides practical experience in designing systems that resemble modern messaging platforms while exploring privacy-oriented communication models. Unlike conventional messaging applications, Chad emphasizes ephemeral data handling and presence-based interaction.

The volatility constraint introduces additional design challenges, requiring careful handling of session memory, socket connections, and scheduled server resets. This makes the project both technically meaningful and academically relevant.

---

## Target Audience

The application is designed for users who prefer privacy-focused, temporary communication systems. Potential users include:

* Individuals who do not want message history stored
* Users looking for lightweight real-time chat platforms
* People who prefer walkie-talkie-style interaction
* Privacy-conscious users seeking minimal data retention

Although primarily an academic project, the application demonstrates practical implementation of ephemeral messaging systems.

---

## What Makes It Unique?

The defining feature of Chad is its volatility.

Unlike traditional messaging platforms, messages are not permanently saved. The system prioritizes real-time communication over archival storage. Once users disconnect, their messages are cleared from active memory.

Additionally, the system is designed to periodically reset server memory to maintain privacy and reinforce the temporary nature of communication.

---

## Tools and Technologies

Primary technologies include:

* Flask (web framework)
* Flask-SocketIO for real-time communication
* OTP-based authentication system
* HTML, CSS, and JavaScript for frontend interaction
* Email-based OTP delivery through backend API integration
* Deployment to a cloud hosting platform such as Render or similar container-based services

---

## How I Intend to Accomplish This

Development will follow a staged approach:

1. Build foundational Flask project structure
2. Implement basic input and output routing
3. Establish backend authentication logic
4. Implement OTP-based login verification
5. Develop chat room functionality
6. Add real-time messaging using WebSocket communication
7. Track online users within active sessions
8. Implement volatility mechanisms for message clearing
9. Deploy the application to a public domain

This incremental strategy ensures stability before introducing more advanced features.

---

## Techniques for Organization and Task Management

To manage development effectively, I will:

* Divide development into weekly milestones
* Use modular project architecture
* Develop and test features incrementally
* Maintain separation between authentication, messaging, and UI components
* Utilize version control for tracking changes and preventing regression

The primary objective is to complete a functional minimum viable product before adding optional enhancements.

---

## Approach to Troubleshooting and Setbacks

If technical challenges arise, I will:

* Consult official Flask and SocketIO documentation
* Debug components incrementally to isolate errors
* Seek guidance from course materials and instructor feedback
* Use reliable web development resources for clarification
* Test each feature independently before integration

This systematic approach will help ensure steady progress throughout the project.


