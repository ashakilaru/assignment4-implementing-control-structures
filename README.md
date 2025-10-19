# assignment4-implementing-control-structures

(Java 17 & C++17)

This repo contains two implementations of the employee scheduling application required for Assignment 4:
- `java-scheduler` (Java 17, Maven)
- `cpp-scheduler` (C++17, CMake)

Both programs:
- Collect employee names and daily shift preferences (optionally ranked).
- Assign shifts for 7 days (Morning, Afternoon, Evening).
- Enforce: no more than 1 shift/day per employee, max 5 days/week.
- Ensure at least 2 employees per shift per day (random fill if needed).
- Detect & resolve conflicts when preferred shifts are full.

## Quick links
- Java: `java-scheduler/README.md`
- C++: `cpp-scheduler/README.md`
- Submission instructions: `deliverables/submission_instructions.txt`

Follow the language-specific README for build/run steps. After you run each program, capture the terminal output as a screenshot and put it in `screenshots/` (filenames indicated there).
