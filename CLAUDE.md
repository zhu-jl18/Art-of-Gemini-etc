# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Environment Configuration

This is a test repository configured for Claude Code development with custom API settings:
- Uses local Anthropic API endpoint at `http://localhost:4141`
- Configured with Claude Sonnet 4 as the primary model
- Has non-essential model calls disabled for testing

## Repository Structure

This directory serves as a minimal test environment for Claude Code functionality. The main configuration is located in:
- `.claude/settings.json` - Base environment configuration
- `.claude/settings.local.json` - Permission configurations and allowed operations

## Permitted Operations

The repository is configured to allow specific operations including:
- Git operations (commit, push, branch, remote management)
- Hexo blog operations (clean, generate, new posts)
- File reading from specific blog directories
- Docker version checking
- Web fetching from GitHub domain
- MCP server operations for deep analysis

This setup appears to be primarily for testing Claude Code's integration with blog management workflows and MCP server capabilities.