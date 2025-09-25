# Quick Note to Post

Transform rough ideas, research notes, or observations into structured newsletter post concepts.

## Usage

```
/quick-note-to-post [note-content] [tier-preference]
```

## What this does

- Takes unstructured ideas, research, or observations as input
- Applies The AI Maker content framework: Hook → Failure Pattern → Framework → Implementation → Next Steps
- Determines which learning pillar the content fits (Workflow/Tool/Thinking Mastery)
- Structures content using your proven voice patterns and tone markers
- Suggests whether it's better suited for free tier (inspiration) or paid tier (implementation)
- Provides preliminary outline with key talking points

## Content Framework Applied

1. **Hook with Personal Story**: Creates engaging opening with your voice markers
2. **Identify Common Failure Pattern**: Finds the problem most readers face
3. **Present Systematic Framework**: Develops actionable methodology
4. **Include Implementation Steps**: Outlines practical how-to guidance
5. **End with Next Steps**: Provides immediate actionable takeaway

## Parameters

- `note-content`: Your raw ideas, research, or observations inside /brain-dump folder
- `tier-preference`: "free", "paid", or "auto" to determine content tier (default: auto)

## Output includes

- Structured post outline following your content framework
- Learning pillar classification (Workflow/Tool/Thinking Mastery)
- Tier recommendation (free vs paid) with rationale
- Key voice markers and personal story angles to develop
- Potential premium tier follow-up opportunities
- Estimated engagement potential based on similar content performance

## Example

```
/quick-note-to-post "Been experimenting with Claude MCP for automated research workflows. Amazing results but setup was painful. Most people probably giving up too early." auto
```

This command accelerates your ideation-to-outline process while ensuring content maintains your strategic approach and authentic voice.
