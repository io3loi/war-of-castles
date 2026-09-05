The AI must update the project status after every completed task.
The AI must record every important change in the changelog.
The AI must record discovered problems in the bugs file.
If information is missing or contradictory, the AI must stop and ask for clarification.
Required Files
Before working, the AI must read:
PROJECT_RULES.md
GAME_DESIGN.md
CURRENT_STATE.md
TASK_QUEUE.md
CHANGELOG.md
DECISIONS.md
Completion Rule
After completing one task, the AI must:
Explain what it changed.
Explain how it checked the result.
Update CURRENT_STATE.md.
Update CHANGELOG.md.
Stop and wait for the next instruction.
Final Rule
Accuracy and consistency are more important than speed.
