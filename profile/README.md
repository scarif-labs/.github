# Scarif Labs

> You bring the idea. We build it.

We're a small independent studio that designs and builds software for founders and teams, mostly products, AI systems and internal tools. This org holds the work we've made public.

## Horus

[scarif-labs/horus](https://github.com/scarif-labs/horus)

An Android app that runs Claude Code, Codex and OpenCode in an Alpine Linux ARM64 environment on the phone. It doesn't need root or Termux; it bundles its own PRoot runtime, PTY and terminal renderer. If you plug the phone into a computer, the optional `horus` CLI adds SSH, port forwarding and file sync over USB.

It's on [F-Droid](https://f-droid.org/packages/com.scariflabs.horus/), and the docs are at [scariflabs.com/horus/docs](https://scariflabs.com/horus/docs).

## JEV software decision benchmark

[scarif-labs/jev-software-decision-benchmark](https://github.com/scarif-labs/jev-software-decision-benchmark)

We tested JEV, a probabilistic decision model from TypeSafe, on one job: deciding whether a dependency update is safe to auto-merge. On the main 1,102-case set it scored an AUROC of 0.851, ahead of static rules (0.602) and DeepSeek Flash (0.585). On a separately built set of 185 cases from 103 repositories it fell to 0.605, and the threshold we'd fixed beforehand let through 15 bad merges out of 30.

The repo has the data, scripts, methodology and a list of the study's limitations, so you can rerun it yourself.

## Working with us

If you have something you want built, get in touch at [hi@scariflabs.com](mailto:hi@scariflabs.com?subject=Saw%20your%20GitHub&body=Hi%2C%0A%0AI%20came%20across%20your%20GitHub%20and%20wanted%20to%20get%20in%20touch.%0A%0A).

