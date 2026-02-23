# Chad - A Volatile Web-Based Messaging Application

## Overview

Chad is a web-based volatile messaging application built using Flask and real-time communication technologies. The primary purpose of the application is to provide temporary, session-based communication where messages are not permanently stored. Users log in using a one-time password (OTP) system and can join chat rooms to send and receive messages in real time.

Unlike traditional messaging platforms, Chad is designed around volatility and privacy. Once a user disconnects or logs out, their local message data is cleared. The application is intended to simulate lightweight, walkie-talkie-style communication that prioritizes immediacy over permanence.

---

## What Does the Application Do?

Chad allows users to:

* Log in using OTP-based authentication
* Join public or private chat rooms
* Send and receive real-time messages
* View currently online users
* Experience temporary communication where messages are not persistently stored

Real-time functionality will be implemented using Flask-SocketIO to allow instant message broadcasting between connected users.

The system is intentionally designed to avoid long-term message storage. Messages will only exist during active sessions, making the application fundamentally volatile.

---

## Why Is It Worth Doing?

This project is worth doing because it integrates multiple foundational web development concepts into one cohesive application. It requires:

* Authentication systems (OTP-based login)
* Database design and management
* Real-time communication
* Routing and templating
* Session management
* Deployment to a live domain

By building Chad, I will gain practical experience designing and implementing systems similar to modern messaging platforms. However, unlike traditional chat applications, this project explores privacy-focused communication and ephemeral data handling.

The volatility constraint introduces an additional design challenge, requiring careful consideration of how sessions, sockets, and temporary storage are handled. This makes the project both technically engaging and conceptually meaningful.

---

## Target Audience

The target audience includes users who prefer privacy-focused, temporary communication. This could include:

* Individuals who do not want message history stored
* Users looking for lightweight, fast chat rooms
* People who prefer walkie-talkie-style interaction
* Privacy-conscious users who want minimal data retention

While the application is primarily academic, it demonstrates how ephemeral communication systems can be implemented in practice.

---

## What Makes It Unique?

The defining feature of Chad is its volatility.

Unlike most messaging platforms, messages are not permanently saved. The system prioritizes real-time interaction over archival storage. Once users disconnect, their messages are cleared from their session.

This design decision shifts the application away from being a social archive and toward being a live communication tool. The focus is on presence, immediacy, and privacy.

---

## Tools and Technologies

Primary technologies include:

* Flask (web framework)
* Flask-SocketIO (real-time communication)
* MongoDB (database management)
* OTP authentication system
* HTML, CSS, and JavaScript for front-end interaction
* Deployment to a custom domain (e.g., chad.sayhan.app)

If required, an email server or third-party email API may be used to deliver OTP codes securely.

---

## How I Intend to Accomplish This

Development will follow a staged approach:

1. Build foundational Flask project structure
2. Implement basic input/output routes
3. Establish database connectivity
4. Add OTP-based authentication
5. Create chat room functionality
6. Implement real-time messaging
7. Add online user tracking
8. Refine volatility logic (session-based message clearing)
9. Deploy to live domain

This incremental approach ensures stability at each step before adding complexity.

---

## Techniques for Organization and Task Management

To manage development effectively, I will:

* Break features into weekly milestones
* Use modular file organization within Flask
* Develop and test components incrementally
* Separate concerns (authentication, messaging, UI, database)
* Use version control to track changes and prevent regression

I will prioritize building a functional minimum viable product before adding advanced features.

---

## Approach to Troubleshooting and Setbacks

If technical challenges arise, I will:

* Review official documentation for Flask and related tools
* Debug incrementally to isolate issues
* Consult class materials and instructor guidance
* Use reliable web development resources for clarification
* Test features individually before integration

By approaching troubleshooting systematically and seeking guidance when necessary, I will maintain steady progress throughout the semester.


