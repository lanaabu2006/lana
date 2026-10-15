# lana

A Claude Code plugin with one skill: turn a paper into five bullets (title, question, method, result, limitation).

## Install

This folder is both the plugin and its marketplace (`lanaabu2006-skills`).

From a local copy of this folder, run these inside Claude Code:

```
/plugin marketplace add ./lana
/plugin install lana@lanaabu2006-skills
```

From GitHub, once this folder is the root of a repository:

```
/plugin marketplace add lanaabu2006/<repository-name>
/plugin install lana@lanaabu2006-skills
```

Restart Claude Code (or run `/reload-plugins`) after installing.

## Use

Ask Claude to summarise a paper, or call the skill directly:

```
/lana:lana papers/some-paper.txt
```

You get exactly five one-sentence bullets. Anything the paper does not state is marked "Not stated in the paper".

## Uninstall

```
/plugin uninstall lana@lanaabu2006-skills
/plugin marketplace remove lanaabu2006-skills
```
