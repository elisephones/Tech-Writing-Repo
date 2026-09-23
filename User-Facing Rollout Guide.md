*Implementation Playbook*

# Knowledge Assistant Rollout Guide

A step by step guide to launching an AI Knowledge Assistant that is built on our vetted customGPT framework.

| Term | Definition |
|---|---|
| **Knowledge Base** | A curated collection of approved documents. |
| **Knowledge Assistant** | An AI assistant that answers questions using those documents as its evidence. |
| **Subject Matter Expert** | The owner who keeps a Knowledge Base accurate and current. |

---

*Purpose*

## Why this guide exists

This guide walks you through how to roll out a Knowledge Assistant to your business area. The goal is simple: make sure every assistant is built on trusted, governed knowledge that is accurate, easy to maintain, and aligned to what your business actually needs.

You do not need to be technical to follow it. Each phase below tells you what to do, who to involve, and what "good" looks like before you move on.

*The journey at a glance*

## Seven phases, from scope to launch

| Phase | Name | What it covers |
|---|---|---|
| 1 | Set up a Knowledge Base | Define what your assistant will know and who it serves. |
| 2 | Assess your content | Gather and vet the documents that will answer users' questions. |
| 3 | Define metadata | Describe each document so the assistant knows when to use it. |
| 4 | Upload your content | Move approved documents into your designated SharePoint folder. |
| 5 | Validate the assistant | Test with your Subject Matter Experts to confirm answers are accurate. |
| 6 | Launch | Open the assistant to all intended users and show them how to use it. |
| 7 | Maintain | Keep content current so answers stay accurate over time. |

---

*Phase 1*

## Set up a Knowledge Base

A Knowledge Base is a curated collection of approved documents that helps a Knowledge Assistant answer users' questions. A single Knowledge Assistant can connect to one Knowledge Base, or many.

### Define the scope of your Knowledge Base

Complete the [KB Inventory Framework](#) by defining:

- Business area and domain
- Knowledge Base name and description
- Subject Matter Expert (SME)
- Intended audience
- Users who should not have access (if applicable)
- Content risk level: Low, Medium, or High
- Content status: Current, Needs update, or Outdated
- Current content location (for example, SharePoint or Confluence)

> **START SMALL**
>
> It is fine for your first group of documents to be small. Begin with a focused set, then add more content later as you learn what your users ask.

### When should I create a separate Knowledge Base?

Create a separate Knowledge Base when the content:

- Should only be available to a specific audience or group of users, or
- Supports a different business function or topic that is not covered in an existing Knowledge Base.

---

*Phase 2*

## Assess your knowledge content

As you gather your content, make sure it fits the scope of your Knowledge Base and answers the questions your audience is likely to ask.

### Start with the questions your audience will ask

Define the types of questions your audience may have, then confirm your content can answer them.

> **EXAMPLE**
>
> Say you are building a Knowledge Assistant for Communication associates, scoped to the Client Communications domain. You might expect questions like:
>
> **"I need help sending a client communication."**
>
> **"There is a service outage and I need to let clients know."**
>
> Your content should include material that answers these anticipated questions.

> **A QUICK TEST**
>
> Ask yourself: "Would I want the assistant to use this document to answer an employee's question?"
>
> If yes, it likely belongs in your Knowledge Base.

### What content to include and what to leave out

| Include | Leave out |
|---|---|
| Policies, processes, and procedures | Draft or work in progress documents |
| Quick Reference Guides (QRGs) | Duplicate versions of the same document |
| Frequently Asked Questions (FAQs) | Expired or outdated guidance |
| Standard Operating Procedures (SOPs) | Documents without a clear owner |

**Supported formats:** PDF, TXT, DOCX

---

*Phase 3*

## Define metadata for your content

Metadata is simply information that describes each document: what it is, who it applies to, and when it should be used. It helps your Knowledge Assistant understand a document and choose the right one to answer a question.

For each document in your Knowledge Base, define the following:

| Field | Description | Example |
|---|---|---|
| **Document Name** | Title of the document | Claims Escalation Path |
| **Knowledge Base** | Name of the Knowledge Base | Claims Knowledge Base |
| **Owner** | Who maintains it | Abby Smith |
| **Business Area** | What function it supports | Claims |
| **Document Type** | What kind of document it is (FAQ, Policy, QRG, Process) | QRG |
| **Key Terms** | A few important terms within it | Adjustment, escalation, auto-adjudication |
| **Last Reviewed Date** | When the content was last reviewed | 2026-07-27 |

> **WHERE TO LOG IT**
>
> Use the [KB Documents with Metadata Template](#) to capture this information for every document you curate.

---

*Phase 4*

## Upload your content

To use the current GPT Knowledge Assistant framework, your content needs to live in a designated SharePoint Knowledge Base folder.

Once your Knowledge Base has been scoped and your content has been reviewed and defined:

1. **Request your folder.** Contact Elise Phonesavanh. A designated SharePoint Knowledge Base folder will be provisioned for you.
2. **Upload your content.** Upload all of your Knowledge Content to the designated folder.

---

*Phase 5*

## Validate the Knowledge Assistant

Once your content is published to your SharePoint folder, a customGPT will be created for you. This customGPT is the Knowledge Assistant that your users will interact with. It connects directly to your SharePoint Knowledge Base folder.

Your first Knowledge Assistant is for testing and validation. We recommend giving access only to your content SMEs and a small, specialized group of testers.

> **WHAT TO DO**
>
> Work with your testers to ask the assistant real questions and confirm it answers accurately and as expected before anyone else gets access.

---

*Phase 6*

## Launch

Once your SMEs and testers have thoroughly tested the assistant, give your approval to Elise Phonesavanh to launch. The Knowledge Assistant will then be made available to all intended users, beyond your initial group of testers.

### As the business owner, communicate:

- What the assistant does
- Where to access it
- Who should use it
- Example questions to try

Provide demonstrations and quick reference materials wherever they help people get started.

---

*Phase 7*

## Maintain your Knowledge Base

Knowledge Bases need ongoing maintenance, so responses stay accurate. Every Knowledge Base should have a designated SME who is responsible for reviewing and updating its content.

### Your SME should regularly:

- Replace outdated documents
- Remove obsolete versions
- Upload revised documents
- Review metadata for accuracy

### Recommended review cadence

| Content risk level | Recommended SME review frequency |
|---|---|
| **Low risk** | Annually, or when business changes occur |
| **Medium risk** | Every six months, or when updates are made |
| **High risk** | Quarterly, or immediately after policy or regulatory changes |

---

> **NEED HELP GETTING STARTED?**
>
> Reach out to Elise Phonesavanh to request your SharePoint Knowledge Base folder, coordinate testing, and approve your assistant for launch.
