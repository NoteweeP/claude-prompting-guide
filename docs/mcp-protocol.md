# Using MCP Protocol with Claude.ai

## What is MCP?
The Message Control Protocol (MCP) allows Claude.ai to interact with external systems and perform actions like:
- Managing GitHub repositories
- Reading/writing files
- Browser automation
- Creating artifacts

## Basic Structure

MCP commands follow this structure:

```xml
<function_calls>
<invoke name="function_name">
<parameter name="param1">value1