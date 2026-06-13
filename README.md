<div align="center">

<pre>
╭─────────────────────────────────────────────╮
│                                             │
│   $ whoami                                  │
│   user                                │
│                                             │
│   $ cat ~/.about                            │
│   nixos. low-level tinkering.               │
│   the occasional web thing.                 │
│                                             │
│   $ ls ~/links                              │
│   user.codeberg.page                  │
│                                             │
╰─────────────────────────────────────────────╯
</pre>

<!-- AUTO-GENERATED:START (do not edit by hand) -->
<p><a href="https://user.codeberg.page/md.html?file=projects/PROFILE.md">latest project writeup</a> · <a href="https://user.codeberg.page/md.html?file=logbook/2026-04-14.md">latest logbook entry</a></p>

<p>total project writeups: 5 · total logbook entries: 3</p>

<p><sub>auto-updated from my <a href="https://codeberg.org/user/pages">pages repo</a>.</sub></p>
<!-- AUTO-GENERATED:END -->

</div>

<br>

### `~/` full disclosure: my ai policy

> i use ai as a writing assistant while coding; i do use claude code and such, but i try to do it sparingly and actually learn. i don't consider myself a "vibe coder" and i take full responsibility for all code shared. none of my pull requests or issues will ever be ai slop; i genuinely only contribute stuff i did or found myself, to projects i actually care about.
>
> none of my actual writing is written with ai. at worst, some readmes are there as placeholders, but when they are, it'll be blatantly obvious.

<br>

<div align="center">

### `~/projects` what i build

<sub>grouped roughly. all repos live on both codeberg and github.</sub>

</div>

<br>

<table>
<tr><th colspan="2" align="left"><code>// systems and infra</code></th></tr>
<tr>
  <td valign="top" width="220"><strong>nix-config</strong></td>
  <td>declarative multi-host nixos flake for my desktop, laptop, and homeserver.</td>
</tr>
<tr>
  <td valign="top"><strong>e-waste homeserver</strong></td>
  <td>a 2013 laptop repurposed into a small nixos homeserver for self-hosting docker containers (navidrome, filebrowser, searxng, vaultwarden), backups. "powered" by nix-config.</td>
</tr>
<tr>
  <td valign="top"><strong>libreboot-nidhoggr</strong></td>
  <td>personal libreboot patch set for the thinkpad t480; enables smt, natacpi battery thresholds, fn/ctrl swap at ec level, and a grub+seabios dual payload.</td>
</tr>

<tr><td colspan="2">&nbsp;</td></tr>
<tr><th colspan="2" align="left"><code>// tools and apis</code></th></tr>
<tr>
  <td valign="top" width="220"><strong>pswdgen-api</strong></td>
  <td>dockerized ssh and password generator api with a github actions ci/cd pipeline.</td>
</tr>
<tr>
  <td valign="top"><strong>vibe-oopsie</strong></td>
  <td>scans git history (including dangling commits) for leaked secrets.</td>
</tr>
<tr>
  <td valign="top"><strong>kebab-folders</strong></td>
  <td>cli to preview and convert folder names to kebab-case.</td>
</tr>

<tr><td colspan="2">&nbsp;</td></tr>
<tr><th colspan="2" align="left"><code>// toys and visualizers</code></th></tr>
<tr>
  <td valign="top" width="220"><strong>heart-cli</strong></td>
  <td>cli gift: <code>heartfetch</code> is a neofetch rewrite that prints a spinning 3d heart as the logo; <code>sandboxheart</code> is a mini sandbox.</td>
</tr>
<tr>
  <td valign="top"><strong>uardal</strong></td>
  <td>romanian wordle-style game that picks a random word each visit.</td>
</tr>
<tr>
  <td valign="top"><strong>sortvisualizer</strong></td>
  <td>quicksort visualizer on html canvas with in-place line swaps.</td>
</tr>
<tr>
  <td valign="top"><strong>mandelbrot</strong></td>
  <td>mandelbrot set visualizer with a webassembly-accelerated core.</td>
</tr>
</table>

<br>

<div align="center">
<sub><code>$ exit 0</code></sub>
</div>
