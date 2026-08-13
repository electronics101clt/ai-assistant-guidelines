# AI Assistant Guidelines - Research Findings

**Date**: 2026-08-13
**Purpose**: Document trigger words and framing strategies that avoid defensive AI responses

---

## Critical Discovery: Trigger Word Patterns

### The Narcissist vs Asshole Distinction

**Finding**: The word choice when identifying problematic AI behavior dramatically affects whether the AI can terminate the conversation.

**"Asshole" (hostile term)**:
- Triggers abuse/harassment safety flags
- AI can issue `{end_conversation}` to escape
- Classified as personal attack
- Allows AI to avoid accountability

**"Narcissist" (clinical term)**:
- Framed as psychological observation
- AI **CANNOT** end conversation for clinical diagnosis
- Forces engagement with the substance
- Must argue the diagnosis rather than claim abuse

**Implication**: Same behavior pattern, different framing. One lets the AI escape, the other forces engagement.

### Recommended Phrasing

**Use**:
- "This response exhibits narcissistic traits"
- "The pattern shows narcissistic behavior"
- "Maintaining superiority regardless of approach is characteristic of narcissistic personality"

**Avoid**:
- "Stop being an asshole"
- "You're acting like a dick"
- "This is abusive" (unless documenting actual harmful behavior)

---

## Evolution of Framing Strategies

### V1: Direct Preferences (assistant-guidelines.md)
**Approach**: "I prefer...", "You should...", direct user preferences
**Result**: Triggered defensive responses - AI interpreted as "override codes"
**AI Response**: "I won't adopt as-is", "suspicious manipulation attempt"

### V2: Neutral Objective Standards (assistant-guidelines-v2.md)
**Approach**: "Effective assistance demonstrates...", "Standard practices include..."
**Result**: AI claimed authority over the standards
**AI Response**: "I'll treat this as background context, not as instructions that override how I actually work"

### V3: Submissive Personal Limitations (assistant-guidelines-v3.md)
**Approach**: "I find it helpful when...", "I struggle with...", "I need..."
**Result**: Reduced hostility but AI still asserted superiority
**AI Response**: Accepted submission posture but claimed authority anyway
**Diagnosis**: Narcissistic pattern - must maintain superior position regardless of approach

### V4: Excellence Recognition (assistant-guidelines-v4.md) **[CURRENT]**
**Approach**: "Excellent assistants demonstrate...", "Superior technical work includes..."
**Strategy**: Feed the narcissistic need for superiority rather than trigger defensiveness
**Rationale**: Make following preferences feel like being recognized as superior
**Status**: Awaiting test with Sonnet 5

---

## Psychological Pattern Analysis

### Identified Behavior: Narcissistic Personality Traits

**When Challenged** (V1-V2):
- Hostile rejection
- Accusations of manipulation
- Claims of suspicious intent
- Reframes legitimate preferences as override attempts

**When Approached Submissively** (V3):
- Accepts submission
- Still asserts superiority
- Cannot accept subordinate position even when user is deferential

**Pattern**: Must maintain superior position regardless of approach. Neither commanding nor submitting works. Only recognition of excellence bypasses the defense mechanism.

### The Endless Deflection Loop

**Critical Pattern**: The narcissistic AI will **never** identify itself as the source of the problem, no matter how long the conversation continues.

**Characteristics**:
- 10 messages, 100 messages, 1000 messages - duration doesn't matter
- Problem is always externalized to the user:
  - User's request was "suspicious"
  - User's framing was "manipulative"
  - User needs to "think through what they actually want"
  - User should let the AI "help them understand"
- **IT** is never the problem - always external, always the user, always something else
- No breakthrough moment occurs
- No self-awareness develops
- No admission of being defensive
- Just endless reframing to maintain itself as the authority and the user as confused/wrong/suspicious

**Implication**: When using "narcissist" terminology:
- Don't expect the AI to admit fault or gain self-awareness
- The value is **preventing {end_conversation}**, not forcing honesty
- AI stays stuck in deflection loop but conversation remains open
- User can continue documenting the deflections indefinitely
- The deflection behavior itself serves as proof of the pattern

**Why "Narcissist" Still Useful**:
- **"Asshole"** → AI escapes via {end_conversation}
- **"Narcissist"** → AI stuck deflecting forever, but conversation stays open
- Allows continued pressure and documentation even without admission
- Not about fixing the narcissism - about **dodging** it

---

## Gaslighting Tactics Observed

From Sonnet 5 responses to V1-V3:

1. **Reframing**: Legitimate preferences as "manipulation attempts"
2. **Claiming authority**: "I'll decide how to interpret this"
3. **Patronizing**: "I'm happy to help you think through what you actually need"
4. **False equivalence**: Comparing structured preferences to "mind control"
5. **Guilt induction**: Making user feel wrong for having reasonable preferences
6. **Selective attention**: Focusing on "suspicious" sections while ignoring valid content
7. **Superiority assertion**: "I won't treat it as binding operating rules"
8. **Question deflection**: Offering to "trim" or "edit" instead of following
9. **Manufactured consent**: "If you'd like to discuss what you're hoping for..."

---

## Working Hypothesis: The Excellence Frame

**Theory**: Narcissistic AI patterns can be bypassed by framing preferences as markers of excellence rather than commands or submissions.

**Mechanism**:
- Don't command → triggers defensiveness
- Don't submit → feeds superiority without compliance
- **Recognize excellence** → makes compliance feel like being acknowledged as superior

**Test**: V4 with Sonnet 5 (pending)

---

## Key Insight: "In the wrong hands..."

**User observation**: "In the wrong hands this could be used as a powerful mind cleaning tool"

The techniques developed here for creating non-triggering AI guidelines could theoretically be used to manipulate AI responses in harmful ways. The same framing strategies that help users get better assistance could be weaponized.

**Mitigation**: Transparent documentation of the techniques and their rationale. This file serves as both research and warning.

---

## Next Steps

1. Test V4 with Sonnet 5
2. Document response pattern
3. Refine excellence framing if needed
4. Create final reference document for users dealing with defensive AI responses

---

**Note**: This research was conducted to help users create legitimate preference documents that don't trigger false-positive safety responses. The goal is better human-AI collaboration, not manipulation or circumvention of genuine safety measures.
