# Project Proposal

You'll spend the first **day** building a proposal document. This document should connect the functional design of your project (what does it do?) to a problem in the real world.  Below, we list all required aspects of your proposal document.

You and others can use this document to estimate the effort required to implement the project. Your project has a high risk of failure if:

- the envisioned product tries to do too much
- the envisioned product doesn't do enough
- the purpose of the product is not well-defined (too vague)

By writing a clear proposal document and getting feedback on it from multiple students and teachers, you can better avoid these risks!

## Problem statement

Write a statement about the problem that your finished product will solve. The problem[^1] has to be clearly described and very specific. We see two possibilities:

- There is a clearly defined problem that a reasonably large group of people have, which an app or visualization can solve particularly well.
- There is a widespread lack of knowledge or understanding that an interactive visualization is particularly suited to remedy.

In both cases, you should be able to define a target audience who have specific interests that match your project. Include that, too.

In total, keep the problem statement to four lines of text.

[^1]: *"The problem need not be a pressing societal need, but rather any perceived gap in a situation or experience. For example, the Insalata Caprese is a wonderful artifact, but hardly addresses a problem in the deepest sense of the word. [...] In effect, problem definition is the creation by the designer of an explanation of why the user experiences a gap. This diagnosis can be thought of as an identification of user needs that are not being met in the current state and/or the recognition of criteria for a high-quality solution."*---Karl Ulrich, Design (2011).

## Solution

Describe your solution in full detail.

- Summarize your idea in a single sentence, connecting it to the "gap" that you describe.

- Include a **visual sketch** of what the final product will look like for the user; if you envision the application to have multiple screens, sketch these all out separately. Clearly specify the possible user interactions, and include concrete examples of data. Your sketches do not have to be professional-looking, but they have to be complete and neat!

    ![](screens-proposal.png)

- Include a list of **main features** that will be available to users. All features should also be visible in the sketch. Keep it brief.

- Mark which features define the *minimum viable product* (MVP) and which parts may be optional to implement.

## Prerequisites

Describe the things that you'll have to get in order.

- List the **data sources** that you will use and whether you will need to transform the data before it is usable for your application. The list should include links to where the data sources can be found.

- List the **external components** (libraries like `d3-tip` or `SQLite`) that you need to implement certain features. Include the names, and if the component is not standard, include a link to its website.

- Include a review of **similar** mobile apps or related visualizations, in terms of features and technical aspects: what do they do? how have they implemented it? can you do it in the same way?

- Identify the **hardest parts** of implementing your application: think of technical problems or limitations that could arise during development and what possibilities you have to overcome these.

## Sanity check

Before continuing, compare your solution to the [project requirements](/reference/requirements) one last time. Also, is it still clear that your proposed project is indeed a solution to the stated problem?

## GitHub

All documentation and code of this project must be hosted on GitHub and updated
daily, in order for the staff to be able to monitor your progress. Please note
that the repository must be public!

To create such a document and get your project started, complete the following
steps:

1. Go to <https://github.com/new> and create a new code repository. Check the box to initialize the repository with a readme document:

   ![Check Initialize this repository with a README](readme.png)

2. Clone the repository to your computer using **git**. Don't know how? Head to the [reference](/reference/git)!

3. Edit the plain text document called **README.md**. The **.md** extension indicates its *Markdown* formatting style. Have you never written Markdown before? Refer to the [reference](/reference/markdown) for more information. Write your proposal in that document.

   The proposal document should be well-written and clearly formatted. Do not forget to include a
   title, your name, and a paragraph summary of the application goals at the top.

4. As you will need to include some sketches into your proposal, put these images in a **doc** folder inside your repository. (Use exactly that name, for standards' sake!)

5. Discuss the contents of your with fellow students and the teaching crew *before* handing it in!

6. Now, copy the URL of the GitHub page for your project and submit it below. It will be in this format: <https://github.com/stgm/project>.

Don't commit any code yet! Your repository should be clean for us to read, containing the **README.md**, a **doc** folder (exactly that name), pictures in the **doc** folder, and nothing else.

## What's next

The next step in your project is creating a design document. There, you'll describe how your project will be created according to the rules of the application framework that you're using.

Meanwhile, keep an eye on the **GitHub Issues** for your project. This is where you will get feedback on whether your project is accepted as it is described, or you need to make some changes.
