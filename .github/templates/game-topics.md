# Game Repository Topics Template

Use up to 20 GitHub topics per README lander repo. Topics should be lowercase, hyphenated keyword variants built from the game's primary search slug.

## Variables

- `{slug}`: the primary keyword slug for the game, for example `doodle-jump`.
- `{repo}`: the GitHub repo name, usually `{slug}-game`.

## Default Topics

Use this exact order and keep the list at GitHub's topic limit:

```txt
{slug}
{slug}-game
{slug}-unblocked
{slug}-online
{slug}-free
play-{slug}
play-{slug}-game
play-{slug}-online
play-{slug}-game-online
{slug}-game-online
{slug}-online-game
{slug}-free-online
{slug}-online-free
{slug}-free-unblocked
{slug}-unblocked-game
{slug}-browser-game
{slug}-html5-game
{slug}-no-download
free-{slug}-game
online-{slug}-game
```

## Alias Handling

If the repo slug and play-page slug differ, include the most recognizable alias by replacing the lowest-value tail terms first. Example: `badicecream-2` may also include `bad-ice-cream-2` and `bad-ice-cream-2-game`.