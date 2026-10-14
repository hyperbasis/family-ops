# Family Ops: Keeping Household Matters Moving Beyond a Chat

How one household turned scattered information into a durable, human-controlled way to manage everyday affairs with AI assistance

**Co-creators:** The person behind the GitHub account **@hyperbasis** (human project initiator, system designer, real-world user, and final decision-maker) and **Kevin**, an AI assistant (contributing to discussion, requirements, methodology, and writing).

## Why Do Household Matters Never Seem to End?

I never set out to build an AI system. I simply wanted a clearer way to organize my life.

Every household has a steady stream of things to deal with: utilities and other routine expenses, bank transfers and charges, insurance policies and contracts, school notices, children's activities, car repairs, appointments, and letters from public authorities. Each one may be manageable on its own. The difficulty is that they keep arriving from different places. Some can be settled the same day; others require several exchanges, and some take months to reach a conclusion.

The trouble often comes later. What exactly did that letter say? Did I respond? Am I still waiting for the other party? Is this charge related to an earlier one? Is there a deadline I have forgotten?

What I really wanted was not an AI that would run my life. I wanted these matters to have a reliable history and current context, so that I could pick up where I left off without searching through everything or explaining the situation all over again.

## From One-Off AI Help to Collaboration That Can Pick Up Where It Left Off

I tried tools including Claude and ChatGPT. They are very good at individual tasks: understanding a letter, comparing documents, explaining a charge, or drafting an email. With AI assistance, many things that previously took considerable effort became much easier.

Over time, though, I realized that handling one conversation well is not the same as managing a matter that remains open for weeks or months. Conversations grow long and eventually end. Tools change. New messages about the same issue arrive through other channels. If the chat itself is the only record, important state can disappear during a handoff.

I began recording household matters in ordinary folders and indexes. Later, I migrated from an earlier set of tools and files into a new workspace. As the records grew, my original index was asked to do too much at once: act as a file directory, task list, history, and deadline tracker. That made it harder to maintain.

So I kept adjusting the approach while dealing with real household business. I separated original evidence from current status. I made sure information from different sources could return to the same matter. I distinguished complex ongoing cases from simple tasks. And I made it a rule that an AI taking over should first read existing records rather than ask me to repeat the entire background.

That is how **Family Ops V1** took shape. It has become part of the way I manage day-to-day household affairs.

## The Key Shift: Not Just Collecting Files, but Bringing Information Together

Household information does not live only in paper letters. It appears in email, calendars, school portals, messaging groups, websites, phone calls, and sometimes in something I say in passing. Family Ops is therefore, first and foremost, a way to receive and sort information from multiple sources.

### Paper Documents and Photos

I can photograph a paper notice or scan it into a PDF and pass it to the household assistant. AI can help identify the contents, dates, and actions required. But the original image or PDF is kept. A summary must never replace the underlying evidence.

### Email and Calendar

In my current setup, ChatGPT can, when the relevant connections and permissions are in place, search Gmail for messages related to household matters and consult Google Calendar for confirmed dates or appointments. This makes it possible to recognize that a new email is a reply to an existing matter, rather than turning every incoming message into a separate task.

### School Portals, WhatsApp, and Other Websites

Some information sits on platforms that a chat assistant cannot access directly, such as school portals, specific websites, or WhatsApp Web. When needed, a tool with browser capabilities, such as my execution assistant **Robot**, can collect the information and hand back its source, date, and as much of the original content as practical.

A collection tool should not independently declare a household matter finished, nor should it create a competing ledger of its own.

### Spoken Notes and Things I Notice Along the Way

Not every matter has a document attached. If I notice an unusual payment while I am out, or suddenly remember that I need to confirm an appointment, I can simply tell the assistant. The system can record it as **my own statement**, without presenting it as a fact verified by a bank, school, or other institution.

These are different entry points, not different systems. The important thing is that information, wherever it comes from, reaches one place responsible for sorting and following it up. Authorized sources can be collected automatically where that is practical. Everything else can still be entered by a person.

## What Happens After Information Arrives?

In Family Ops, one central role is responsible for the official state of household matters. I call this role the **Household Administrator** (事务官).

It receives information from me, files, email, calendars, and outside collection tools. It first decides whether the information concerns our household and whether it belongs to an existing matter. Only then does it determine what kind of record, if any, is needed.

Some items are ordinary notices that require no further action. Some are worth keeping for reference. Some are small tasks that can be completed the same day. Others contain appointments or deadlines. Only issues that need repeated contact, waiting, and multiple pieces of evidence become ongoing **Cases**.

If the same matter begins with a paper letter, continues with a Gmail reply, and ends with a phone confirmation, it should remain one matter, not turn into three conflicting records. If I am waiting for a reply, the state must say **Waiting**. If a decision is mine to make, the next step must be clear. A polished AI summary is not evidence that the matter has been resolved.

In V1, I use Google Drive for documents and working files, and a human-readable **Family Ledger** to see **Cases, Tasks, Deadlines, and Reference** items. Matters requiring continued attention have their own folders and records. Only events where a date actually matters go on the calendar. Brief operating and handoff instructions help a new person or a different AI pick up the work.

Ultimately, I want the system to answer four simple questions:

1. What is this about?
2. What do I need to do now?
3. When does it need to be done?
4. What happens if I do nothing?

## Working With It in Everyday Life, Not Living at My Desk

For me, the biggest change is not that I have another spreadsheet. It is that many things I once had to sit at a computer to handle can now be dealt with in the gaps of ordinary life.

For example, while waiting in line at a supermarket, I might suddenly want to check an appointment. Instead of opening my email, searching through messages, and comparing dates, I can ask my chat assistant by voice to look up the relevant correspondence and tell me whether the appointment has been confirmed and what remains unresolved. If a reply is needed, I then decide explicitly whether to have it drafted or sent.

Car maintenance works much the same way. I can ask, by voice, where things stand with a repair shop, whether any new dates have appeared in the correspondence, and whether I need to confirm anything. The assistant reads the available records and gives me a clear answer. I still decide what to do next.

None of this means that every action should happen automatically or without checks. Reading email, sending a reply, creating a calendar event, and visiting an external platform each require the appropriate connection, permissions, and actual execution capability. Sending messages, making payments, and other consequential actions still require explicit authorization and verification.

Convenience should not come at the cost of control.

## It Still Works Without AI

Family Ops does not depend on a particular AI to keep its records alive. Without AI, a family member can still put documents in the right place, update the ledger, note the next step, and maintain dates as necessary. AI simply reduces the time spent organizing, searching, and checking.

Today I use ChatGPT together with Google Drive, Gmail, and Google Calendar. I have also used Claude. That is my current tool choice, not a configuration everyone must copy. Someone else can choose a different AI, or use the approach entirely by hand. Folders, spreadsheets, and calendars can likewise be replaced by other tools that store information reliably and allow it to be exported.

Most importantly, **AI does not own a household's affairs**. The original documents, records, access rights, and final decisions belong to people. Official status should be maintained by an explicitly responsible role; other tools should collect information or make suggestions, rather than each creating its own version of the facts.

## More Than an Idea: A GitHub Template You Can Actually Use

I am sharing Family Ops as an independent GitHub project. It should explain why I built it, but also give others who face similar problems a practical starting point. I do not want readers to finish an article and then have to design the entire system from scratch.

The repository includes a copyable starter workspace. If the GitHub **Template repository** setting is enabled, readers can choose **Use this template** to create their own repository with the example files and instructions. The files can also be copied into a private workspace manually.

That is different from copying a README. A template repository carries over the folder and file structure, giving someone a foundation they can inspect, adapt, and maintain.

The starter is deliberately small but complete: a place for newly received information, a place for ongoing matters, a simplified ledger template, an example Case containing entirely fictional details, operating and handoff guidance, and optional prompts for AI assistance. It should also provide two ways to get started: one for people working manually and another for those who want to connect an AI.

Everything is an editable, removable example, not a rule about how other people must organize their lives.

After creating a repository from the template, a user should first establish a private workspace under their own control, put the ledger into an appropriate spreadsheet tool, decide who maintains it, and try the process with one small, entirely nonsensitive matter. Email, calendars, and other information sources can be connected later if they are genuinely useful.

A repository template copies structure and instructions only. It does not copy my Google account connections, access permissions, or automation settings. Nor does it mean that an unattended Agent has somehow been deployed for the user.

To protect privacy, the public template will contain **none of my family's real letters, contracts, bills, names, contact details, accounts, or credentials**. Users should likewise avoid committing their real household records to a public GitHub repository. The template is a starting point; each household's actual data belongs in its own controlled private space.

## V1 Today, and What May Come Later

Family Ops V1 already supports my current household workflow reliably. It is not perfect, and it does not attempt to automate everything at once. As new needs arise, I can refine the operating rules, template, or an appropriate AI Skill through actual use, while keeping the system simple, transparent, and portable.

Further ahead, I may explore putting more structured information into a database, or using retrieval-augmented generation (RAG) to handle a larger body of documents. Those are possible future directions, not capabilities already implemented in V1, and certainly not prerequisites for using the template.

From dealing with a single letter to keeping track of matters across multiple sources, Family Ops has stayed focused on one question: **How can people remain in lasting control of their own affairs while letting suitable tools handle repetitive, mentally draining information work?**

AI can change how efficiently we do things. People should still be at the center of their own lives.

## Explore the starter workspace

The repository contains **fictional examples**, not anyone's private household records. You can start manually or choose to add AI assistance later.

- [Getting started](GETTING_STARTED.md): a step-by-step manual and AI-assisted introduction.
- [Starter workspace](template/README.md): example folders, ledgers, and a fictional Case.
- [Optional AI prompts](template/AI_PROMPTS.md): examples to adapt and review.

## Privacy and safety

Keep actual family documents, financial records, contact information, credentials, and the working ledger in **separately controlled private storage**, never in a public GitHub repository. Original evidence should remain under the household's control.

Copying this repository or using it as a template does **not** connect email or calendars, deploy an AI agent, establish automations, or grant permissions. Any integration requires independent setup and explicit authorization.

The public project narrative and example workspace are separate from the private operational records of Family Ops.

## License

The original article, documentation, and fictional starter materials in this repository are shared under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You may copy, adapt, and share them, including for commercial purposes, provided you give appropriate credit, link to the license, and indicate whether you made changes.

Attribution: **[@hyperbasis](https://github.com/hyperbasis)**, Family Ops project initiator and author, with AI-assisted discussion and drafting credited above. The license does not grant access to private household records, personal data, accounts, or third-party materials.
