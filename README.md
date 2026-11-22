# Kapusta theme for Claude

A theme for the Claude desktop app in the colors of Kapusta. Light mode is the pink "Live No. 1" poster, and dark mode is the cabbage-green t-shirt.

- **Background:** the band logo, a cabbage band playing live (bass, drums, vocals, guitar) on a stage with footlights, sweeping spotlights, a crowd, falling cabbage leaves and rising notes. Everyone moves to one 100 BPM beat.
- **Messages:** your messages are ruffled cabbage-leaf bubbles with a riso-print offset shadow. Claude's replies sit in a leaf-edged box with a small cabbage-on-K stamp.
- **Sound:** recorded from Kapusta's own live mix of Watcha. A beat from the song plays when you send a message, and the "Watcha!" shout plays when Claude finishes an answer (on a Mac). Turn them off with `/kapusta-sound off`, and back on with `/kapusta-sound on`. The speaker button in the session's title bar adds a few synthesized cues on top, for questions and errors.

## Install

At the prompt of a Claude Code terminal session:

```
/plugin install kapusta --marketplace pellerb14/kapusta-claude-theme
```

Answer `y` to add the marketplace, then pick the user scope.

From a shell:

```bash
claude plugin install kapusta --marketplace pellerb14/kapusta-claude-theme
```

In the desktop app, where `/plugin` does not run: click + next to the prompt box, then Plugins, Add marketplace with `pellerb14/kapusta-claude-theme`, then Add plugin.

## Sidebar

The app doesn't tell the background where the sidebar is, so the art assumes it is open. If you keep the sidebar closed, run:

```
/kapusta-sidebar off
```

`/kapusta-sidebar on` switches back, and the command with no argument toggles between the two.
