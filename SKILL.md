---
name: social-media-analyzer
description: "Analyze YouTube Shorts, X/Twitter, Facebook, and other social platforms for view drops, follower origins, algorithm signals, and growth patterns. Use when diagnosing low views, engaged views, Shorts distribution, follower sources, or multi-platform performance."
type: workflow
lifecycle: active
---

# Social Media Analyzer — Multi-Platform Growth Diagnostics

Diagnose why content performs unevenly across YouTube Shorts, X/Twitter, Facebook, and related platforms. Focus on algorithm signals, retention metrics, content originality, and acquisition sources.

## When to Use

Trigger on requests involving:
- YouTube Shorts with low/zero views or uneven performance
- "1 engaged view at 100%", "Shown in feed near zero", or similar Studio metrics
- X/Twitter follower origins or audience location
- Facebook/Instagram growth vs. other platforms
- CapCut uploads, meme/clip channels, or re-upload style content
- Algorithm changes (especially Oct 2026 Shorts originality update)

## Core Workflow

### 1. Identify Platform and Gather Public Data
- For YouTube: browse `@handle/shorts` or specific video URLs. Extract view counts, titles, subscriber count, and content style.
- For X/Twitter: use user search and recent posts. Note follower count, bio, and public activity. Private follower lists and exact acquisition sources are not accessible.
- For Facebook/others: note cross-posting patterns and relative growth signals.

### 2. YouTube Shorts Diagnosis (Primary Use Case)

**Key metrics (YouTube Studio):**
| Metric | Meaning | What low numbers indicate |
|--------|---------|---------------------------|
| Shown in feed | Times the Short appeared in the Shorts feed | Near zero = distribution never started |
| Viewed vs. swiped away | % who stayed past first seconds | Low = hook failed in the test batch |
| Engaged views | Viewers who stayed past initial seconds (excludes loops) | The stricter, more meaningful count |
| Average % viewed | Watch completion among engaged viewers | Low = mid-video drop-off |

**Typical failure modes:**
1. **Shown in feed ≈ 0** — Algorithm did not distribute. Common on small channels, mixed niches, or content flagged as light re-uploads.
2. **1 engaged view at 100%** — One solid viewer finished it, but almost no seed audience was shown the video. Not a full test.
3. **High views, low engaged views** — People start watching then swipe. Hook or first 1–2 seconds problem.
4. **Some Shorts hit thousands, others die at 1–25** — Normal variance. Seed audience reaction decides expansion.

**October 2026 Shorts originality update:**
- YouTube reduced reach for channels primarily re-uploading or lightly editing other creators' clips.
- Minor CapCut captions, sound, or template edits often do not count as "significant additions."
- Channels that openly clip and re-edit (common meme pages) see more uneven or reduced distribution.
- Original commentary, unique storytelling, or substantial transformation performs better.

### 3. X/Twitter Follower Analysis
- Cannot access private follower lists or exact "where they came from" data.
- Direct user to: Profile → Followers → sort by Latest for newest accounts.
- For aggregate location: X Premium Analytics (audience country) or third-party tools (Circleboom, Fedica).
- Review public bios, recent posts, and mutual connections on the newest followers for likely source signals.

### 4. Cross-Platform Pattern Recognition
- Compare relative growth: strong on one platform (e.g., Facebook) + weak on another (YouTube Shorts) often signals content-format or algorithm mismatch.
- CapCut workflow is neutral — upload source does not cause selective suppression.
- Consistent niche + strong first-frame hooks outperform volume of lightly edited clips.

## Diagnostic Checklist

For a low-view Short:
1. Confirm "Shown in feed" number.
2. Compare engaged views vs. public views.
3. Check first 1–2 seconds for visual hook strength.
4. Note if content is a light re-edit of existing clips (originality risk).
5. Compare against the channel's own higher-performing Shorts for pattern differences.

## Output Style

Lead with the clearest diagnosis (distribution never started vs. hook failed vs. originality penalty).  
Provide the specific Studio metric to check next.  
Give 2–3 concrete, platform-specific next actions.  
Avoid claiming shadowbans or permanent blocks without metric evidence.

## References
- See conversation history for real examples of @jasejoker YouTube Shorts performance patterns and X follower analysis.
- Oct 2026 Shorts originality update details are critical for clip/meme channels.
