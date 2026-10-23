# Third-party skills

The `li-*` skills in this folder come from
[Jakeschincariol/linkedin-agent-skill](https://github.com/Jakeschincariol/linkedin-agent-skill)
(commit `add2c23882fe79180737d242ff80a5da205eda6a`), by Jake Schincariol,
under the MIT License. See `LICENSE-linkedin-agent-skill`.

They were copied unmodified. Before adding them, we read every file: the two
Python scripts in `li-human/` use only the standard library and make no network
calls, and none of the skills post to LinkedIn. They store data only under
`~/.claude/linkedin/`.
