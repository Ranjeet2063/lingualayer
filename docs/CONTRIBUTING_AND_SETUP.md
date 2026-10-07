# Contributing & Environment Setup Guide

## Overview
This document specifies developer contribution guidelines, environment setup, and verification routines for **lingualayer**.

Related Issue: #177 (cargo test --workspace / cargo build --workspace fails on a clean checkout (license-router contractimport! ordering))

## Prerequisites & Standards
- Ensure local toolchain and runtime requirements match repository specifications.
- Verify environment variables prior to local runtime initialization.
- All code contributions must pass automated linting and formatting validation before pull request dispatch.

## Verification Checklist
1. `git status` clean working tree
2. Run standard local lint and unit test suites
3. Verify deterministic state handling
