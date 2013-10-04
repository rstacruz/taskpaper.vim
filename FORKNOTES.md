Changes:

 * Adds conceal characters to `@done`.
 * Makes `@done` and `@cancelled` styleable using taskpaperDoneTag and 
 taskpaperCancelledTag.

Recommended settings
--------------------

    au Filetype taskpaper hi Title ctermfg=4
    au Filetype taskpaper hi taskpaperDoneTag ctermfg=Green ctermbg=none guifg=Green
    au Filetype taskpaper hi taskpaperCancelledTag ctermfg=Red ctermbg=none guifg=Red
    au Filetype taskpaper hi Conceal ctermfg=Green ctermbg=none guifg=Green
