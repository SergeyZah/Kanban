Open [http://localhost:5173/login](http://localhost:5173/login) with your browser to see the result.

# KanbanBoard

KanbanBoard is a Node.js application to create your success plan.

## Features

- User login and registration
- Creating new tasks
- Editing and deleting current tasks
- The ability to change deadlines, topic, and task description

## Stack

- React 19
- JavaScript XML

## Requirements

- React 19+
- npm 10+

## Installation

```bash
npm install
```

## Run Locally

Development mode:

```bash
npm run dev
```

Production build:

```bash
npm run build
npm run start
```

Lint:

```bash
npm run lint
```

Tests:

```bash
npm test
```

## Environment

The app uses `BASE_URL` for API requests.

Example:

```env
BASE_URL=https://wedev-api.sky.pro/api/kanban/
```

## Testing

The project uses `Jest` for unit tests.

Test files:

- [utils\calculatingProgress.test.ts](C:\Users\user\Desktop\Все\Skypro\diploma-work\src\utils\calculatingProgress.test.ts)
- [utils\croppingLines.test.ts](C:\Users\user\Desktop\Все\Skypro\diploma-work\src\utils\croppingLines.test.ts)
- [utils\FetchRightCover.test.ts](C:\Users\user\Desktop\Все\Skypro\diploma-work\src\utils\FetchRightCover.test.ts)
- [utils\fetchSelectedCourses.test.ts](C:\Users\user\Desktop\Все\Skypro\diploma-work\src\utils\fetchSelectedCourses.test.ts)

## Error Handling

API calls are located in [`\services\`](C:\Users\user\Desktop\Все\Skypro\diploma-work\src\services).

The app uses a shared pattern:

- API functions display error messages
- User interface components display error messages encountered by the user

This is applied to:

- catalog loading
- auth flows
- add/remove course actions
- workout loading
- workout progress loading and saving


