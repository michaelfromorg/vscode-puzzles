# vscode-puzzle

vscode-puzzle is a super simple Visual Studio Code add-on that collects a problem from the internet and brings it directly into your editor. Practice your programming skills with ease.

## Features

vscode-puzzle currently supports problems from r/dailyprogrammer, Project Euler, and Coding Bat. It fetches a random problem for any of those three sites, creates a folder, and stores both a markdown file with the problem description and creates a `.py` file for you to begin your solution. Here's an example of an output.

![Displaying the problem](assets/creates-problem.png)

> In the future, there is a plan to support a different preferred export type (other than Python), and problems from different websites.

## Requirements

n/a

## Extension Settings

In the future, there will be an option to set your preferred solving language.

TODO: use the `contributes.configuration` extension point to set this up!

## Known Issues

TBD

## Release Notes

This is currently being built as a part of the Microsoft VS Code Hackathon. Release notes to come following this weekend.

### 1.0.0

The initial release of vscode-puzzle is described above.
