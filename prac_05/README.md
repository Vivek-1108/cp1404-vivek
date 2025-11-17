# Practical 05 - Dictionaries and Code Reviews with PRs

**Author**: Vivek Dobariya  

## Overview
This repository contains solutions for Practical 05, which focuses on:
- Using **dictionaries** in Python for various tasks.
- Implementing **code reviews** using GitHub pull requests (PRs).
- Practicing collaborative coding practices to prepare for the IT industry.

## Contents
The repository includes the following programs:

### 1. `state_names.py`
- **Purpose**: Allows users to look up the full name of Australian states using their abbreviations.
- **Features**:
  - Accepts lowercase and uppercase inputs.
  - Prints all states and their full names neatly formatted.
  - Uses the EAFP (Easier to Ask Forgiveness than Permission) approach for error handling.

### 2. `hex_colours.py`
- **Purpose**: Enables users to look up hexadecimal colour codes for predefined colour names.
- **Features**:
  - Handles case-insensitive inputs.
  - Provides graceful error handling for invalid colour names.
  - Allows continuous input until a blank line is entered.

### 3. `word_occurrences.py`
- **Purpose**: Counts the occurrences of words in a user-provided string.
- **Features**:
  - Outputs word counts sorted alphabetically.
  - Aligns output neatly using string formatting.
  - Handles any input string gracefully.

### 4. `emails.py`
- **Purpose**: Stores users' emails and names in a dictionary.
- **Features**:
  - Extracts names from email addresses.
  - Allows users to confirm or edit extracted names.
  - Displays all stored emails and names in a formatted list.

### 5. `kivy_demo.py` and `kivy_layout.kv`
- **Purpose**: Demonstrates the use of Kivy for GUI programming.
- **Features**:
  - Adds a new label to the GUI layout.
  - Adjusts the label size to occupy 10% of the vertical space.

### 6. `wimbledon.py`
- **Purpose**: Processes data from a CSV file to display Wimbledon champions and their countries.
- **Features**:
  - Displays champions and the number of times they have won.
  - Lists countries in alphabetical order.
  - Uses appropriate data structures (list of lists, dictionary, set).

## Instructions
### Running the Programs
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the repository folder:
   ```bash
   cd practical_05
   ```
3. Run the desired program using Python:
   ```bash
   python state_names.py
   ```

### GitHub Workflow
- Each program is developed in its own branch (e.g., `prac_05_feedback`).
- Changes are committed frequently with meaningful messages.
- Pull requests (PRs) are created for code reviews before merging into `master`.

## Code Review Process
- Request a code review by mentioning a reviewer in the PR description (e.g., `@username`).
- Reviewers provide feedback via comments on the PR.
- Authors address feedback by making changes and pushing updates to the branch.
