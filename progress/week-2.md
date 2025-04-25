# Week 1 Summary (Apr 7–13)

**Project:** Task Manager App

[← Back to Progress Tracker](../progress-log.md)

## Time Tracking

| Task                                                    | Est. Time | Actual Time | Notes                                           |
| ------------------------------------------------------- | --------- | ----------- | ----------------------------------------------- |
| Task nesting and subtasks feature (Phase 1 Milestone 2) | 1 day     | 1 week      | Got caught up with assignment and security cert |
| Initial Google Calendar sync integration (stub)         | 2 hours   | 1 week      | Got caught up with assignment and security cert |

## Deliverables

| Planned                                                                       | Delivered                                               | Status |
| ----------------------------------------------------------------------------- | ------------------------------------------------------- | ------ |
| Task nesting and subtasks feature (Phase 1 Milestone 2)                       | Task nesting and subtasks feature (Phase 1 Milestone 2) | ✅     |
| Initial Google Calendar sync integration (even a stub or placeholder is fine) | Initial Google Calendar sync integration (stub)         | ✅     |

## Issues & Solutions

- **Issue:** Mixing business logic with UI components
  - **Solution:** Container-View Pattern
  - **Impact:** Separation of concerns, Reusable business logic, Improved maintainability
  - **Prevention:** Plan architecture and deployment strategies before implementation

frontend/
├── src/
│ ├── project/ # Project-related features
│ │ ├── containers/ # State management & business logic
│ │ ├── views/ # Presentational components
│ │ ├── hooks/ # Custom hooks for project operations
│ │ ├── services/ # API/business services
│ │ └── types/ # TypeScript definitions
│ │
│ ├── task/ # Task-related features
│ │ ├── containers/ # Task state & logic containers
│ │ ├── views/ # Task view components
│ │ ├── shared/ # Shared components (Input, etc.)
│ │ └── types/ # Task type definitions
│ │
│ └── shared/ # Application-wide shared code
├── components/ # Reusable UI components
└── theme/ # Theme configuration

## Key Metrics

- Commits: 33
- Deployments: 3
- Tests: N/A
- Coverage: N/A

## Learnings

- **Technical:**
  - Better understanding of Container-View Pattern
  - Service Layer
  - Custom Hooks Pattern
  - Type-Driven Development
  - Styled Components with Theme
  - Container-View Pattern
- **Process:**
  - Need clearer time-boxing
  - Architecture planning is crucial

## Next Week

1. Complete Google Calendar integration
2. Add task nesting feature
3. Implement testing framework

## Adjustments

- **What worked:**

  - Architecture planning

- **What needs improvement:**
  - Stay consistent with time-boxing
