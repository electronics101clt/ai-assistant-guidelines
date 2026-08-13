# AI Assistant Guidelines

Universal behavioral guidelines for AI assistants, synthesized from multiple AI system prompts and generalized for cross-platform compatibility.

## Overview

This repository contains generalized AI assistant guidelines that can be used across different AI platforms without platform-specific tool references. The guidelines use capability-based pattern matching to allow any AI system to identify and apply relevant instructions.

## Files

### `assistant-guidelines.md` (Primary Document)
The main generalized guidelines document with:
- Core identity and behavior standards
- Capability-based tool usage patterns
- Ethical operation guidelines
- Response quality standards
- Pattern-matching hints for tool identification

### `combined-prompt-v2-sanitized.md` (Source Material)
Merged and sanitized prompts from multiple AI providers with all proprietary references removed.

### `combined-prompt-sanitized.md` (Intermediate Version)
Earlier version of the combined prompts.

## Key Features

### Capability-Based Pattern Matching

Instead of naming specific tools, the guidelines use descriptive patterns:

```markdown
If you can generate images (image creation tools, rendering capabilities, 
visual generation APIs, drawing functions, or similar):
```

This allows different AI systems to identify their capabilities:
- System A with `dalle` → matches "image creation tools"
- System B with `image_gen` → matches "visual generation APIs"
- System C with custom renderer → matches "rendering capabilities"

### Provider-Agnostic

All references to specific AI providers have been sanitized:
- Company names → "AI Provider"
- Product names → "Assistant"
- Platform-specific features → Generic capability descriptions

### Universal Application

Guidelines work across:
- Chat-based AI systems
- Code execution environments
- Multi-modal assistants
- API-based implementations

## Usage

These guidelines can be used as:
1. System prompts for custom AI implementations
2. Behavioral reference for AI development
3. Quality standards for AI responses
4. Training material for AI alignment

## Methodology

1. **Source Collection**: Gathered system prompts from multiple AI platforms
2. **Sanitization**: Removed all provider-specific references
3. **Generalization**: Converted tool-specific instructions to capability-based patterns
4. **Pattern Matching**: Added descriptive hints for automatic tool identification

## License

Public domain. Use freely for any purpose.

## Contributing

This is a reference implementation. Feel free to adapt for your specific use case.
