---
name: "Samuel"
topic: "Making a Cross-Platform Desktop App with Tauri"
slack_username: "polypixeldev"
time_estimate: "30-45 mins"
---

## Workshop name

### Plan

> What do you want to run, and how do you think it'll be like? (can you give us a rough outline?)

> Are there any resources you think you might use? Have you run something like this before, or have an example (even if it's not related 100%)

I would like to run a workshop on using [Tauri](https://tauri.app) to make cross-platform desktop apps.
Tauri uses Rust as a backend to render a webview, which allows it to be used in combination with any web framework.
I'll be using [Vite](https://vitejs.dev) and [React](https://react.dev) for the frontend.

I'll use the example of a simple app I made called [text_ops](https://github.com/polypixeldev/text_ops), but people will be free to make whatever they would like.

I've never run a workshop before.

#### Outline
1. Set up prerequisites: https://tauri.app/v1/guides/getting-started/prerequisites
2. Set up NodeJS: https://nodejs.org/en (official install) or https://github.com/Schniz/fnm (version manager)
3. Scaffold project: `npm create tauri-app@latest` (options: name, frontend lang: ts/js, package manager, ui template: react, ui flavor: typescript)
4. Initialize git repo in project (optional): `git init`
5. Install Tauri CLI: `npm install -D @tauri-apps/cli`
6. Start development app: `npm run tauri dev`
7. Explain how the IPC (inter-process communication) works using starter code and whiteboard
8. Show them [text_ops](https://github.com/polypixeldev/text_ops) as an example and give a few ideas on what you could build.
9. Answer questions and help people build their app!

### Do you think you might need anything?

> Do you need hardware boards, or other supplies like paint that you would need us to purchase or have on hand? We won't have any projectors available.

Just a whiteboard and marker

### People involved

> List all the people who are running this workshop if it's more than 1!

Just me
