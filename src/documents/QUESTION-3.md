## Describe how your approach would differ (if at all) between building this from scratch to integrating it within an existing system (e.g Drupal/Symfony)

Let me explain the differences between building the product search from scratch versus integrating it into an existing system, and my reason for the chosen approach:

While I understand the company primarily uses PHP/Drupal, I consciously chose to build this test with Vite + React + TypeScript to demonstrate both my frontend capabilities and understanding of modern web architectures.

Here's how the approaches differ:

If I was building from `scratch (Current Implementation)` and had the freedom to choose the technology used, I would prefer, like I did for this exercise. I could build a self-contained component with its own state management, direct API integration through JavaScript fetch.

If I was `integrating with the existing system for Drupal`, I would need to consider Drupal's existing frontend architecture, but I could integrate the React component in two ways:

- As a custom Drupal block with proper library declarations or
- Through Drupal's JavaScript behaviors system.

The core search functionality would remain the same, but the implementation details would adapt to fit the host system's architecture and best practices. My current React implementation is actually advantageous for integration as it's built as a self-contained component that could be embedded into either system with minimal modifications.

The key is that both approaches are valid, and being comfortable with both technologies allows me to make informed decisions based on specific project needs rather than defaulting to what's already in use. This flexibility is valuable when working on different features within the same system.
