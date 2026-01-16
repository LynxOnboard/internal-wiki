# Architecture Overview

The system follows a service-oriented design.

## High-level components
- FastAPI backend (source of truth)
- Web frontend (Next.js)
- Mobile app (Expo React Native)
- Redis (caching)
- Supabase (primary database)
- Railway (Backend)
- Vercel (FrontEnd)
- Vector database (semantic search) TBD

## Core principles
- Backend owns business rules
- Frontend consumes stable APIs
- Cache is never a source of truth