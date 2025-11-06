# GitHub Discussions Setup Guide

This document provides instructions for setting up GitHub Discussions with voting capabilities for the gyp_future repository.

## Prerequisites

GitHub Discussions must be enabled for the repository. To enable:

1. Go to repository Settings
2. Scroll down to "Features" section
3. Check the "Discussions" checkbox

## Recommended Discussion Categories

Once Discussions are enabled, configure the following categories:

### 1. Ideas (Voting Enabled)

- **Name**: Ideas / Идеи
- **Description**: Propose and vote on ideas for future development
- **Format**: Open-ended discussion
- **Voting**: ✅ Enable upvoting and downvoting
- **Icon**: 💡 (light bulb)

**Configuration Steps:**
1. Go to Discussions → Categories
2. Create new category "Ideas"
3. Enable "Enable voting" option
4. Set emoji to 💡
5. Save the category

### 2. General

- **Name**: General / Общее
- **Description**: General discussions about the project
- **Format**: Open-ended discussion
- **Voting**: Optional
- **Icon**: 💬 (speech balloon)

### 3. Q&A

- **Name**: Q&A / Вопросы и ответы
- **Description**: Ask questions and get answers
- **Format**: Question/Answer
- **Icon**: 🙋 (person raising hand)

## Discussion Templates

The repository includes a discussion template for Ideas:

- **Location**: `.github/DISCUSSION_TEMPLATE/idea.yml`
- **Usage**: Automatically suggested when creating a new discussion in the Ideas category
- **Fields**: 
  - Description
  - Problem Statement
  - Proposed Solution
  - Alternatives Considered
  - Additional Context

## Voting Instructions

To vote on ideas:

1. Navigate to the Discussions tab
2. Select the Ideas category
3. Click on an idea to view details
4. Use the ⬆️ upvote button to support the idea
5. The ideas with the most votes will appear at the top

## Pinning Important Ideas

Repository maintainers can pin important discussions:

1. Open the discussion
2. Click the "..." menu (top right)
3. Select "Pin discussion"
4. Pinned discussions appear at the top of the category

## Closing and Locking Discussions

When an idea is implemented or rejected:

1. Open the discussion
2. Add a final comment explaining the outcome
3. Close the discussion (prevents new comments)
4. Optionally lock the discussion (prevents further interaction)

## Moderation

Maintainers can:
- Edit or delete inappropriate comments
- Convert discussions to issues when ready for implementation
- Move discussions between categories
- Mark answers in Q&A discussions

## Links

- [GitHub Discussions Documentation](https://docs.github.com/en/discussions)
- [Discussion Templates Documentation](https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms)
