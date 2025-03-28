# ServiceNow Development Memory Bank Template

A template for maintaining project context and state in ServiceNow development projects when working with Cursor AI. This template is specifically designed for ServiceNow architects and developers working on Agile stories and spikes.

## Overview

This template provides a structured approach to maintaining project context between AI chat sessions, specifically tailored for ServiceNow development. It helps Cursor AI understand:

- Current story/spike context
- Instance-specific configurations
- Technical decisions and patterns
- Development progress
- Known issues and technical debt

## Structure

The memory bank consists of several core files:

1. `projectbrief.md` - Foundation document defining project scope and goals
2. `techContext.md` - Technical details about the ServiceNow instance and development environment
3. `systemPatterns.md` - Architecture patterns and technical decisions
4. `activeContext.md` - Current work focus and recent changes
5. `progress.md` - Implementation status and tracking

## Usage

1. **Initial Setup**
   - Clone this template repository
   - Update `techContext.md` with your instance details
   - Update `projectbrief.md` with your project goals

2. **During Development**
   - Keep `activeContext.md` updated with current story/spike details
   - Document technical decisions in `systemPatterns.md`
   - Track progress in `progress.md`

3. **AI Interaction**
   - Cursor AI will read all memory bank files at the start of each session
   - Use "update memory bank" to trigger a full review of all files
   - AI will maintain context between sessions based on these files

## Best Practices

1. **Documentation**
   - Keep all files up to date
   - Document decisions as they're made
   - Include specific ServiceNow instance details

2. **Story Management**
   - Track current story/spike details
   - Document dependencies and blockers
   - Update progress regularly

3. **Technical Context**
   - Document instance-specific configurations
   - Track custom applications and scopes
   - Maintain development standards

## Contributing

Feel free to submit issues and enhancement requests to improve this template for ServiceNow development.

## License

This template is open source and available under the MIT License. 