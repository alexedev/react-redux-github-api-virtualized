# Infinite GitHub users in React + Redux
### Job test application

Used:
- React (react-create-app generator)
- Redux
- react-virtualized (for list with infinite scrolling)

Users from GitHub API are fetched by 10 at once, next ones are fetched on scrolling.
On first load a list with first 10 users is shown, on scroll a redux-thunk loadNextPage for fetching is called,
as a result also isNextPageLoading field is updated (checking prevents additional triggering of loadNextPage).

Timing

- 10:00 - start of work
- 10:20 - pause (need to start my normal full-time work)

