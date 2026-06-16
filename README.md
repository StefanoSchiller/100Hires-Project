# 100Hires-Project

**Tools Installed:**

1. Cursor for Windows x64
2. ClaudeCode extension on Cursor.
3. Codex extension on Cursor.

**Steps completed:**

1. Opened Notepad on my computer.
2. Wrote the 3 lists I had to log: "Tool Installed", "Steps Completed", "Issues / How I solved them".
3. Downloaded Cursor for Windows x64.
4. Installed Cursor on Windows.
5. Created Cursor Account.
6. Set Up Cursor Account.
7. Logged in the Cursor App.
8. Opened for the Extensions tab.
9. Searched for ClaudeCode extension on the search bar.
10. Installed ClaudeCode extension.
11. Searched for Codex extension on the search bar.
12. Installed Codex extension.
13. Opened GitHub.
14. Created a GitHub account.
15. Logged into my GitHub account.
16. Created a repository.
17. Named it "100Hires Project".
18. Toggled the "Add README" option on.
19. Downloaded my repository.
20. Opened my downloaded repository from the "File" dropdown menu and selecting the "Open Folder" option in Cursor.
21. Clicked on the README.md file on the side menu to edit the created README on my repository.
22. Copied everything I wrote on my Notepad regarding this process.
23. Pasted it into the README.
24. Edited the spacing.
25. Numbered the lists.
26. Noticed I was editing locally.
27. Copied the URL HTTPS from my GitHub.
28. Used the shortcut Ctrl + Shift + P to open the Command Palette.
29. Used the command "Git: Clone" and pasted my repository URL.
30. Cursor requested I log into GitHub.
31. Logged into GitHub through Cursor.
32. Saved my repository locally.
33. Edited my README.md file on Cursor.
34. Opened Source Control.
35. Tried committing my changes to the README file and failed.
36. Configured my user.name and user.email through the cursor terminal.
37. Synced and pushed my repository to GitHub.

**Issues / How I solved them:**

1. Didn't know how to install extensions or where to find the option to do so in Cursor. Looked and read through all the options to find the "Extensions" tab. Found it and properly installed the required extensions.
2. Didn't know how to open my repository through Cursor. Asked ChatGPT how to open it and it gave me two solutions: cloning the repository directly from GitHub and copying the URL HTTPS from my GitHub and pasting it on Cursor or downloading my repository and opening it from Cursor. I downloaded my repository and opened it from Cursor.
3. After downloading and editing the README.md file, I realized that I was editing it locally, which meant my repository on GitHub would not update by itself and I would have to manually update it so I can push it. So I decided to clone my repository on Cursor through the URL instead.
4. Didn't understand why the spacing wasn't working the way I wanted or intended it to work. First I tried to edit the indent mode - didn't succeed. Tried with the indent size - failed again. Tried pressing the enter key on my keyboard twice - succeeded.
5. Wanted to put **bold** letters on my README.md to better organize the file but didn't know how to do so. Asked ChatGPT for help and quickly learned how to apply it on my file.
6. Didn't know how to commit or upload my changes. Asked ChatGPT how to do so and learned how to save, commit and push the repository through Source Control.
7. Couldn't commit my changes to the file because I needed to configure my "user.name" and "user.email" on Git and I didn't know how to do it. Asked ChatGPT how to configure and I learned how to do it through the Cursor terminal. Used the following command lines:

git config --global user.name "yourname"

git config --global user.email "[youremail@gmail.com](mailto:youremail@gmail.com)"





---



**# Research Phase — Cold Outreach Pipeline for B2B SaaS**

## What This Is

This repository contains primary research on cold outreach pipeline strategy for B2B SaaS — one of the most critical and evolving disciplines in modern sales.

The goal was to identify 10 genuine practitioners (not just thought leaders or bloggers) who are actively building, running, and teaching outbound systems, and to collect their real content — YouTube transcripts, LinkedIn posts, and other materials — as the foundation for a future playbook.

---

## Why Cold Outreach Pipeline

Cold outreach is the backbone of outbound sales. In B2B SaaS especially, where deal cycles are long and buyers are increasingly hard to reach, having a repeatable, scalable pipeline generation system is what separates growing companies from stalled ones.

This topic is also personally relevant: I'm building an AI automation agency targeting SMBs in Latin America, with a core product centered on WhatsApp and email-based lead qualification. Understanding how top practitioners build outbound systems — from prospecting and copywriting to sequencing and AI-assisted personalization — directly informs what I'm building.

---

## How I Selected These Experts

The selection criteria were simple but strict:

- **Practitioners first** — people who have personally run outbound campaigns, not just written about them

- **Active content creators** — posting regularly on LinkedIn, YouTube, or podcasts in the last 12 months

- **Range of angles** — the list covers cold email copywriting, outbound sequencing, AI-assisted prospecting, LinkedIn outreach, psychology of cold outreach, and agency-scale systems

Generic "top 10 sales influencers" lists were deliberately avoided. Each expert was vetted individually by reviewing their actual content before inclusion.

---

## The 10 Experts

| # | Name | Focus | Primary Platform |

|---|------|-------|-----------------|

| 1 | Jason Bay | Outbound frameworks & cold email strategy | YouTube + LinkedIn |

| 2 | Nick Cegelski & Armand Farrokh (30MPC) | Tactical sales breakdowns from top B2B reps | Podcast + YouTube |

| 3 | Alex Berman | Cold email templates & agency outbound | YouTube |

| 4 | Will Allred | Cold email psychology & data-backed writing | LinkedIn |

| 5 | Josh Braun | Buyer psychology & non-pushy outreach | LinkedIn + Podcast |

| 6 | Samantha McKenna | Research-led personalization (Show Me You Know Me) | LinkedIn |

| 7 | Michel Lieben (ColdIQ) | AI-powered outbound at agency scale | LinkedIn + Blog |

| 8 | Nick Abraham | Cold email infrastructure & deliverability at scale | YouTube + LinkedIn |

| 9 | Patrick Dang | Foundational cold email & sales training | YouTube |

| 10 | Florin Tatulea | Outbound sequencing & cold email frameworks | LinkedIn + Substack |

Full annotations with links and context: [research/sources.md](research/sources.md)

---

## Repository Structure

```

/research

  sources.md                  — annotated list of all 10 experts

  /linkedin-posts             — recent LinkedIn posts organized by author

  /youtube-transcripts        — video transcripts organized by author

  /other                      — additional materials

```

---

## What Was Collected

- **7 YouTube transcripts** pulled via the `youtube-transcript-api` Python library, organized by author inside `/research/youtube-transcripts/`

- **LinkedIn posts** manually collected from each expert's profile, organized by author inside `/research/linkedin-posts/`

- All sources documented with links and dates in `/research/sources.md`

---

## Tools Used

- `youtube-transcript-api` (Python) — for automated transcript collection

- Cursor — for scripting and repo management

- Git + GitHub — version control and delivery

---

*Research collected: June 2026*