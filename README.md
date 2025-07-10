# MBTI-16-Personality-Quiz-Game-using-Java

Objective: To develop a Java-based console application that simulates the Myers-Briggs Type Indicator (MBTI) personality quiz. The goal is to determine the user's personality type based on responses to 15 carefully crafted psychological questions.

Overview: This project implements a simplified version of the MBTI (Myers-Briggs Type Indicator), a widely used personality assessment model. The quiz asks the user 15 multiple-choice questions designed to assess preferences across four dichotomies:
1.Extraversion (E) / Introversion (I)
2.Sensing (S) / Intuition (N)
3.Thinking (T) / Feeling (F)
4.Judging (J) / Perceiving (P)
Based on the user’s answers, the application calculates and displays their 4-letter personality type (e.g., INTJ, ESFP, etc.) and shows a short description of the type.

Key Features:
Interactive Console Interface: Simple, clean input prompts using Java’s Scanner class.
Real MBTI Logic: Uses four trait axes to determine the user's personality.
Trait Analysis: Tallies responses to determine dominant preferences.
Personality Descriptions: Displays brief summaries for all 16 MBTI types.
Input Validation: Handles incorrect answers gracefully by skipping them.

Technologies Used:
Technology	Description
Java (JDK 17)	Core programming language
IntelliJ / VS Code	Development environment
Console I/O	User interaction via CLI
Java Control Flow	Loops, conditionals, methods

Future Enhancements:
GUI version using Java Swing or JavaFX.
Store user results in a file or database.
Add progress bar or graphical summary of traits.
Include PDF export of quiz results and personality report.
Load questions from an external JSON or XML file for flexibility.
