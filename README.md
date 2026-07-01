# Prism: AI-Powered Behavioral Analysis Tool

Prism is a public-facing tool that analyzes the empathic, cooperative, and cognitive dynamics behind real-world social and policy problems. Users submit a policy, program, or social issue, and Prism draws on behavioral science, cognitive science, and social psychology to break down what's happening, why it persists, and what evidence-based levers could shift the outcome.

## What it does

A user describes a social scenario, policy, or program in plain language. Prism analyzes the underlying behavioral and social dynamics at play and returns a structured breakdown of the mechanisms driving the behavior, along with evidence-informed suggestions for intervention.

## How it works

- **Frontend:** HTML, CSS, JavaScript
- **Analysis engine:** Anthropic's Claude API, prompted to reason through the scenario using behavioral science, cognitive science, and social psychology frameworks
- **Deployment:** Hosted on GitHub Pages, with a Vercel serverless function acting as a secure proxy — this keeps the API key off the client side rather than exposing it in the frontend code

## Live demo

https://rachelyhkim-cog.github.io/prism.html/

## Why I built it

I wanted a way to translate behavioral science research into something usable in real time — a tool that could take a messy, real-world social problem and connect it back to the cognitive and social mechanisms research has already identified, rather than starting from scratch every time.

## Notes on development

Built through an iterative, AI-assisted development process: I directed the tool's design, scope, and behavioral science framing, and worked through real implementation issues along the way — including CORS errors, API key configuration, and JSON response truncation — while Claude handled the bulk of the code implementation itself.
