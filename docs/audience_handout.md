# Audience Handout — Practical AI at Work

**Filtrona Lunch & Discussion for AI · 19 May 2026**

---

## 1. The main idea

AI is becoming a work habit. The value doesn't come from having access — it comes from knowing how to use it safely, clearly, and practically.

For Filtrona, the recommended starting point is **Microsoft 365 Copilot Chat**, because it's already included in our Microsoft 365 E5 license.

---

## 2. The six AI Golden Rules

1. **Protect data.** No confidential content in public AI tools.
2. **Give context.** Situation, audience, objective, constraints.
3. **Ask for format.** Table, email, checklist, script, summary, slide outline.
4. **Verify facts.** AI can sound confident while being wrong.
5. **Iterate.** Ask AI to improve, shorten, expand, compare, or challenge.
6. **You remain accountable.** AI is an assistant, not the business owner.

---

## 3. The CRAFT-V prompt method

Six parts. Use as many as the prompt needs.

```text
Context: What is happening?
Role:    Who should AI act as?
Action:  What exactly should it do?
Format:  What should the output look like?
Tone:    How should it sound?
Verify:  What assumptions, risks, or unknowns should it flag?
```

**Example:**

```text
Context: I need to follow up with a regional sales manager for missing
         weekly sales commentary.
Role:    Act as a professional business analyst.
Action:  Draft a concise email requesting the input before Friday.
Format:  Subject + email body.
Tone:    Friendly, clear, professional.
Verify:  List assumptions you made about deadline or relationship.
         Avoid sounding annoyed. Keep under 120 words.
```

---

## 4. The Copilot spectrum — get the names right

Do not worry about memorising licence language. Remember the business difference.

| Level | Use it for | Practical rule |
|---|---|---|
| **Safe default: Copilot Chat** | Drafting, summarising, brainstorming, structuring | Good starting point for general work help. Verify facts. |
| **Work context: Copilot in M365 apps** | Teams, Outlook, Word, Excel, PowerPoint support | Useful where the work already happens. Permissions and content quality matter. |
| **Governed scale: agents & workflows** | Repeatable processes, intake, approvals, routed tasks | Bring IT in when the use case needs company data, approvals, agents or integrations. |

Detailed licensing and entitlement notes are on the AI@Filtrona resource page.

## 5. Where to use Copilot

| Tool | Good for |
|---|---|
| Copilot Chat | General drafting, brainstorming, summaries, checklists |
| Teams | Meeting summaries, action items, follow-up drafts |
| Outlook | Email drafting, tone rewrite, long-thread summary |
| Word | First drafts, summaries, structured documents |
| Excel | Trend explanation, formulas, anomaly explanations |
| PowerPoint | First slide draft, story structure |
| Clipchamp | Quick training or communication videos |
| Power Automate | Repetitive workflow automation |

---

## 6. Approved-for-work vs personal-learning

This is the most important rule. Two columns.

**Approved for Filtrona work**

- Microsoft 365 Copilot Chat (Enterprise Data Protection)
- Microsoft 365 Copilot in Word / Excel / PowerPoint / Outlook / Teams (if licensed)
- Clipchamp, Power Automate, Power Apps, Power BI
- Copilot Studio agents on our tenant

**Fine for personal learning only — never for Filtrona work content**

- ChatGPT, Claude, Gemini (consumer versions)
- OpenAI and other public image / video generators
- InVideo, public coding assistants
- Anything where the prompt may be used to train a model

### The principle: classification follows content

> Confidentiality lives in the **content**, not the filename. Removing "Filtrona" from a file does not make the data safe to paste into a public tool.

**The practical test:** if a competitor or this customer saw the content, would there be a problem? If yes — it doesn't go in a public tool, no matter how you rename it.

---

## 7. Workflow patterns and Power Automate templates

Many productivity gains start as workflow discipline before they become advanced AI. A reusable pattern is:

**Capture → Route → Track → Assist**

- Capture inputs through Forms, SharePoint lists, Excel Online or Power Apps.
- Route approvals, reminders and escalations with Power Automate.
- Track status, ageing, bottlenecks and audit trail.
- Assist with Copilot for summaries, analysis and follow-up drafts — with human review.

Examples that follow this pattern: weekly reporting, eCAPEX-style approvals, visitor registration, issue logs, training requests and recurring status updates.

Useful templates using standard connectors:

- Weekly reminder 30 minutes before something is due
- Form submission → SharePoint list → email confirmation
- SharePoint item created → start and wait for approval
- Forward emails to a Teams channel
- Planner task status change → notify chat
- Email attachments saved to a OneDrive folder
- Schedule a reply to send at the perfect time
- Notify privately when someone fills out a form

> Premium connectors (Dataverse, SQL, Salesforce, SAP, custom APIs) require a paid plan. Flag those separately when you find a need.

---

## 8. Use cases by team — Filtrona context

| Team | Where to start |
|---|---|
| **Operations** | Shift handover summaries · SOP rewrites · deviation report drafting · downtime root-cause notes |
| **HSE** | Incident write-up assistance · toolbox-talk drafts · audit finding summaries · translation for site teams |
| **Supply chain** | Supplier non-conformance letters · delay-explanation drafts · PO &amp; spec comparisons · scenario summaries |
| **Commercial** | Customer meeting prep · account summaries · proposal drafts · objection-response coaching |
| **Finance** | Variance commentary first draft · forecast narrative · report explanation · period-close checklists |
| **People &amp; HR** | Training content · policy FAQs · onboarding guides · job description drafts |
| **IT &amp; Data** | DAX/Power Query help · script debugging · documentation · requirements drafts · data quality checks |
| **Anyone** | Email tone rewrite · meeting recap · long-thread summary · checklist generation |

---

## 9. For our technical population — code & data

AI is a pair-coding partner for:

- **Office Scripts** (TypeScript / JavaScript for Excel automation)
- **Power Query M** — transformation errors explained in plain English
- **DAX** — "why is this measure returning blank?"
- **Regex** — the one part of programming nobody enjoys
- **Error messages** — what they mean in your context

You don't paste your data into the prompt — you ask for help with the *shape* of the code. The data stays in your workbook.

---

## 10. Five things to try this week

1. Ask Copilot Chat to summarise one long email thread.
2. Ask Copilot to rewrite one difficult message professionally.
3. Turn meeting notes into action items with owners and dates.
4. Ask Copilot to explain a table or suggest a formula in Excel.
5. Identify one repetitive workflow that could be simplified with Power Automate.

---

## 11. Useful prompt templates

### Meeting summary

```text
Summarize this meeting for a business audience.
Output:
1. Key decisions
2. Action items with owners and dates
3. Open questions
4. Risks
5. Suggested follow-up email

Verify: list anything you inferred rather than heard directly.
```

### Email rewrite

```text
Rewrite this email to be concise, professional, and friendly.
Keep the meaning unchanged.
Avoid sounding passive aggressive.
Provide subject line and email body.

Verify: flag any sentences where you changed the meaning.
```

### Report analysis

```text
Act as a business analyst.
Review this report and identify:
- key trends
- unusual movements
- risks
- business implications
- recommended next actions

Output as a table with columns:
Observation | Evidence | Implication | Suggested action | Confidence

Verify: list assumptions and areas needing human review.
```

### Slide outline

```text
Create a 6-slide executive presentation outline.
Audience: senior business stakeholders.
Objective: explain the issue, evidence, options, recommendation,
and next steps.
Tone: clear, concise, decision-oriented.
Verify: note any data points you would need to confirm before
final draft.
```

### Workflow automation idea

```text
Act as a Power Automate consultant.
I currently do this repetitive task: [describe task].
Use only STANDARD connectors (Outlook, SharePoint, Teams, OneDrive,
Excel Online, Forms, Approvals, Planner) — no premium connectors.

Output:
1. Trigger
2. Steps
3. Required data
4. Risk / control points
5. Simple first version

Verify: flag any step that might quietly require a premium licence.
```

---

## 12. Share your use case

A new tile is live on the **AI@Filtrona** SharePoint hub: **Share your use case**.

It's a 5-minute Microsoft Form. The first batch of submissions opens our:

- **Monthly Best Use Case** spotlight
- **Top Contributors** recognition wall

The goal isn't perfection. It's learning out loud.

---

## 13. Resources

- **AI@Filtrona** — SharePoint → AI@Filtrona
- **Filtrona AI Community** — Teams channel for questions and ideas
- **Microsoft Learn — Copilot:** `learn.microsoft.com/en-us/copilot`
- **Microsoft Learn — Power Automate:** `learn.microsoft.com/en-us/power-automate`
- **Microsoft Learn — Copilot Studio:** `learn.microsoft.com/en-us/microsoft-copilot-studio`

---

*Questions, ideas, or "I tried this and it broke" stories — bring them to the Filtrona AI Community on Teams. There's no such thing as a silly question in here.*
