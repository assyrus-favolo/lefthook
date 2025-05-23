[Introduction](./intro.md)

# User guide

- [Installation](./installation/README.md)
  - [Ruby](./installation/ruby.md)
  - [Node.js](./installation/node.md)
  - [Swift](./installation/swift.md)
  - [Go](./installation/go.md)
  - [Python](./installation/python.md)
  - [Scoop](./installation/scoop.md)
  - [Homebrew](./installation/homebrew.md)
  - [Winget](./installation/winget.md)
  - [Snap](./installation/snap.md)
  - [Debian-based distro](./installation/deb.md)
  - [RPM-based distro](./installation/rpm.md)
  - [Alpine](./installation/alpine.md)
  - [Arch Linux](./installation/arch.md)
  - [Mise](./installation/mise.md)
  - [Manual](./installation/manual.md)
- [Usage](./usage/README.md)
  - [Commands](./usage/commands.md)
  - [ENV variables](./usage/env.md)
  - [Tips](./usage/tips.md)

# Reference guide

- [Configuration](./configuration/README.md)
  - [`assert_lefthook_installed`](./configuration/assert_lefthook_installed.md)
  - [`colors`](./configuration/colors.md)
  - [`extends`](./configuration/extends.md)
  - [`lefthook`](./configuration/lefthook.md)
  - [`min_version`](./configuration/min_version.md)
  - [`no_tty`](./configuration/no_tty.md)
  - [`output`](./configuration/output.md)
  - [`rc`](./configuration/rc.md)
  - [`remotes`](./configuration/remotes.md)
    - [`git_url`](./configuration/git_url.md)
    - [`ref`](./configuration/ref.md)
    - [`refetch`](./configuration/refetch.md)
    - [`refetch_frequency`](./configuration/refetch_frequency.md)
    - [`configs`](./configuration/configs.md)
  - [`skip_output`](./configuration/skip_output.md)
  - [`source_dir`](./configuration/source_dir.md)
  - [`source_dir_local`](./configuration/source_dir_local.md)
  - [`skip_lfs`](./configuration/skip_lfs.md)
  - [`templates`](./configuration/templates.md)
  - [{Git hook name}](./configuration/Hook.md)
    - [`files`](./configuration/files-global.md)
    - [`parallel`](./configuration/parallel.md)
    - [`piped`](./configuration/piped.md)
    - [`follow`](./configuration/follow.md)
    - [`exclude_tags`](./configuration/exclude_tags.md)
    - [`skip`](./configuration/skip.md)
    - [`only`](./configuration/only.md)
    - [`jobs`](./configuration/jobs.md)
      - [`name`](./configuration/name.md)
      - [`run`](./configuration/run.md)
      - [`script`](./configuration/script.md)
      - [`runner`](./configuration/runner.md)
      - [`group`](./configuration/group.md)
        - [`parallel`](./configuration/parallel.md)
        - [`piped`](./configuration/piped.md)
        - [`jobs`](./configuration/jobs.md)
      - [`skip`](./configuration/skip.md)
      - [`only`](./configuration/only.md)
      - [`tags`](./configuration/tags.md)
      - [`glob`](./configuration/glob.md)
      - [`files`](./configuration/files.md)
      - [`file_types`](./configuration/file_types.md)
      - [`env`](./configuration/env.md)
      - [`root`](./configuration/root.md)
      - [`exclude`](./configuration/exclude.md)
      - [`fail_text`](./configuration/fail_text.md)
      - [`stage_fixed`](./configuration/stage_fixed.md)
      - [`interactive`](./configuration/interactive.md)
      - [`use_stdin`](./configuration/use_stdin.md)
    - [`commands`](./configuration/Commands.md)
      - [`run`](./configuration/run.md)
      - [`skip`](./configuration/skip.md)
      - [`only`](./configuration/only.md)
      - [`tags`](./configuration/tags.md)
      - [`glob`](./configuration/glob.md)
      - [`files`](./configuration/files.md)
      - [`file_types`](./configuration/file_types.md)
      - [`env`](./configuration/env.md)
      - [`root`](./configuration/root.md)
      - [`exclude`](./configuration/exclude.md)
      - [`fail_text`](./configuration/fail_text.md)
      - [`stage_fixed`](./configuration/stage_fixed.md)
      - [`interactive`](./configuration/interactive.md)
      - [`use_stdin`](./configuration/use_stdin.md)
      - [`priority`](./configuration/priority.md)
    - [`scripts`](./configuration/Scripts.md)
      - [`runner`](./configuration/runner.md)
      - [`skip`](./configuration/skip.md)
      - [`only`](./configuration/only.md)
      - [`tags`](./configuration/tags.md)
      - [`env`](./configuration/env.md)
      - [`fail_text`](./configuration/fail_text.md)
      - [`stage_fixed`](./configuration/stage_fixed.md)
      - [`interactive`](./configuration/interactive.md)
      - [`use_stdin`](./configuration/use_stdin.md)
      - [`priority`](./configuration/priority.md)
- [Examples](./examples/README.md)
  - [lefthook-local.yml](./examples/lefthook-local.md)
  - [Apply fixes on pre-commit hook](./examples/stage_fixed.md)
  - [Filter files](./examples/filters.md)
  - [Skip or run on condition](./examples/skip.md)
  - [Use remote config](./examples/remotes.md)
  - [Use commitlint](./examples/commitlint.md)

---

[Contributors](./misc/contributors.md)
