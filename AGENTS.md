# CapCut skill builder

Use this guide when creating or revising an effect skill in this repository. The goal is an effect that someone else can install, prepare footage for, and preview as an editable CapCut draft.

## Understand the effect

- Watch the reference or inspect the supplied frames before describing the edit. Separate the visual mechanism from the example footage and wording.
- Identify the minimum asset roles. If an asset is missing, show the person what to capture: screen content, camera framing, start and end poses, and the moment of the cut where relevant.
- Keep the instructions specific to this effect. Do not copy constellation-only rules such as star count, shape, or line color into unrelated skills.

## Write the skill

- Put it at `skills/<effect-name>/SKILL.md` with matching lowercase hyphenated `name` and a concise `description` explaining the effect and when to use it.
- Include: required inputs, how to prepare missing assets, the essential CapCut layer or timing mechanics, and effect-specific visual checks. Put substantial optional detail in a linked `references/` file.
- Ask for user-controlled content that changes the result. For text effects, ask for the exact words. Suggest colors after seeing the footage and ask the user to choose; ask about shape or placement only when the effect needs it. Reuse an earlier choice only if the user asks to.
- Before editing, verify a working CapCut editing connection with an account-bound tool, not merely a visible plugin registration. If Codex lacks it, offer to set up the official plugin and guide authorization, then resume the original request. Do not ask again if the user already requested setup. Follow CapCut's [official setup guide](https://sf16-sg.tiktokcdn.com/obj/eden-sg/962370eh7nupenuhbo/capcut_codex_plugin/SKILL.md) when authorized. In Claude Code, require compatible CapCut editing tools and do not imply that the Codex plugin installs there.
- Build an editable draft and let the user watch it. Check important frames at full preview size. Export only when the user asks or has already authorized it. If the connection or source quality prevents the effect, explain the concrete blocker instead of claiming completion.
- Never put personal footage, account data, temporary paths, copied tutorial media, or private screenshots in the public skill repository.

## Keep installation and site pages consistent

- The public effect pages currently support **Codex** and **Claude Code** only. The skill install command is `gh skill install qiqibuilds/capcut-video-skills <effect-name> --agent <codex|claude-code> --scope user`.
- Installing the skill does not install CapCut. For new Codex users, include a separate copyable setup prompt linked to the official guide. State that CapCut editing has been verified in Codex; Claude Code needs a compatible editing connection.
- Add the effect to this repository's README. If the paired website source is available, add a gallery card and a detail page using its `design.md`, with a real effect preview or an honest diagram, an asset list, and both platform commands. Do not add unsupported platform choices or invented metrics.
- Do not assign a license or copy a third-party logo or tutorial asset without checking ownership and the repository's chosen terms.

## Check before publishing

1. Run `gh skill publish --dry-run` on this repository and fix validation errors. Review any warnings.
2. Test installation into an isolated temporary directory with `gh skill install <local-repository> <effect-name> --from-local --dir <temporary-directory>`. After publishing, repeat from the public repository and confirm its `SKILL.md` and linked references are present.
3. Check that the public skill contains no personal paths or private assets. Test the edit with representative footage when tools and assets are available; never treat the syntax check as proof of visual quality.
4. Check the website page in a browser, including the copy buttons and narrow layout, before describing it as ready.
