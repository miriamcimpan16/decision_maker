# decision_maker
decision_maker

A decision journal with memory. Instead of just weighing pros and cons for a single choice, the app remembers how your past decisions turned out and uses that history to help you make better ones in the future.

Overview

When you're about to make a decision, it's easy to forget how a similar situation played out before. decision_maker closes that loop: it tracks the decisions you make, checks in with you after a set amount of time to see how they went, and surfaces that history the next time you face something similar.

How it works:


1. Start a decision

The user enters the decision they're facing, along with some context. They pick an existing category or create a new one.

2. Check for related decisions

The app looks for past decisions in the same (or a similar) category.
If a similar decision is still pending (no recorded outcome yet), the app reminds the user and asks if they want to close it out first.
If a similar decision is completed, the app shows how it turned out, as a reference point.

3. Pros and cons

The user can write their own arguments, or let the app generate them.
If AI-generated, the model uses the given context — and, when available, insights from similar past decisions — to produce more relevant arguments.
Each argument is tagged with its source (user or AI) for transparency.



4.Final choice

The user picks their decision and sets a time horizon for when its impact will be clear (e.g. 1 week, 1 month, 3 months, 1 year, or a custom period). The decision is saved with status pending.

5.Check-in

When the chosen time horizon passes, the app prompts the user to record the outcome. Status changes to completed.
If ignored, the decision stays pending and will resurface the next time the user logs a related decision (see step 2).

Python = motorul
CustomTkinter = caroseria și bordul (ce vezi)
JSON = portbagajul unde se păstrează lucrurile
OpenAI API = un prieten foarte deștept pe care îl întrebi când ai nevoie
PyInstaller = fabrica care transformă proiectul într-un program .exe

