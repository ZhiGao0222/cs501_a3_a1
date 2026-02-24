# Assignment 3 Question 1: Settings Screen

## Description
This project is a polished Android Settings screen built with Jetpack Compose. It demonstrates Row/Column layout mastery, extensive use of Compose Modifiers, and a variety of Material 3 components.

## Requirements Met
- **Layout Mastery**: Utilizes a main `Column` container with properly nested `Row` components for each setting item.
- **Modifiers**: Demonstrates the use of `padding`, `fillMaxWidth`, `weight`, `heightIn`/`sizeIn`, `align`, `border`, `clip`, `background`, and `clickable` to prevent truncation and align controls perfectly.
- **Material 3 Components (6+)**: Incorporates `TopAppBar`, `Card`, `Switch`, `Slider`, `Checkbox`, `Button`, `OutlinedButton`, `AssistChip`, `HorizontalDivider`, and `Snackbar`.

## Screenshots
![Settings Screen](screenshot1.png)

## AI Disclosure
I used Google's Gemini AI to assist me with specific technical issues in this assignment:
1. **Debugging**: AI helped identify a missing comma syntax error and a package name mismatch (`com.example.settingsscreen` vs `com.example.a3_q1`) that caused a runtime crash.
2. **Material 3 API Migration**: AI advised replacing the deprecated `ButtonDefaults.outlinedButtonBorder` with `BorderStroke` to fix a compilation error.
3. **Rubric Verification**: AI helped cross-check my code against the grading rubric to ensure all required Modifiers (specifically `Modifier.align`) were explicitly demonstrated.
