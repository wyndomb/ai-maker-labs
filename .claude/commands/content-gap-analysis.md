# Content Gap Analysis

Analyze your newsletter archive to identify content gaps and opportunities across the three learning paths.

## Usage
```
/content-gap-analysis [pillar] [depth]
```

## What this does
- Scans newsletter-archive/ for published content distribution
- Maps content against your three pillars: Workflow Mastery (44%), Tool Mastery (22%), Thinking Mastery (33%)
- Identifies under-covered topics within each learning path
- Cross-references with performance data to prioritize high-potential gaps
- Suggests specific content opportunities based on successful patterns
- Flags topics that align with your premium tier conversion strategy

## Parameters
- `pillar`: Focus analysis on specific pillar - "workflow", "tool", or "thinking" (optional)
- `depth`: "surface" for quick overview or "deep" for detailed analysis (default: surface)

## Output includes
- Current content distribution vs target percentages
- Specific topic gaps within each pillar
- Underutilized high-performing content themes
- Premium tier blueprint opportunities
- Recommended next 3-5 post topics with rationale

## Example
```
/content-gap-analysis workflow deep
```

This command helps maintain strategic balance while identifying content opportunities that align with your audience's demonstrated interests.