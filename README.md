This is a terminal-based expense sharing application inspired by Splitwise, designed to simplify the process of managing shared expenses among individuals and groups. Built using Object-Oriented Programming principles in C++, it allows users to create groups, add expenses, and view expense distributions across members efficiently.

Key Components:

1) Main & States Modules: These modules handle the user interaction and menu navigation. The States class manages transitions between different menu states and executes corresponding user actions like moving between group views or expense management options.

2) Colors Utility: A helper class for coloring console output to improve readability and user experience.

3) SplitPerson & Expense Classes: SplitPerson holds individual participant data (name, cost).
Expense represents a single expense entry and contains a list of participants and how the cost is split.

4) Group Class: Represents a collection of expenses for a single group. Users can add and view expenses associated with a group.

5) Groups Class: Manages all user-created groups. Provides functionality to create new groups and retrieve formatted group-level summaries.

Features:

1. Add participants and their individual contributions
2. Create and manage multiple expense groups
3. Track and display split-wise cost distribution per group
4. Simple CLI-based UI with support for menu-driven navigation
