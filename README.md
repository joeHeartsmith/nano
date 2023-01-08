# nano
[PATCH] Extra row in the help bar for high res X display windows

This is a patch submission for [nano](https://savannah.gnu.org/patch/?10303).  For small projects not requiring a pull request, or where maintainers prefer e-mail patch submissions, I keep copies here for reference/download.

- File: ./src/global.c, ./src/nano.c, ./src/winio.c
- Submission Date: 2022-01-07
- Commit Date: N/A

Summary: When using nano on a high-resolution X display, there can be room for the help bar to be expanded an additional row.  If the window has more than 160 columns, this patch will enable nano to add a third line of shortcuts.
