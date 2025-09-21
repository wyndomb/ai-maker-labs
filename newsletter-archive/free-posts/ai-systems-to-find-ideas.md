# How I Built an AI System That Finds Ideas I Actually Want to Write About

**The four-layer system that transformed my content ideation forever.**

_By Wyndo • July 17, 2025_

I thought I'd cracked the content creation code.

I had my AI prompts dialed in, my research process mapped out, my publishing schedule locked down. But every Monday morning still felt like starting from scratch. That's when I realized: I was struggling to find really good content ideas.

I used to have this painful weekly ritual: ask AI to generate 20 newsletter ideas based on my past posts.

**The results?** Generic suggestions that could have come from any AI newsletter:

- "10 ChatGPT Tips for Busy Professionals"
- "AI Productivity Hacks That Actually Work"
- "The Future of Work in the Age of AI"

**This left me with an impossible choice:** chase trending topics and sound like everyone else, or stick to my authentic voice but risk no one reading it. Meanwhile, I was constantly worrying if I was losing touch with what my audience actually wanted.

But, everything changed a few months ago.

It was Monday morning.

Newsletter due Thursday. I'd been "researching" for three hours straight: thirty-seven browser tabs sprawled across Reddit and Twitter threads. My Notion had a pathetic list of half-formed ideas that felt stale before I even wrote them down.

There had to be a better way.

## The light bulb moment

That's when I realized I was thinking about finding content ideas all wrong.

Instead of asking AI to generate ideas from scratch, I needed to teach it to become my research assistant: one that could surface opportunities worth my attention, while I maintained complete control over what actually deserved my time.

Think of it like having a research assistant who knows your interests deeply enough to bring you only the opportunities worth considering. They can tell you what conversations are happening and what questions people are asking, but you still decide which conversations you're qualified to join.

I spent the next two weeks building what I now call my "Content Intelligence System." Four interconnected layers that work together to surface ideas that are both trending AND authentically mine.

Each layer operates on the same principle: surface what's relevant, but never override what feels right. The system might tell me that productivity content performs well, but if I don't have fresh insights this week, I won't force it.

Every idea still has to pass the same test: Do I have something unique to say about this? Does writing about this feel authentic? Can I bring real experience to this topic? If the answer is no, the data doesn't matter.

Here's how it works...

## 1. Newsletter Intelligence

I connected my Gmail to Claude and taught it to scan AI newsletters I subscribe to—not to copy their ideas, but to spot emerging themes and conversations I should be aware of. Since Claude already knows my voice and expertise through my project knowledge (where I've uploaded all my past posts and social notes), it can identify which trending topics align with my perspective.

## 2. Reader Intelligence

Claude analyzes comments across my newsletters and social posts to identify what my audience actually cares about. Instead of guessing what readers want, I let their actual words guide my content direction.

Claude then provides me with 8 content ideas with real citations from readers and content angle to push. With these information, I can judge it clearly if the idea is worth pursuing for.

## 3. Performance Intelligence

Every week, I uploaded my newsletter performance data to my project knowledge so Claude knows which posts got the most views, likes, and comments. Now Claude can reverse-engineer what works and suggest similar approaches for new topics.

For a data nerd like me, this is my heaven. It's like having a data analyst who says:

> "Your 'personal experiment' posts always perform well. Here's how you could apply that format to this trending AI development."

But I didn't stop there. I had Claude build me a data dashboard using the artifact feature—complete with viral pattern identification and next-level content ideas for my newsletter.

## 4. Community Intelligence

I deployed an AI agent using Gumloop to monitor AI subreddits and extract the top rising posts each week and send it to my email. But instead of just giving me a list of trending topics, the agent filters everything through my established expertise and writing style.

**The result:** I get a weekly digest of "here's what the AI community is buzzing about, and here's how you could uniquely contribute to these conversations."

## The transformation

After months doing this, my automation system wasn't just about finding ideas faster or saving time, but it was about finding better ideas. I became more effective at it.

Now, I know some of you swear by the blank page approach. There's real wisdom in wrestling with ideas from scratch—that struggle often produces the most original insights. I respect that process completely.

But what I learned there's a difference between **productive creative struggle** and **inefficient research**. The creative wrestling should happen with ideas worth wrestling with.

This system doesn't eliminate that creative tension. It redirects it toward better problems. Instead of spending mental energy on 'What should I write about?' I now focus that same creative intensity on 'How can I bring my unique perspective to this conversation that's already happening?'

The blank page still exists—it's just informed by better context.

Posts developed through this system feels more authentic.

The system was surfacing ideas that resonated more deeply because they emerged from the intersection of what was trending AND what my audience actually needed.

When you're regularly exposed to the patterns of what works—which topics resonate, how successful posts are structured, what questions readers ask most—you internalize those patterns.

I started recognizing good ideas faster in regular conversations. I began spotting content angles in everyday situations. The automation was training my natural ideation instincts.

The biggest surprise was how this changed my relationship with my own expertise.

Before, I was constantly second-guessing myself: "Is this topic too niche?" "Am I missing something important?" "Will people care about this?"

Now, when Claude suggests an idea, it comes with context: "This connects to your expertise in practical AI implementation" or "Three readers mentioned this exact problem in recent comments."

That external validation gave me confidence to go deeper into topics I might have previously avoided as "too niche."

## What still requires human judgment

This system gives me better raw material, but it doesn't make editorial decisions.

Claude might surface five trending topics, but I still choose which one aligns with my publishing calendar. It might suggest three angles on a topic, but I decide which feels most authentic to explore.

**Here's how this plays out in practice:** AI regularly suggests ideas that look good on paper but feel wrong for me. Sometimes they're too generic or vague. Other times they're over-the-top concepts that sound impressive but aren't in my wheelhouse yet. Occasionally, they're topics that would probably perform well but don't excite me.

**But, my filter remains simple:** Do I enjoy writing this? If the answer feels forced, I don't pursue it, regardless of what the data suggests. I'd rather write something I'm genuinely curious about than chase viral potential with content that feels hollow.

The AI surfaces conversations worth exploring. The ideas come from real trends and real reader needs, filtered through my established perspective.

Instead of choosing between authenticity and relevance, I get both. Instead of hoping I'm in touch with my audience, I have data. Instead of starting each week with anxiety about what to write, I start with confidence about what's worth exploring.

## Implementation plan

If you think the content intelligence system is interesting, here are some ways you can start it:

### Step 1: Set up your AI knowledge base

Before Claude can understand your voice, it needs to know who you are. Create a new Claude project and upload:

- Your last 10 best-performing pieces of content
- A document describing your expertise and perspective
- Examples of content you love (and hate) from others

This becomes Claude's reference for "sounds like you" vs "sounds generic."

### Step 2: Connect your information diet

**The easiest automation to implement:** let Claude monitor what you're already reading.

If you use Gmail, connect it to Claude using MCP.

The prompt that works for me:

> "Scan my AI newsletter subscriptions from this week. Based on my writing style and expertise in [your focus area], what emerging themes should I be paying attention to? What questions are being raised that I could answer from my unique perspective? Format as: Theme → Why it matters → Your unique angle."

### Step 3: Add reader intelligence

Once newsletter intelligence is working, add reader feedback analysis. Copy comments from your last 5 posts into a document and ask Claude:

> "What questions and pain points do you see in these reader comments? What topics are they asking about that I haven't covered yet? What frustrations could I address?"

This layer often surfaces your best content ideas because it's based on actual audience need, not just industry trends.

### Step 4: Use Gumloop to scrape Subreddits

This is the hardest part because you'll no longer be in Claude's ecosystem. You need to go out and use Gumloop to scrape the subreddits you want. But due to its intuitive user interface, it's actually easier to set up.

To find which subreddits are relevant to you, I use GummySearch. You can just tell it your interests and it will provide you with relevant subreddits.

Additionally, Gumloop offers 1,000 free credits per month for free users, so you don't have to pay anything to test it out.

---

What's hard about this whole system is not about setting it up, but maintaining it sustainably. You need to spend time 15-20 minutes each week to upload everything to your knowledge base so it grows with you as you have more contents.

Most importantly: this will help you with better raw material to work with. You're still choosing which ideas to pursue, how to angle them, and how to execute them. You're just not starting from zero every single week.

## Your next step

Here's what I wish someone had told me a few months ago: the choice between authenticity and relevance is a false dilemma.

You don't have to sacrifice your unique voice to stay connected to what's happening in your field. You don't have to choose between chasing trends and staying true to your expertise.

The key is remembering that data shows you what conversations are happening, but your experience determines which ones you can meaningfully contribute to. No amount of optimization matters if you don't have something genuine to say.

This works because the content still comes from what you actually know and care about. The system just helps you find the right moments to share it.

Now, stop reading about automation and start building it.

Open Claude. Upload five piece of content you're genuinely proud of, something that represents your voice at its best. Then ask: "Based on this writing style and perspective, what content ideas should I be considering this week?"

Pay attention to which suggestions make you think "that's interesting" versus "that's generic." That gap is your system telling you what it needs to learn about your voice.

## The real test for you

If you're still manually hunting for ideas next Monday morning, you haven't solved the problem—you've just read about solving it.

Your audience deserves content that's both timely and authentically yours. You deserve a creative process that energizes rather than exhausts you.

The system exists.

The tools are ready.

The only question is whether you'll build it or keep struggling with the old way.

What will you automate first?
