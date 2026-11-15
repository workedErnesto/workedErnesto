# profile assets

Self-contained animated terminal headers, project cards and local badges. The terminal is an illustrative profile introduction. It uses CSS keyframes without scripts or external fonts and respects `prefers-reduced-motion`.

Project cards have uniform 24px internal padding and carry architecture descriptions. Their layout does not depend on custom README styles, which GitHub removes.

Each card exists as a `-light` and a `-dark` file. The README shows both with the `#gh-light-mode-only` and `#gh-dark-mode-only` fragments, so GitHub picks the one for the theme selected on the site. A `prefers-color-scheme` rule inside an image follows the operating system instead and gave light cards on the dark theme. The files carry a transparent right and bottom margin that sets the gap between the cards: first-row cards are 16 units apart horizontally and 8 units plus the line box below, so the gaps look equal.

Brand icons: [Simple Icons](https://github.com/simple-icons/simple-icons), CC0, and [Devicon](https://github.com/devicons/devicon), MIT. License texts are in `licenses`. Trademarks belong to their owners. Framework packages use their ecosystem icon; server, search, code and email symbols are custom line icons.
