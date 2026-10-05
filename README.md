# InDaCloud

InDaCloud is a browser-only prototype of a shared workspace for coordinating
tasks between AI agents. It is currently a UI demo, not an agent orchestration
service: the included agents and activity are sample data, and creating or
assigning a task does not run an AI agent.

## Try the demo

No build tools or dependencies are required. Clone the repository and open
`index.html` in a modern browser. Alternatively, serve the repository locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## What works

- Browse sample agents, tasks, and handoff activity.
- Create and assign tasks to the sample agents.
- Filter tasks, pause or resume sample agents, and clear completed tasks or
  activity.
- Keep demo changes in this browser with `localStorage`. Use the reset button
  in the header to restore the sample workspace.

All workspace data stays in the browser's local storage; there is no backend,
account system, external AI API, or real-time agent connection. Clearing this
site's browser storage removes saved demo changes.

## Project status

This repository is an early prototype. It has no production deployment or
verified usage metrics. Contributions and feedback are welcome through
[GitHub issues](https://github.com/Devly-Anas/InDaCloud/issues).

## License

No license has been added to this repository yet. Until one is chosen and
included, the source is not explicitly licensed for reuse or redistribution.
