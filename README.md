# Production Rails Patterns

Practical, production-tested patterns for Rails/PostgreSQL systems.

## Overview

This repository documents real-world solutions to common production challenges in Rails applications. Each case study covers the problem, solution approach, implementation details, and lessons learned.

## Case Studies

### 1. Preventing Stale Asynchronous Updates

Using generation counters to prevent race conditions in background job processing.

### 2. Moving Expensive Grouping to PostgreSQL

Replacing expensive Ruby-side grouping with efficient PostgreSQL queries.

### 3. Incremental Modernization with Strangler Fig

Incrementally separating legacy subsystems using Strangler Fig boundaries.

## Getting Started

Each case study includes runnable examples and tests demonstrating the patterns in action.
