# Learning Journal Template

A learning journal template to help you track your learning journey and to keep you accountable.

_This template is generated and adapted from the [100-days-of-OSS-template](https://github.com/open-sauced/100-days-of-oss-template) by OpenSauced._

## Instructions

If you want to learn alone, we recommend using this template to keep track of your learning and keep you accountable, especially during the **Month of Learning challenge** at [Virtual Coffee](https://virtualcoffee.io/). You can use it as a starting point, customize it to your needs, and record your progress even after the challenge ends.

You will use Markdown to work on your progress. If you need to familiarize yourself with Markdown, you can read the docs about [Markdown's basic syntax](https://www.markdownguide.org/basic-syntax/).

You can create a new repository for your journal or you can fork this repository. Read more about how to do it in the [Getting Started](#getting-started) section.

## Set a Goal

Before you start, set a goal for yourself. Set weekly goals and/or goals for the month. Then ask yourself, will setting weekly goals help you achieve your goals for the month?

For example, you may want to learn accessibility for 1 hour/week, 10 hours/week, or complete one lesson/day. Maybe your goal involves creation. You may want to write an article, a lightning talk, or a conference talk based on your learning. The sky is the limit!

Declaring that in your README will help you stay focused and motivated. Take a look at the [`readme-template.md`](./readme-template.md) for inspiration.

## Getting Started

There are a couple of ways to use this template. You can create a new repository using this template or fork this repository. We will walk you through them both.

> ⚠️ Before getting started, always ensure you **work on your changes in your forked repository** and _not directly_ in this repository.

### Creating a New Repository Using This Template

1. Click the green "Use this template" button on the top of this repository.
2. Click the "Create new repository" from the dropdown menu.
3. Fill in the repository name and description (optional). Leave the "Include all branches" checkbox unchecked — you only want the default branch.
4. Click the green "Create repository" button.
5. Follow steps 3-9 in the [Forking This Repository](#forking-this-repository) section below to record your learning progress.

### Forking This Repository

1. Fork this repository by clicking the fork button on the top.
2. Clone _your forked repository_ to your local machine.

   - Go to _your forked repository_ on GitHub.
   - Click the "<> Code" button and copy the HTTPS link.
   - In your terminal on your local machine, navigate to the directory where you want this repo to live. Then run this command:

     ```bash
     git clone <https-link>
     ```

     Paste the HTTPS link that you've copied. For example:

     ```bash
     git clone https://github.com/<username>/learning-journal-template.git
     ```

3. Create a new file and name this file anything you want, e.g., `accessibility-learning-journal.md`. This file will be where you update your learning progress. You can use the template in the [`journal-template.md`](./journal-template.md) file. Copy and paste the template into your progress track file, and customize it to your need.
4. Create a new branch for each challenge day if you want to keep your work separate.

   - In your terminal, run this command:

     ```bash
     git checkout -b <new-branch-name>
     ```

     You can name the branch anything, e.g., `day-1`. Then the command will be:

     ```bash
     git checkout -b day-1
     ```

5. Update the [`table-of-contents.md`](./table-of-contents.md) file by adding the link to the target day in the progress track file. You can skip this if you don't want to use a table of contents.

   ```markdown
   [Day X](./file-name.md#day-x)
   ```

   For example:

   ```markdown
   [Day 1: HTML list tags](./journal-template.md/#day-1-february-1-2024--html-list-tags)
   ```

6. Add and commit your work to your branch.

   - In your terminal, run these commands:

     ```bash
     git add .

     git commit -m "Your commit message"
     ```

     Change the "Your commit message" with your message. For example:

     ```bash
     git commit -m "Add day 1"
     ```

7. Push your changes to _your forked repository_.

   - In your terminal, run this command:

     ```bash
     git push -u origin <your-branch-name>
     ```

     Change the `your-branch-name` to your current branch name. For example:

     ```bash
     git push -u origin day-1
     ```

8. Create a pull request and merge your changes.
   - Go to _your forked repository_ on GitHub.
   - Click the green "Compare & pull request" button.
   - Modify the title if necessary and write the description of your changes.
   - Create a pull request by clicking the green "Create pull request" button.
   - Merge your changes into the `main` branch by clicking the green "Merge pull request" and the "Confirm merge" button.
9. Repeat steps 4 or 5 to 8 for each day of the challenge.

## Tips for making the most out of Month of Learning challenge

- Update your journal daily, even if you only have time to learn briefly.
- If you need help, ask for help! You can ask a friend, a mentor, or the community for help. <br> In Virtual Coffee, you can ask for one in the `#help-and-pairing` channel on Slack.
- Share your progress with the community or in public regularly. It will motivate you, keep you accountable, and inspire others, too
