# Prototype Prompt Builder

The Prototype Prompt Builder helps turn UX research and wireframes into a clear prompt for an AI prototyping platform. Use the generated prompt to create a clickable prototype, then put it in front of real users to test a focused user journey.

The builder is tuned for **Google Stitch** and **Lovable**, and also supports similar tools such as Bolt.new, v0 and Figma Make. It helps structure your instructions; it does not do the UX research or design thinking for you. Start with research, a persona, a journey map, a user story and wireframes so the prototype reflects a real user need.

## Use the builder

Open [Prototype Prompt Builder](https://martinsolent.github.io/basic_prompting/) in a modern browser. There is no installation, build step or server-side component.

Fill in the six steps:

1. **Platform** — choose Stitch, Lovable or another tool.
2. **Product** — describe the product, its target users and key user story.
3. **Screens** — list the screens and their contents in user-flow order.
4. **Test task** — describe what a tester should accomplish and which interactions must work.
5. **Look and feel** — set a design system, mood, colours and theme.
6. **Testing and accessibility** — choose requirements such as realistic sample data, accessible contrast, large touch targets, clear labels and visible feedback.

The prompt updates as you enter information. Choose **One prompt** for a single instruction or **Screen by screen** for a sequence of smaller prompts, then copy and paste the output into your chosen platform. You can also use voice dictation where supported by your browser.

## Guides

- [How to use the builder](how-to-use.html) explains the form fields, design-system choices and prompt workflow.
- [Step-by-step tutorial](tutorial.html) walks through an example from research to testing.
- [Markdown tutorial](tutorial/prototype-prompt-tutorial.md) is the text version of the tutorial.

## Privacy and saving

The builder runs in your browser and does not send the form contents to an app backend. It does **not** save your work automatically, so copy your prompt somewhere safe before closing or refreshing the page. The theme preference is stored in browser local storage. Dictation uses your browser's speech-recognition support, which may have its own browser or network requirements.
