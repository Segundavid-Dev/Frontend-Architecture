_This is my attempt at understanding a topic i seem to enjoy as i delve deeper and deeper into it "Architecture of Software Systems". I do Frontend for now so i decided to understand it that point of view.
I hope to implement all i learnt during this phase of curiosity in my future projects😄!_

## What really is Frontend Architecture ?

Frontend Architecture is the architecture of software systems(Frontend)...yes you read that right! haha😅. But for real, what is Frontend Architecture all about.

```
Frontend Architecture are all the decisions we should take during the planning, design and implementation phase of building a system
```

What then are these decisions ?

- Reusability of UI elements into components
- Seperations of Concerns like UI, state management, Logic
- Domain Modelling (Entity or Modules)
- Seperations of Global State and Component level state
- Accessibilty considerations
- Mobile First Consideration dependeping on Use Case

### Layers in Frontend

- PRESENTATION LAYERS
- APPLICATION / BUSINESS LAYERS
- ENTITIES LAYERS
- INFRASTRUCTURE

The primary purpose of these design patterns and architectural concepts is to ensure that as the project scales or new business features are added, the codebase remains manageable and does not grow in complexity.

## Key specifications in Frontend Architecture

- Functional Requirements - Functional requirements define **what the software should do**. They specify the core features and capabilities that the system must support to fulfill user needs and business objectives.
  Examples include: Authentication and Authorization, Product Search Functionality, user profile management, Order payment, e.t.c

- Non-Functional Requirements

  - Scalability
  - Performance
  - Reliabilty
  - Security
  - SEO considerations
  - Browsers support

- Technology Decisons

  - Frameworks/Library Choice (React, Angular, Vue, Svelte e.t.c)
  - Routing Tools
  - State Managements

- Build and Tooling
  - Bundler and dev server (e.g., Vite, Webpack)
  - Linting and formatting (e.g., ESLint, Prettier)
  - Type checking (e.g., TypeScript)
  - Testing framework (e.g., Vitest, Jest, Playwright)
  - CI/CD pipeline setup
  - Environment management (.env strategy)

and many more....

> This is still a work in progress, i would update this docs as i learn more and dive even deeper
