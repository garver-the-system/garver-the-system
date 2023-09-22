# Garver the System

Alexander Garver, a Systems/Software engineer looking to make lives better.

My projects are hosted on GitLab. I keep this profile around for contributing to other projects and
because it's more well-recognized.

## Projects

### Kitchen Server

[![Latest Release](https://gitlab.com/kitchen-server/kitchen-server/-/badges/release.svg)](https://gitlab.com/kitchen-server/kitchen-server/-/releases)
[![pipeline status](https://gitlab.com/kitchen-server/kitchen-server/badges/main/pipeline.svg)](https://gitlab.com/kitchen-server/kitchen-server/-/commits/main)

My primary project, a homelab server that stores recipes and serves them as webpages over the local
network.

Originally written in Python, I changed it to Rust for type-safety and the trait system among other
things. It's now built on the [Poem](https://github.com/poem-web/poem) framework. 

I've fleshed out a CI system, and I'm probably more proud of it than I should be. Branch testing
and semantic-version releases have manual triggers to kick off testing and deployment, but merge
requests and `latest` releases happen automatically.

### Tagalyzer


[![Latest Release](https://gitlab.com/garver-the-system/tagalyzer/-/badges/release.svg)](https://gitlab.com/garver-the-system/tagalyzer/-/releases)
[![pipeline status](https://gitlab.com/garver-the-system/tagalyzer/badges/main/pipeline.svg)](https://gitlab.com/garver-the-system/tagalyzer/-/commits/main)

Tagalyzer is a text-processing library and CLI that will find statistics on how frequently words
appear in files relative to one another. The intention is to help analyze the frequency of words in
my blog posts to help me decide how to tag it. As of now, it's far from being feature complete,
which is why its semantic verison is so low.

As my first library project, I'm designing it from the ground up
with maintainability and automation in mind -
[0.0.2](https://gitlab.com/garver-the-system/tagalyzer/-/releases/0.0.2) added linting, testing,
and deployment in CI.

### The Garver Toolbox

This is (theoretically) a collection of Bash utilities I don't want to leave behind every time I
install a new flavor of Linux, set up a Raspberry Pi, or switch to my Mac.

At the moment, it's fairly neglected as I've been focusing work on other projects (primarily
[Kitchen Server](#kitchen-server) and my job search). I do intend to pick it back up eventually,
but for now it's not a priority.

## Find Me Online

[My Website](https://garverthesystem.com/)

I work mostly on [GitLab](https://gitlab.com/garver-the-system).


<!--
**garver-the-system/garver-the-system** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
