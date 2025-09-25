# Topic Saturation Check

Review your recent content distribution and identify potential audience fatigue or over-saturation.

## Usage
```
/topic-saturation-check [timeframe] [threshold]
```

## What this does
- Analyzes recent newsletter content distribution across your three pillars
- Compares current distribution against target: Workflow Mastery (44%), Tool Mastery (22%), Thinking Mastery (33%)
- Identifies topics or themes appearing too frequently
- Flags potential audience fatigue based on engagement drops
- References your performance data to correlate topic frequency with engagement decline
- Suggests content rebalancing strategies

## Key Checks
- **Pillar Balance**: Are you over-indexing on one learning path?
- **Tool Repetition**: Too many posts about the same AI tools?
- **Framework Fatigue**: Overusing similar methodologies?
- **Engagement Correlation**: Do repeated topics show declining performance?
- **Audience Feedback**: Comments suggesting "more of X, less of Y"

## Parameters
- `timeframe`: "last-month", "last-quarter", or "recent" for last 10 posts (default: recent)
- `threshold`: Saturation threshold percentage for flagging (default: 60%)

## Output includes
- Current vs target distribution across learning pillars
- Specific topics appearing above threshold frequency
- Engagement trends for over-represented topics
- Audience fatigue indicators from comments/performance
- Rebalancing recommendations with specific topic suggestions
- Identification of under-explored high-potential areas

## Example
```
/topic-saturation-check last-quarter 50
```

This command helps maintain content freshness and audience engagement by preventing over-saturation of topics while ensuring balanced coverage of your core themes.