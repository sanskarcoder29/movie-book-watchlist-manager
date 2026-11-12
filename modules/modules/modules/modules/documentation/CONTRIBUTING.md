# Contributing Guidelines

Welcome to the Movie & Book Watchlist Manager project!

This document explains how all team members can contribute to the project, follow the same coding standards, and work together smoothly.

Our goal is to build a simple and useful Python application while learning and applying the Python concepts covered in Chapters 1–10.

## 1. Project Overview

The Movie & Book Watchlist Manager is a Python-based application that helps users manage their personal collection of movies and books.

Users will be able to:
- Add movies and books.
- View all saved records.
- Search by title.
- Filter records by genre and type.
- Update reading and watching status.
- Add and update ratings.
- Delete records.
- View top-rated entries.
- Check collection statistics.
- Save and load records using File I/O.

## 2. Project Rules and Restrictions

All contributors must follow these rules:

- Use Python concepts covered in Chapters 1–10.
- Do not use Object-Oriented Programming (OOP).
- Do not use external Python libraries.
- Do not use databases or external APIs.
- Use basic Python data structures such as lists, dictionaries, sets, and tuples.
- Use loops, conditional statements, strings, and File I/O wherever required.
- Keep the code simple and easy to understand.

## 3. Code Writing Guidelines

While writing code, please follow these guidelines:

1. Use meaningful variable and function names.
2. Keep the code simple and properly organized.
3. Add comments wherever they help explain the code.
4. Avoid unnecessary or repeated code.
5. Handle invalid user input properly.
6. Test your code before submitting it.
7. Make sure your code follows the agreed project structure.

## 4. GitHub Contribution Guidelines

We will use GitHub to manage and combine everyone's contributions.

Please follow these steps:

1. Make sure you have access to the project repository.
2. Always work on your assigned project module.
3. Create a separate branch for your changes.
4. Make changes only related to your assigned task.
5. Test your code before submitting it.
6. Commit your changes with a meaningful commit message.
7. Push your branch to GitHub.
8. Create a Pull Request to merge your changes into the main branch.
9. Wait for the project leader to review your changes.

Please do not directly push changes to the main branch.

## 5. Branch Naming Guidelines

Use simple and meaningful branch names.

Examples:

- feature/core-operations
- feature/search-filter
- feature/statistics
- feature/menu
- feature/file-handling

Choose a branch name based on the work you are doing.

## 6. Commit Message Guidelines

Write short and meaningful commit messages.

Examples:

- Add movie and book functionality
- Implement title search
- Add genre filtering
- Create statistics module
- Improve main menu
- Add file handling functionality
- Fix input validation errors

Avoid unclear commit messages such as:

- update
- changes
- final code
- new file

## 7. Pull Request Guidelines

Before creating a Pull Request:

- Check that your code is working.
- Make sure there are no unnecessary files.
- Explain what changes you have made.
- Mention which feature or module you have worked on.
- Report any known issues.

The project leader will review the Pull Request before merging it into the main branch.

## 8. Common Data Structure

All members must follow the same basic dictionary structure while developing their modules.

Example:

    watchlist = {
        "Inception": {
            "type": "Movie",
            "genre": "Sci-Fi",
            "status": "Completed",
            "rating": 9
        }
    }

Do not change the common structure without discussing it with the team.

This will help us combine everyone's code easily.

## 9. Testing and Bug Reporting

Every contributor should test their assigned functionality.

If you find a problem:

- Explain what went wrong.
- Mention the steps to reproduce the problem.
- Share the error message if available.
- Suggest a possible solution if you have one.

Please report bugs and project-related issues through GitHub Issues whenever possible.

## 10. Team Communication

- Stay active in the project group.
- Share your progress regularly.
- Ask questions whenever you face difficulties.
- Inform the team if you are unable to complete an assigned task on time.
- Share useful suggestions and improvements.
- Help other members whenever possible.

## 11. Final Note

This is a collaborative learning project. Everyone is expected to contribute, learn, and understand their part of the application.

The main objective is not just to complete the project but also to understand how basic Python concepts work together in a real application.

Let's work together and build something useful!

Happy Coding!
