# <img src="https://user-images.githubusercontent.com/538321/217246909-b6d4db57-d50d-45db-a623-ccac79cdfc3f.png" style="height:32px; vertical-align:text-bottom;"/> CKEditor 5


The most powerful Open Source rich text editor with a modular & modern architecture, 200+ features, and built-in AI. Rock solid and fully customizable.

- [Features documentation](https://ckeditor.com/docs/ckeditor5/latest/features/index.html)
- [Online demos](https://ckeditor.com/ckeditor-5/demo/)
- [Main repository](https://github.com/ckeditor/ckeditor5)

<img src="https://github.com/ckeditor/.github/assets/538321/e12136fa-1690-414c-96a1-4b9377724c74" style="align:center">

## What's so unique about CKEditor? 💫
 - CKEditor 5 is a **ready-to-use editor** but also an **[editing framework](https://ckeditor.com/docs/ckeditor5/latest/framework/index.html)** with a **[robust API](https://ckeditor.com/docs/ckeditor5/latest/api/index.html)** and tools such as **[CKEditor 5 inspector](https://ckeditor.com/docs/ckeditor5/latest/framework/develpment-tools/inspector.html)** or **[package generator](https://ckeditor.com/docs/ckeditor5/latest/framework/develpment-tools/package-generator/using-package-generator.html)**. This allows you to build **[your own plugins and solutions](https://github.com/ckeditor/ckeditor5-tutorials-examples)**.
 - **Quality**. 32,000+ tests, 100% code coverage, backed by a team of 40+ developers.
 - Six different **[UI types](https://ckeditor.com/ckeditor-5/demo/editor-types/)**. It fits any kind of application, e.g. Document Management System, email platform, CMS, LMS, CRM, chat.
 - **A large set of [features](https://ckeditor.com/docs/ckeditor5/latest/features/index.html) (~200)**, including: paste from Office (Word, Google Docs), Markdown support, support for tables with table properties and column resizing, @mentions, find & replace, autoformatting, source editing, spell  and grammar checker.
 - Great **accessibility** support.
 - **[Export to PDF/Word](https://ckeditor.com/export-to-pdf-word/)** and **[import from Word](https://ckeditor.com/import-from-word/)**.
 - **[Exceptional collaboration features](https://ckeditor.com/ckeditor-5/capabilities/collaboration-features/)** you will not find anywhere else:
   - Real-time collaborative editing (with ready-to-use backend with REST API, webhooks and detailed logging),
   - Comments and track changes,
   - Revision history.
 - **[CKEditor AI](https://ckeditor.com/ckeditor-5/capabilities/ai-features/)** — generate, transform, review and translate content with in-editor assistants or directly from your own code.

CKEditor 5 is open source under the GPL license. Several of the features above — CKEditor AI, real-time collaboration, comments, track changes, revision history, and document import/export — are [premium features](https://ckeditor.com/docs/ckeditor5/latest/features/index.html#premium-features) available under a [commercial license](https://ckeditor.com/legal/ckeditor-licensing-options/). You can [try the premium features for free](https://portal.ckeditor.com/checkout?plan=free) or review the [pricing](https://ckeditor.com/pricing/).

## AI-powered editing 🤖

[CKEditor AI](https://ckeditor.com/ckeditor-5/capabilities/ai-features/) brings generative AI directly into the editor as a set of configurable, in-editor features:

 - **AI Chat** — a conversational assistant inside the editor, with multi-turn conversations, chat history, web search, and context pulled from URLs, uploaded files, or external systems through the Model Context Protocol (MCP).
 - **AI Quick Actions** — one-click transformations on selected text: rewrite, fix grammar and spelling, change tone, adjust length, summarize, continue writing, convert to bullet points, and translate.
 - **AI Review** — proofreading and clarity, style, and tone checks against your own company style guide, with suggestions shown in context.
 - **AI Translate** — full-document translation with a side-by-side review-and-accept workflow.
 - **Programmatic APIs** — drive AI from your own code instead of the UI: trigger AI Chat and Quick Actions through the editor API, run stateless content transforms over a REST actions endpoint (responses streamed via Server-Sent Events), and transform whole HTML documents through a document-processing endpoint for server-side and batch workflows.

CKEditor AI works with Claude, Gemini and GPT models — or your own custom LLM — and supports on-premises deployment. Try the [interactive demo](https://ckeditor.com/ckeditor-5/demo/ai/) or the [programmatic demo](https://ckeditor.com/ckeditor-5/demo/ai-programmatic/).

## Download and install CKEditor 5 ⛏️

- [CKEditor 5 Builder](https://ckeditor.com/ckeditor-5/builder/) - Scaffold a customized editor: choose an editor type, add the features you need, and download a ready-to-use setup.
- [CDN Quick start guide](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/cloud/quick-start.html)
- [npm or ZIP Quick start guide](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/quick-start.html)
- [Getting started](https://ckeditor.com/docs/ckeditor5/latest/getting-started/index.html) - Full introduction to CKEditor 5

## Framework integrations 🧩

- [React](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/react/react.html) | https://github.com/ckeditor/ckeditor5-react | [Quick start + Live demo](https://ckeditor.com/ckeditor-5/react/)
- [Next.js](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/self-hosted/next-js.html) - Integrates through the official React component.
- [Vue 3](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/vuejs-v3.html) | https://github.com/ckeditor/ckeditor5-vue | [Quick start + Live demo](https://ckeditor.com/ckeditor-5/vue/#code-example)
- [Vue 2](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/vuejs-v2.html) | https://github.com/ckeditor/ckeditor5-vue2
- [Angular](https://ckeditor.com/docs/ckeditor5/latest/getting-started/installation/angular.html) | https://github.com/ckeditor/ckeditor5-angular

## Ready-to-use samples 📋

- https://github.com/ckeditor/ckeditor5-demos - Code examples for CKEditor setups available on [demo pages](https://ckeditor.com/ckeditor-5/demo/)
- https://github.com/ckeditor/ckeditor5-tutorials-examples - Code samples from tutorials on how to create plugins
- https://github.com/ckeditor/ckeditor5-collaboration-samples - A large set of examples on integrating CKEditor 5 with collaboration features

## Tutorials 📚

- [Getting and setting data](https://ckeditor.com/docs/ckeditor5/latest/getting-started/setup/getting-and-setting-data.html)
- [Creating a basic plugin](https://ckeditor.com/docs/ckeditor5/latest/framework/tutorials/creating-simple-plugin-timestamp.html)
- [Implementing a block widget](https://ckeditor.com/docs/ckeditor5/latest/framework/tutorials/widgets/implementing-a-block-widget.html)
- [Implementing an inline widget](https://ckeditor.com/docs/ckeditor5/latest/framework/tutorials/widgets/implementing-an-inline-widget.html)
- [Using a React component in a widget](https://ckeditor.com/docs/ckeditor5/latest/framework/tutorials/widgets/using-react-in-a-widget.html)

## Other resources 🧰

- [CKEditor GitHub Awesome List](https://github.com/ckeditor/awesome-ckeditor/) - A curated list of awesome projects and resources related to CKEditor 5.
- [CKBox](https://ckeditor.com/ckbox/) - Ready-to-use file manager / digital asset manager with a native plugin for CKEditor 5.

## License 📄

CKEditor 5 is available under a dual-license model. You can use it for free under the terms of the [GNU General Public License Version 2 or later](https://www.gnu.org/licenses/gpl.html), or obtain a [commercial license](https://ckeditor.com/legal/ckeditor-licensing-options/) from CKSource Holding sp. z o.o. Premium features, such as CKEditor AI and real-time collaboration, require a commercial license.

# <img src="https://user-images.githubusercontent.com/538321/217248816-e1be1e91-021f-4fce-bf1f-7d05b1946312.png" style="height:32px; vertical-align:text-bottom;"/> CKEditor 4


Note: CKEditor 4 reached its [end of life](https://ckeditor.com/blog/ckeditor-4-end-of-life/) on June 30, 2023, and the open source version is no longer maintained. We recommend starting new projects with CKEditor 5. Existing CKEditor 4 deployments can receive continued security updates and critical bug fixes through the commercial [Extended Support Model](https://ckeditor.com/docs/ckeditor4/latest/support/licensing/extended-support-model.html).

* https://github.com/ckeditor/ckeditor4 - The main repository of CKEditor 4
* https://github.com/ckeditor/ckeditor4-releases - Official distribution releases of CKEditor 4
* https://github.com/ckeditor/ckeditor4-react - React integration for CKEditor 4
* https://github.com/ckeditor/ckeditor4-angular - Angular integration for CKEditor 4
* https://github.com/ckeditor/ckeditor4-vue - Vue integration for CKEditor 4
