**Rationale**

Make it easier to refactor using the keyboard by adjusting the default keymap to supercharge the Option + Command prefix for the most common refactoring actions.

**Mechanism**

| Binding                       | Action             | Default |
| :---------------------------- | :----------------- | :-----: |
| Option + Command + A          | Annotate           |         |
| Option + Command + C          | Extract Constant   | Yes     |
| Option + Command + I          | Inline             |         |
| Option + Command + J          | Join Lines         |         |
| Option + Command + L          | Reformat Lines     | Yes     |
| Option + Command + M          | Extract Method     | Yes     |
| Option + Command + P          | Extract Parameter  | Yes     |
| Option + Command + R          | Rename             |         |
| Option + Command + V          | Extract Variable   | Yes     |
| Option + Command + Z          | Analyze Stacktrace |         |
| Option + Command + Return     | Last Edit Location |         |
| Option + Command + Up Arrow   | Extend Selection   |         |
| Option + Command + Down Arrow | Shrink Selection   |         |

Note: some of these are the default bindings; some of them are not.
