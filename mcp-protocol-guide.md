# Using MCP Protocol with Claude.ai

## Overview
The Message Control Protocol (MCP) is a way to interact with external services and functions through Claude.ai. This guide explains how to effectively use MCP function calls in your conversations with Claude.

## Basic Structure

MCP function calls use this XML-like syntax:

```xml
<function_calls>
<invoke name="function_name">
<parameter name="parameter_name">parameter_value