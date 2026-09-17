---
name: pram
description: Open a PR with auto-merge
disable-model-invocation: true
---

# Requirements
- Check that I'm in a branch other than `main`, `master` or `prod`. If not, make a new branch for the feature
- Check the diff between my branch and the main branch of the repo
- Create a DRAFT PR
- Tag the PR with the proper team (see tags list below)
- Update the PR to be ready for review and auto-merge enabled

# Guardrails
- Use `gh` if it's installed
- Prepend GIT_EDITOR=true to all git commands you run, so you can avoid getting blocked as you execute commands
- Do NOT run tests or checks
- Do NOT git push or commit anything automatically

# PR Template
- Make sure you follow the repo's PR template and naming conventions as seen in docs or in .github workflows, as well as any PR requirements in the repo's AGENTS.md file
- Describe all the changes in the PR by analysing the code changes and summarizing
- Do not include sections of the PR template that were just there as reminders or instructions

# Response
- Always paste the link to the PR in your response, hyperlinked using MD, so I can click it easily

# Tags list
- Accommodation
- Agent Hub
- Business Traveller
- Car Hire
- Connections
- CRO
- Cruises
- customer-communications
- CX
- EngX
- Experiences
- Flights
- hotels
- LERE
- Loyalty
- LuxPlus
- Marketing Platform
- Mobile
- OPEX
- OSS
- Payments
- preference-centre
- Shop
- Tours
- Trip
- VoiceAI
- WhiteLabel
