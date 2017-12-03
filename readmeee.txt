Readme:

1. In layouts/index.html kann ich partials definieren die geladen werden sollen (und vermutlich einfach in jedem html file. D.h. ich muss mein partial irgendwo in das fertige layout von docDock einarbeiten.
2. In layouts/partials/testDoc.html kann ich dann mit Go programmieren was alles wie angezeigt werden soll. Das html benutzt dann den Style css von dem jeweiligen Theme was ich gerade benutze. Hier kann ich Variablen als parameter verwenden und meine Doku draus aufbauen.
3. In content/_index.md oder in anderen markdown files kann ich im frontmatter die variablen definieren. Geht vllt auch einfacher mit yaml, dann kann man sich die "---" sparen.