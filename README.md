# Software Engineering Labs 1–4

**Student:** G.V.N. Sreeharsha  
**SRN:** PES1UG24CS163  
**Section:** C  
**Course:** Software Engineering Laboratory

This repository consolidates navigation for Labs 1–4. Labs 1–3 use the **Customizable Subscription Box Scheduler** problem statement; Lab 4 is the **Q*bert Repair Lab**. The original repositories are preserved as the source of truth for the original submission artifacts.

## Labs at a glance

| Lab | Focus | Contents | Original repository |
|---|---|---|---|
| Lab 1 | Requirements engineering | Requirements table, use-case diagram, use-case flow, complete DOCX/PDF submission | [PES1UG24CS163_LAB_01](https://github.com/harsha2240/PES1UG24CS163_LAB_01) |
| Lab 2 | Agile backlog and sprint simulation using Jira | Lab report PDF | [PES1UG24CS163_LAB_02_JIRA](https://github.com/harsha2240/PES1UG24CS163_LAB_02_JIRA) |
| Lab 3 | Component modelling and architecture selection | Editable component diagram source, PDF export, architecture justification, complete submission PDF | [PES1UG24CS163_LAB_03](https://github.com/harsha2240/PES1UG24CS163_LAB_03) |
| Lab 4 | Vibe coding / Q*bert repair | Python game, before/after videos, chat history evidence | [35_qbert](https://github.com/harsha2240/35_qbert) |

## Consolidated lab folders

- **[Lab 1 – Requirements](./Lab-1-Requirements/)**: [complete submission PDF](https://github.com/harsha2240/PES1UG24CS163_LAB_01/blob/main/Complete-Submission/SE_Lab1_Customizable_Subscription_Box_Scheduler.pdf), [editable DOCX](https://github.com/harsha2240/PES1UG24CS163_LAB_01/blob/main/Complete-Submission/SE_Lab1_Customizable_Subscription_Box_Scheduler.docx), [UML diagram](https://github.com/harsha2240/PES1UG24CS163_LAB_01/blob/main/UML/Subscription_Box_Use_Case_Diagram.png)
- **[Lab 2 – Jira](./Lab-2-Jira/)**: [report PDF](https://github.com/harsha2240/PES1UG24CS163_LAB_02_JIRA/blob/main/PES1UG24CS163_LAB_02_JIRA.pdf)
- **[Lab 3 – Architecture](./Lab-3-Architecture/)**: [complete submission PDF](https://github.com/harsha2240/PES1UG24CS163_LAB_03/blob/main/PES1UG24CS163_Lab3_COMPLETE_SUBMISSION.pdf), [editable draw.io diagram in this repo](./Lab-3-Architecture/PES1UG24CS163_Lab3_Component_Diagram.drawio)
- **[Lab 4 – Q*bert](./Lab-4-Qbert/)**: [Python source in this repo](./Lab-4-Qbert/game.py), [before video](https://github.com/harsha2240/35_qbert/blob/main/Lab-4/BEFORE.mp4), [after video](https://github.com/harsha2240/35_qbert/blob/main/Lab-4/AFTER.mp4), [LLM chat history](https://github.com/harsha2240/35_qbert/blob/main/Lab-4/VIBE_CODING_CHAT_HISTORY.pdf)

## Get the complete lab files in one checkout

The `Original-Lab-Repositories/` directory contains Git submodules pointing to the four original repositories. This keeps each original submission intact and makes all its files available together when the submodules are initialized.

Clone the consolidated project and all four lab repositories:

```bash
git clone --recurse-submodules https://github.com/harsha2240/SE-ALL-Labs-1-4-.git
```

If you already cloned without submodules, run this inside the repository:

```bash
git submodule update --init --recursive
```

Submodule shortcuts: [Lab 1](./Original-Lab-Repositories/Lab-1-Requirements/), [Lab 2](./Original-Lab-Repositories/Lab-2-Jira/), [Lab 3](./Original-Lab-Repositories/Lab-3-Architecture/), and [Lab 4](./Original-Lab-Repositories/Lab-4-Qbert/).

## How the labs connect

1. **Lab 1** defines requirements and use-case behaviour for the subscription box scheduler.
2. **Lab 2** applies Agile planning concepts through a Jira backlog and sprint simulation.
3. **Lab 3** maps the same project into components, interfaces, and a selected architecture.
4. **Lab 4** is a separate AI-assisted debugging exercise that repairs and extends a Q*bert-style game.

## Repository note

The required deliverables (PDF, DOCX, PNG, and MP4) are included as files in the consolidated lab folders, alongside the editable Lab 3 diagram source and Lab 4 Python source. The original lab repositories are also preserved as submodules and linked above for reference.

## Submission reminder

Use the instructor's latest checklist for required screenshots, Jira evidence, editable source files, video duration, and LLM conversation links. This index improves navigation; it does not replace the original submissions.
