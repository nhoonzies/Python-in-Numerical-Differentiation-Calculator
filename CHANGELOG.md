Project Changelog

Numerical Differentiation Calculator

[1.1.0] - Week 2

Focus: Input Validation & Error Handling

Added Validation Layer: Implemented a pre-computation check to verify all input fields before the mathematical engine runs.

New "Validation Status" Log: The Solution Trail now explicitly starts with a "PASS" or "FAIL" status to fulfill auditing requirements.

Error Messaging: Created user-friendly error details for common issues such as non-numeric inputs for x and h.

Division-by-Zero Protection: Added a specific check to prevent a crash if the step size (h) is set to zero.

Empty Field Detection: The app now detects if the user attempts to compute without filling in the function, x value, or step size.

[1.0.0] - Week 1

Focus: UI Skeleton & Core Engine

Initial UI Build: Developed the main application window using Tkinter with a clean, modern layout.

Numerical Engine: Integrated the Central Difference Method formula for calculating derivatives.

Quick Functions Pad: Added a button grid for easy entry of common functions like sin, cos, exp, and log.

Solution Trail Panel: Created the scrollable text area to display the "Given," "Method," and "Steps" of the calculation.

Final Answer Display: Implemented a dedicated highlighted area for the final numerical result.

Repo Initialization: Hosted the source code on GitHub for version control and group collaboration.

Key Validation Rules Implemented

Required Fields: Function f(x), x value, and Step size (h) cannot be empty.

Type Checks: Numerical inputs must be floating-point numbers.

Range Checks: Step size (h) must not be zero to avoid division errors.

Syntax Checks: Function strings must utilize restricted, safe mathematical terms (e.g., np.sin, exp).
