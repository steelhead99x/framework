# Hatchary overlay on FreePBX framework

This is a GitHub fork of FreePBX/framework for Hatchary.

```
origin    git@github.com:steelhead99x/framework.git
upstream  https://github.com/FreePBX/framework.git
```

```
git remote add upstream https://github.com/FreePBX/framework.git
git fetch upstream
git checkout -b hatchary release/17.0
git merge --no-ff upstream/release/17.0
```

Keep Hatchary patches small. Do not vendor this tree into steelhead99x/hatchery compose until the image builds from here.
Sangoma trademark stays theirs. Product humans see is Hatchary.
