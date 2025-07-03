# Next-Gen Languages Implementing the LiveView Pattern (Restricted to Haskell and Rust)

| Language | Framework | Implements LiveView Pattern | Notes |
|----------|-----------|-----------------------------|-------|
| Haskell | IHP | Yes | IHP is explicitly inspired by Phoenix LiveView, offering WebSocket-driven real-time updates, server-side state, minimal JS (~20 KB), and a polished lifecycle. It integrates with Haskell’s ecosystem (e.g., for database access) and supports fault tolerance via Haskell’s concurrency. Ideal for Haskell developers seeking a batteries-included LiveView experience. |
| Rust | Dioxus LiveView | Yes | Dioxus LiveView is a dedicated mode for server-driven UIs, using WebSockets, SSR, and minimal JS for real-time updates. It integrates with Rust’s ecosystem (e.g., Axum, Tokio) and supports fault tolerance. Well-documented and type-safe, it’s suited for Rust developers wanting a LiveView-like workflow. |
