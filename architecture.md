# SignalMind – Architecture Overview

## 1. Purpose
SignalMind is not a traditional app. It is a minimal cognitive interface, designed to restore sovereignty of thought through decentralized interaction with AI.

## 2. Components

### Frontend
- HTML + JS static site (`index.html`)
- Hosted via ENS (`signalmind.eth.limo`)
- UI: minimal prompt > response loop

### Logic Layer
- Input field forwards prompt to configured AI endpoint
- Current prototype uses OpenAI-style API
- Prompt can be adapted based on context (via future `flow-config.js`)

### Intelligence Layer
- Currently cloud-based AI (can be decentralized in Phase 3)
- GPT-style transformer models
- Future version: local inference via open-source LLMs

## 3. Expansion Plan

- Add session memory
- Add Flow-based prompt modulation
- Wallet-gated features (without auth) for collective prompts
- Integrate Flow Code decision logic

## 4. Governance

- All code is open source (MIT)
- Decisions made transparently in public
- Project is coordinated by FluidThinkers
- Long-term: DAO-based maintenance + curation of training data

## 5. Philosophy
SignalMind doesn’t replace human cognition. It reflects it.  
Architecture is simple by design — because attention is the real interface.

