# Nebraska volleyball, rally by rally

An unofficial, fan-built analysis of Nebraska volleyball's official box scores and play-by-play.
Not affiliated with the University of Nebraska-Lincoln or Nebraska Athletics.

Built by one fan with help from an AI model (Anthropic's Claude), which wrote much of the code and
the prose. The numbers are not written by the model: code computes them from the box scores and
play-by-play, and automated checks stop the build if they do not add up.

## Contributors

- **RobotWhiteBread**: the idea, the questions, the source rules, every decision about what
  counts, and the checking.
- **Claude**, an AI model by Anthropic: most of the code that parses, checks and analyses the
  record, and much of the writing. Commits it helped write carry a `Co-Authored-By` line.

This repository holds the published page only (`index.html`). It is generated from a private
analysis pipeline; no box score, play-by-play log or data file is redistributed here. Every number
on the page carries its count, and every rate its interval.

Built 2026-11-26 from 86,174 rallies of 26 seasons (2001-2026).
