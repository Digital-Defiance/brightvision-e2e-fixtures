# brightvision-e2e-fixtures

Tailor-made fixture repositories used by BrightVision LLM e2e and integration tests.

## Workspaces

- `hello-workspace`
- `context-workspace`
- `tasks-seeded-workspace` — committed `.cecli/todos.json` matches mocked Tasks e2e (`sampleTodoStore`)
- `edit-block-workspace`

`agent-todo-char-split-workspace` is **not** pinned here; BrightVision creates it on demand
(`ensureAgentTodoCharSplitWorkspace()` in the superproject) for post-/agent char-split `UpdateTodoList` tests.
