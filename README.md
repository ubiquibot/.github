
## Repositories: 
- Service
- Purpose
- Language
- External Integration
- Database
- Infrastructure
- Main contributor

### 1. ubiquibot/conversation-rewards
- Service: Conversation Reward Module
- Purpuse: This is intended to be the proper implementation of comment incentives, based on our learnings from the first go-around.
- Language: TypeScript
- External Integration: Github Action, Github API
- Database: None


### 2. ubiquibot/permit-generation
- Service: Permit Generation module
- Purpuse: The purpose of this module is to isolate the bot's payment capabilities. This can be directly invoked from other plugins
- Language: TypeScript
- External Integration: ENS, ethers
- Database: Supabase
- Main contributor: @Keyrxng, @pavlovcik

### 3. ubiquibot/assistive-pricing
- Service: Assistive Pricing module
- Purpose: **Don't know**
- Language: Typescript
- External Integration: 
- Database: Supabase

### 4. ubiquibot/comment-incentives
- Service: Comment Incentives module
- Purpose: Split reward to the collaborators who wrote some comments
- Language: Typescript
- External Integration: 
- Database: None (Supabase, TODO: get the assignee multiplier from the database)

### 5. ubiquibot/plugins-wishlist
- Serivce: not a service
- Purpose: Wishlist of the future plugins

### 6. ubiquibot/configuration
- Service: not a service
- Purpose: Helpers to parse and merge configuration files for Ubiquibot.

### 5. ubiquibot/e2e-tests
- Service: not a service
- Purpose: Use this for end-to-end tests.
@pavlovcik How does it work?

### 6. WIP

```
## Services: 
- Any internal or external services your system interacts with.


## Databases: 
- The types of databases used and their relationships to other components.


## External Integrations: 
- Third-party services or APIs your system relies on.


## Infrastructure: 
- The underlying infrastructure, such as cloud services, container orchestration (e.g., Kubernetes), and network architecture.
```