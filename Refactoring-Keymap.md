**Rationale**

Make it easier to refactor using the keyboard by adjusting the default keymap to supercharge the Option + Command prefix for the most common refactoring actions.

**Mechanism**

| Binding                       | Action             | Default |
| :---------------------------- | :----------------- | :-----: |
| Option + Command + A          | Annotate           |         |
| Option + Command + C          | Extract Constant   | Yes     |
| Option + Command + I          | Inline             |         |
| Option + Command + J          | Join Lines         |         |
| Option + Command + L          | Reformat Code      | Yes     |
| Option + Command + M          | Extract Method     | Yes     |
| Option + Command + P          | Extract Parameter  | Yes     |
| Option + Command + R          | Rename             |         |
| Option + Command + S          | Split Vertically   |         |
| Option + Command + T          | Surround With...   | Yes     |
| Option + Command + U          | Unwrap/Remove...   |         |
| Option + Command + V          | Extract Variable   | Yes     |
| Option + Command + Z          | Analyze Stacktrace |         |
| Option + Command + Return     | Last Edit Location |         |
| Option + Command + Up Arrow   | Extend Selection   |         |
| Option + Command + Down Arrow | Shrink Selection   |         |

Note: some of these are the default bindings (as denoted by _Yes_ in the _Default_ column).
