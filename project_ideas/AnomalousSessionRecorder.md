# Anomalous Session Recorder

This library aims to record and analyze user sessions on a web application to detect and flag any anomalies. Anomalies can be defined as deviant or unusual behavior, such as sudden spikes in activity, accessibility issues, page not working or access to restricted resources.

Key features:

- Ability to flag and store anomalous sessions for further analysis.
- Record and store videos of such sessions.
- A web dashboard to access the recorded sessions.
- Take feedback on false positive detections and improve accuracy.

Key Components:

- Core: The main engine that will classify the session as anomalous or normal.
- JS Library: This will stay on the Frontend to connect, record & send sessions to the core.

The library will be implemented in Python and will use machine learning algorithms to detect anomalies in user sessions. It will store the data in a NoSQL database for scalability and quick retrieval. The video recording of anomalous sessions will also be stored on the server.

This will help better understand user behavior and improve the application accordingly.

## Technologies
`
Technologies: Python, AI/ML, NoSQL, Data Visualization
`

Repos:
- https://github.com/TheAlgorithms/SessionGuard-Core
- https://github.com/TheAlgorithms/SessionGuard.js
