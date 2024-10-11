# Shopify app testing

Created this rails app via `rails new` in Oct 2024. 

This repo is one of multiple test apps using Shopify's official scaffolded templates. The goal is to explore the best practices and tools Shopify provides for building apps that integrate with the Shopify Admin UI.

## Context
I initially generated several test apps using Shopify's recommended Shopify CLI and official templates. These apps helped me:

- Understand the structure of Shopify apps created using the latest scaffolded templates.
- Test how managed OAuth flow and session handling work within a Shopify app context.
- Evaluate different ways to integrate Shopify's tools with Rails while building both public-facing web apps and Shopify admin interfaces.
Next:
- Experiment with Shopify’s App Bridge, Polaris, and Shopify API.

## Official Shopify Templates Used

These test apps served as a foundation for learning how to manage routing, sessions, and UI integration, and they helped me create a more robust production Shopify app.

1. APP: shoptempl-remix
Repo: https://github.com/LucidIndian/shoptempl-remix
CLI scaffold
The only official CLI scaffold without linking to a remote repo, I recall I used to be abel to choose “Ruby” which was Rails+react, but appears it’s since been removed from the CLI as an option. 

2. APP: shoptempl-rails-react
    - Rails Template: A Ruby on Rails app with React
    - Repo: https://github.com/LucidIndian/shoptempl-rails-react
    - CLI scaffold + remote GH repo (Official Shopify Ruby template: Rails 7.2 + React)

3. APP: rails8new_shopappgem
- Repo: https://github.com/LucidIndian/rails8new_shopappgem

4. APP: shoptempl-rails-stimulus
- Repo: https://github.com/LucidIndian/shoptempl-rails-stimulus

5. Node.js / Express Template
- A Node.js app using Express for handling backend operations and React for the front end with Polaris components.

## Lessons trying to learn
- Best practices for setting up the package.json file and dependency management.
- Managing multiple view folders for the normal web app and Shopify's admin UI views.
- Effective use of Shopify's App Bridge for cross-app navigation and session management.
- Integration of Shopify’s Polaris components for a native-like admin experience.

This README entry explains my experience and the context behind building Shopify apps from their official templates. Let me know if you'd like to expand or adjust it!


Everything below this is from the original README: 