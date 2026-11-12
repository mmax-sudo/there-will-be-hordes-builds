# There Will Be Hordes — tester builds

Thanks for testing **There Will Be Hordes**: a first-person sword and tower-defence game where you defend your kingdom's last resting place from goblins and orcs for five days and nights. It's an early prototype made of plain blocks, so it's meant to look rough. I want to know whether it's fun.

**Mac only** (Apple chip or Intel).

## Install

### Easiest: one command (no warnings)

1. Open **Terminal**: press **⌘ Space**, type `Terminal`, press **Enter**.
2. Copy this whole line (the copy button is on the right of the box), paste it into Terminal and press **Enter**:

```bash
curl -L https://github.com/mmax-sudo/there-will-be-hordes-builds/releases/latest/download/There-Will-Be-Hordes-Mac.zip -o /tmp/hordes.zip && ditto -x -k /tmp/hordes.zip /Applications && open "/Applications/There Will Be Hordes.app"
```

3. Wait a moment (it's about 65 MB). The game opens by itself.

That's it. From now on, open **There Will Be Hordes** from your Applications folder. You never need to do this again: the game updates itself.

### Without Terminal

1. Download **[There-Will-Be-Hordes-Mac.zip](https://github.com/mmax-sudo/there-will-be-hordes-builds/releases/latest/download/There-Will-Be-Hordes-Mac.zip)** and open it in your Downloads folder.
2. Double-click **There Will Be Hordes**. Your Mac says it "could not verify" the game. That's expected: the game isn't from the App Store. Click **Done**.
3. Open **System Settings → Privacy & Security**, scroll to the bottom and click **Open Anyway** next to "There Will Be Hordes". Enter your Mac password if asked. Do this soon after step 2; the button doesn't stay for long.
4. Double-click the game again and click **Open**.

## Updates

When the game starts, it checks for a newer version, downloads it (a few MB) and starts it, before the main menu. If you're offline, it just starts the version you have.

## Play reports and feedback

- The game asks once whether to send play reports (fight logs, errors and play stats; no voice and no personal info). Please say yes: it shows exactly what went wrong. You can switch it off on the main menu.
- If it asks to record your voice, please say yes and think out loud while you play: what you're trying to do, what's confusing, what's fun, what's annoying.
- When you finish, the end screen has a button that opens your feedback folder. Send me the files in it.

## If something goes wrong

- **Terminal says "Permission denied"** for Applications: run this instead, which puts the game in your own Applications folder:

```bash
mkdir -p ~/Applications && curl -L https://github.com/mmax-sudo/there-will-be-hordes-builds/releases/latest/download/There-Will-Be-Hordes-Mac.zip -o /tmp/hordes.zip && ditto -x -k /tmp/hordes.zip ~/Applications && open ~/Applications/"There Will Be Hordes.app"
```

- **"There Will Be Hordes" can't be opened** after downloading the zip in a browser: use the one-command install above, or the **Open Anyway** steps.
- Anything else: tell me what you saw (a photo of the screen is perfect).

## All builds

Every build is listed under **[Releases](https://github.com/mmax-sudo/there-will-be-hordes-builds/releases)**. The links above always give you the newest one.
