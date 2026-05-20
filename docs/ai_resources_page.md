# AI@Filtrona — Resources Page

**A practical reference for everyone after the Lunch & Discussion for AI session.**
*Maintained on the AI@Filtrona SharePoint hub.*

---

## Start here — simple decision rule

For daily work, start with approved Microsoft tools. For public AI tools, use generic learning examples only — never Filtrona work content. For repeatable processes, think **Capture → Route → Track → Assist** and bring IT in when the use case needs work-data grounding, custom agents, approvals, premium connectors or external integration.

## What our Microsoft 365 E5 environment gives us

These are useful Microsoft capabilities available in or around our environment. Some are included, some depend on add-on licence, trial, tenant setting or consumption model. Check with IT before positioning anything as production-ready.

| Capability | What it is | Where to access |
|---|---|---|
| **Microsoft 365 Copilot Chat** | Web-grounded AI chat with Enterprise Data Protection | `m365copilot.com` or the Microsoft 365 Copilot app |
| **Power Automate** (seeded) | Cloud flows with all **standard connectors** | `make.powerautomate.com` |
| **Microsoft Forms** | Surveys, quizzes, and intake forms | `forms.office.com` |
| **Copilot Studio for Teams** | Subset of Copilot Studio for in-Teams agents | Inside Microsoft Teams |
| **Copilot Studio standalone trial** | 30 days free, extendable to 60 days | `copilotstudio.microsoft.com` |
| **Security Copilot** | Security-focused Copilot capabilities may depend on tenant allocation and configuration | Microsoft Security stack / IT Security |
| **Office Scripts** | TypeScript automation for Excel Online | Inside Excel Online |
| **Clipchamp**, **Power BI Pro**, **SharePoint**, **OneDrive**, **Teams**, **Outlook**, **Word**, **Excel**, **PowerPoint** | Standard productivity apps | Microsoft 365 portal |

### What is *not* automatically included with E5

- **Microsoft 365 Copilot** (the paid add-on, ~$30 / user / month enterprise list price). This is what enables Copilot to read your work email, files, and Teams content via Microsoft Graph.
- **Copilot Studio ongoing capacity** (consumption-based / Copilot Credits / Azure billing depending on setup)
- **AI Builder / advanced AI workflow capacity** (requires current Microsoft licensing check before use)
- **Power Automate Premium connectors** (Dataverse, SQL, Salesforce, SAP, custom APIs)

---

## Reusable workflow pattern

Use this pattern when you see repeated manual chasing:

| Step | What it means | Microsoft stack examples |
|---|---|---|
| **Capture** | Collect clean inputs once | Forms, SharePoint List, Excel Online, Power Apps |
| **Route** | Send the right task to the right person | Power Automate, Outlook, Teams, Approvals |
| **Track** | Show status and audit trail | SharePoint views, Excel tables, Power BI |
| **Assist** | Draft summaries and next steps | Copilot Chat, Copilot in Excel/Word/Teams |

Applies to weekly reporting, eCAPEX-style approval tracking, visitor registration, issue logs, training requests and recurring status updates.

---

## Approved for Filtrona work

> Use these freely for work content. Still follow normal internal data-handling policies.

| Tool | Use it for |
|---|---|
| **Microsoft 365 Copilot Chat** | General drafting, brainstorming, summaries, checklists |
| **Copilot in Word / Excel / PowerPoint / Outlook / Teams** | App-native AI (where the user is licensed for the M365 Copilot add-on) |
| **Power Automate** (standard connectors) | Approvals, reminders, form intake, notifications, file routing |
| **Power Apps** | Internal forms and lightweight apps |
| **Power BI** | Reports, dashboards, AI-assisted narratives |
| **Clipchamp** | Internal training and communication videos |
| **Copilot Studio agents on our tenant** | Custom agents grounded in our SharePoint/Teams content |
| **Microsoft Forms** | Surveys, quizzes, intake (including the AI use case submission) |

---

## Fine for personal learning — never for Filtrona work content

> Public AI tools are great for learning. **Do not paste Filtrona content into them.**

| Tool | Use it for |
|---|---|
| **ChatGPT** (consumer) | General learning, prompt practice |
| **Claude** (consumer) | General learning, writing experimentation |
| **Gemini** (consumer) | Prompt practice, exploration |
| **Public image / video generators** | Personal creative exploration |
| **InVideo** (public site) | Personal experimentation |
| **Public coding assistants** | Learning algorithms or syntax in a personal sandbox |

> ⚠️ Anything where the prompt may be used to train the model is **not** appropriate for work content, regardless of how interesting the tool looks.

---

## 🔐 The data security principle (applies across both tables above)

**Classification follows content, not metadata.**

Removing "Filtrona" from a filename, redacting a customer name, or renaming a workbook does *not* make the underlying data safe. The data inside is what classifies the file.

**The test:**
> *If a competitor, customer, or supplier could see this content, would there be a problem?*
>
> If yes — the content stays inside Filtrona-approved tools, no exceptions.

This rule is the same in both columns above. Approved-for-work tools have Enterprise Data Protection in place. Public tools do not. The content classification doesn't change based on which website you paste it into.

---

## Copilot Web mode vs Work mode — the practical difference

This is the most common confusion. Here's the plain-English version:

| Mode | Knowledge source | When to use |
|---|---|---|
| **Web** | The public internet (via Microsoft's grounded search) | General questions, definitions, summaries of public information, brainstorming |
| **Work** | **Your** organisation's Microsoft Graph: your emails, files, Teams chats, calendar | Anything that depends on internal information |

**Important:** the **Work** toggle requires a paid **Microsoft 365 Copilot** add-on license. Without that add-on, you only have the Web mode (which is what Copilot Chat is — and Copilot Chat still has Enterprise Data Protection on prompts and responses).

*Source: Microsoft Learn — "Decide which Copilot is right for you" (2026).*

---

## Trials and experiments — try responsibly

For colleagues who want to experiment beyond daily Copilot usage, trial options may be available depending on tenant policy and Microsoft licensing at the time. Treat trials as a sandbox for learning, not a production commitment.

Practical rule:

- Use generic examples only during trial exploration.
- Do not connect sensitive work data without IT approval.
- Bring useful ideas back as a business use case before scaling.
- Let IT confirm licensing, capacity, connectors and governance before anything becomes operational.

---

## Power Automate templates — start here

These templates all use **standard connectors only** (included with our M365 license — no premium required):

- Follow up on a message
- Schedule a reply to send at the perfect time
- Forward your emails to a channel
- Automate weekly reminders and updates in a chat
- Save email attachments to OneDrive
- Get notified privately when someone fills out a form
- Notify a chat when Planner tasks change status
- Send approval request when item added to SharePoint list

Browse the full template gallery (filter to "Microsoft 365") at: `make.powerautomate.com → Templates → Top picks`.

---

## Internal channels — where to ask, share, and learn

| Where | What for |
|---|---|
| **AI@Filtrona** SharePoint hub | Curated tools, training, your use case submissions |
| **Filtrona AI Community** (Teams) | Day-to-day Q&A, prompts, small wins, troubleshooting |
| **Share your use case** form | Formal submission for recognition (Top Contributors, Monthly BEST) |
| **IT** | Anything that needs an admin ticket, licence question, or premium capacity request |

---

## Trusted external sources for ongoing learning

Use these for personal upskilling — *not* for production decisions about our tenant configuration (always confirm with IT for those).

- **Microsoft Learn** — `learn.microsoft.com/en-us/copilot` · official, free, kept current
- **Microsoft Learn — Power Automate** — `learn.microsoft.com/en-us/power-automate`
- **Microsoft Learn — Copilot Studio** — `learn.microsoft.com/en-us/microsoft-copilot-studio`
- **Microsoft 365 Copilot blog** — `microsoft.com/en-us/microsoft-365/blog/category/microsoft-365-copilot`
- **Microsoft Power Platform community** — `community.powerplatform.com` · open Q&A from practitioners

---

## Quick reference card — the rules in 10 lines

1. Copilot Chat with EDP is included with our M365 E5 — use it now.
2. Microsoft 365 Copilot (the paid add-on) is what reads your work data; ask IT.
3. Copilot Studio has a 30-day trial; agents keep running for up to 90 days after expiry.
4. Standard Power Automate connectors are free with our licence; premium isn't.
5. ChatGPT, Claude, Gemini (consumer) are for personal learning only.
6. Confidentiality lives in content, not the filename.
7. Always verify AI output — especially numbers, names, dates, policies.
8. Use CRAFT-V to structure prompts (Context, Role, Action, Format, Tone, Verify).
9. Share what works on the AI@Filtrona hub.
10. You stay accountable for what you send.

---

*Last reviewed: May 2026. Facts in this page are traceable to Microsoft Learn or microsoft.com product pages. Where Microsoft updates a feature, this page is updated within one working week.*
