### Fixed
- Markdown previews and chat messages read a link with a title (`[docs](https://x.dev "Docs")`),
  which shows when the pointer rests on it, and reference-style links (`[docs][1]` with
  `[1]: https://x.dev` on a line of its own), whose definitions no longer show as text. A
  definition that nothing refers to still shows as written, so a list of sources keeps its
  addresses.
