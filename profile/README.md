<p align="center"><img src="lispm-lambda-rainbow.png" alt="LispM logo" width="120" /></p>

<h3 align="center">LispM — a Lisp Machine for agents</h3>

The Lisp Machine was an environment where everything was a live Lisp object, and the editor and the system were one. Back then its inhabitants were programs; LispM makes room in it for agents. They run inside Emacs rather than beside it: their conversations are org documents that are also their context, their tools are Elisp functions, their approvals org TODO states, and their memory org files under git.

LispM is three projects:

- **[lispm-agent](https://github.com/LispMachineLab/lispm-agent)**, LispM Agent: AI agents that run inside Emacs, their conversations org documents, their tools Elisp.
- **[lispm-desktop](https://github.com/LispMachineLab/lispm-desktop)**, LispM Desktop: Emacs laid out as Mac OS 9's desktop, a workspace for agents, ready from the first start.
- **[lispm-browser](https://github.com/LispMachineLab/lispm-browser)**, LispM Browser: a WebKit browser in Emacs, with tabs, keyboard hints and Chrome extensions.

Each stands on its own. LispM Desktop brings them together, the agents in its sidebar and the browser as one of its applications.

**Get LispM for Mac.** LispM.app is LispM Desktop with Emacs inside it: you need not know Emacs to begin. On macOS 11 or later, open Terminal and paste:

```sh
curl -fsSL https://lispmachinelab.github.io/install.sh | sh
```

LispM opens a few minutes later, and stays in Applications; run the line again to update ([what it does](https://github.com/LispMachineLab/lispm-desktop/blob/main/install.sh)).

**Already use Emacs?** Run LispM Desktop in your own Emacs 30.1 or later, which installs the other two at its first start:

```sh
git clone https://github.com/LispMachineLab/lispm-desktop ~/lispm-desktop
emacs --init-directory ~/lispm-desktop
```

All three are free software, under the GNU GPL, version 3 or later.
