# Core Features of the Phoenix LiveView Pattern

| Feature | Description |
|---------|-------------|
| Server-Side Rendering and State Management | The server generates initial HTML and maintains application state, reducing client-side complexity. State is stored in server-side processes or sessions. |
| Real-Time Bidirectional Communication | Uses WebSockets for low-latency, persistent client-server interaction, enabling real-time updates for user events and server-initiated changes. |
| Minimal Client-Side JavaScript | A lightweight JS layer (~20-50 KB) handles event capture, WebSocket communication, and DOM patching, avoiding heavy client-side frameworks. |
| Efficient DOM Updates | The server sends minimal HTML or JSON diffs to the client, which patches the DOM (e.g., using morphdom), optimizing network usage. |
| Event-Driven Lifecycle | Server-side callbacks (e.g., mount, handle_event, handle_info) manage initialization, user interactions, and background updates. |
| Seamless Backend Integration | Tight integration with the framework’s ecosystem (e.g., routing, database, concurrency), allowing unified server-side logic. |
| Fault Tolerance and Recovery | Handles network disruptions with automatic reconnection and state restoration, leveraging the backend’s concurrency model. |
