- The original source code was violating almost all guidelines for clean code and SOLID principles. To name a few:
    - non-descriptive variable names (`ot`, `nt`)
    - no verbs in bools (`good`, `appr`)
    - pyramid of doom
    - unnecessary parentheses
    - uneccessary new lines
    - no interfaces whatsoever
- The Speaker class is responsible for everything, which is a major problem when it comes to the scalability of this class
- All of them.
- The techniques I applied for refactoring were:
    - Extracting almost every class into an interface
    - Moved the logic to the services
    - Removed the pyramid of doom
    - Introduced dependency injection 