# Project Documentation

## Overview
This project is an AI Code Review Assistant that analyzes source code
and provides feedback on errors, improvements, and overall quality.

## Workflow
1. User inputs code (paste, upload, or GitHub URL)
2. Language is auto-detected
3. Code is analyzed for errors and warnings
4. A score is calculated (0–100)
5. Results are displayed with a circular score graph

## Scoring Logic
- Start from 100
- Errors reduce score heavily
- Warnings reduce score slightly
- Clean code gives high score

## UI Features
- Animated typing
- Visual score ring
- Glow effect on high-quality code
