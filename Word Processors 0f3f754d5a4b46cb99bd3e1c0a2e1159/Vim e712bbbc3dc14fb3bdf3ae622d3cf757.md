# Vim

URL: https://en.wikipedia.org/wiki/Vim_(text_editor)

![600px-Vim-%28logiciel%29-console.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/600px-Vim-28logiciel29-console.png)

**Vim** ([/vɪm/](https://en.wikipedia.org/wiki/Help:IPA/English);[[2]](https://en.wikipedia.org/wiki/Vim_(text_editor)) a contraction of **Vi IMproved**) is a clone, with additions, of [Bill Joy](https://en.wikipedia.org/wiki/Bill_Joy)'s [vi](https://en.wikipedia.org/wiki/Vi) [text editor](https://en.wikipedia.org/wiki/Text_editor) program for Unix. Vim's author, [Bram Moolenaar](https://en.wikipedia.org/wiki/Bram_Moolenaar), based it on the [source code](https://en.wikipedia.org/wiki/Source_code) for a port of the [Stevie editor](https://en.wikipedia.org/wiki/Stevie_(text_editor)) to the [Amiga](https://en.wikipedia.org/wiki/Amiga)[[3]](https://en.wikipedia.org/wiki/Vim_(text_editor)) and released a version to the public in 1991. Vim is designed for use both from a [command-line interface](https://en.wikipedia.org/wiki/Command-line_interface) and as a standalone application in a [graphical user interface](https://en.wikipedia.org/wiki/Graphical_user_interface). Vim is [free and open-source software](https://en.wikipedia.org/wiki/Free_and_open-source_software) and is released under a license that includes some [charityware](https://en.wikipedia.org/wiki/Careware) clauses, encouraging users who enjoy the software to consider donating to children in [Uganda](https://en.wikipedia.org/wiki/Uganda).[[4]](https://en.wikipedia.org/wiki/Vim_(text_editor)) The license is compatible with the [GNU General Public License](https://en.wikipedia.org/wiki/GNU_General_Public_License) through a special clause allowing distribution of modified copies "under the [GNU](https://en.wikipedia.org/wiki/GNU) GPL version 2 or any later version".[[5]](https://en.wikipedia.org/wiki/Vim_(text_editor))

Since its release for the Amiga, [cross-platform](https://en.wikipedia.org/wiki/Cross-platform) development has made it available on [many other systems](https://en.wikipedia.org/wiki/Vim_(text_editor)). In 2006, it was voted the most popular editor amongst [Linux Journal](https://en.wikipedia.org/wiki/Linux_Journal) readers;[[6]](https://en.wikipedia.org/wiki/Vim_(text_editor)) in 2015 the [Stack Overflow](https://en.wikipedia.org/wiki/Stack_Overflow) developer survey found it to be the third most popular text editor,[[7]](https://en.wikipedia.org/wiki/Vim_(text_editor)) and the fifth most popular development environment in 2019.[[8]](https://en.wikipedia.org/wiki/Vim_(text_editor))

## History[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=1)]

Vim's forerunner, [Stevie (ST Editor for VI Enthusiasts)](https://en.wikipedia.org/wiki/Stevie_(text_editor)), was created by Tim Thompson for the [Atari ST](https://en.wikipedia.org/wiki/Atari_ST) in 1987[[9][10]](https://en.wikipedia.org/wiki/Vim_(text_editor)) and further developed by Tony Andrews[[9][11]](https://en.wikipedia.org/wiki/Vim_(text_editor)) and G.R. (Fred) Walter.[[12][13]](https://en.wikipedia.org/wiki/Vim_(text_editor))

Basing his work on Stevie, [Bram Moolenaar](https://en.wikipedia.org/wiki/Bram_Moolenaar) began working on Vim for the [Amiga](https://en.wikipedia.org/wiki/Amiga) computer in 1988, with the first public release (Vim v1.14) in 1991.[[14][15]](https://en.wikipedia.org/wiki/Vim_(text_editor))[[better source needed](https://en.wikipedia.org/wiki/Wikipedia:NOTRS)]

At the time of its first release, the name "Vim" was an acronym for "Vi IMitation", but this changed to "'Vi IMproved" late in 1993.[[16]](https://en.wikipedia.org/wiki/Vim_(text_editor))

[Untitled](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/Untitled%20Database%20cf3aa6324f6c4ee2b7884c8ce3063be8.md)

## Interface[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=2)]

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/200px-Vim.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/200px-Vim.png)

Graphical Vim (gVim) under [GTK+ 2](https://en.wikipedia.org/wiki/GTK%2B).

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-opened-files-and-registers.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-opened-files-and-registers.png)

Code at the top (Go), opened files, registers ("clipboard manager" and macros history)

Like [vi](https://en.wikipedia.org/wiki/Vi), Vim's interface is not based on menus or icons but on commands given in a [text user interface](https://en.wikipedia.org/wiki/Text_user_interface); its [GUI](https://en.wikipedia.org/wiki/GUI) mode, **gVim**, adds menus and toolbars for commonly used commands but the full functionality is still expressed through its [command line](https://en.wikipedia.org/wiki/Command_line) mode. Vi (and by extension Vim) tends to allow a typist to keep their fingers on the [home row](https://en.wikipedia.org/wiki/Home_row), which can be an advantage for a [touch typist](https://en.wikipedia.org/wiki/Touch_typing).[[29]](https://en.wikipedia.org/wiki/Vim_(text_editor))

Vim has a built-in [tutorial](https://en.wikipedia.org/wiki/Tutorial) for beginners called vimtutor. It's usually installed along with Vim, but it exists as a separate executable and can be run with a shell command.[[30]](https://en.wikipedia.org/wiki/Vim_(text_editor)) There is also the Vim [Users' Manual](https://en.wikipedia.org/wiki/User_guide) that details Vim's features and a [FAQ](https://vimhelp.appspot.com/vim_faq.txt.html). This manual can be read from within Vim, or found online.[[31][32]](https://en.wikipedia.org/wiki/Vim_(text_editor))

Vim also has a built-in help facility (using the `:help` command) that allows users to query and navigate through commands and features.

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-search-copen-quickfix.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-search-copen-quickfix.png)

Search (grep) inside Vim across files on disk, without plugins

### Modes[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=3)]

Vim has 12 different editing modes, 6 of which are variants of the 6 basic modes.[[33]](https://en.wikipedia.org/wiki/Vim_(text_editor)) The basic modes are:

- **Normal** mode - used for editor commands. This is also the default mode, unless the `insertmode` option is specified.
- **Visual** mode - similar to normal mode, but used to highlight areas of text. Normal commands are run on the highlighted area, which for an instance can be used to move or edit a selection.
- **Select** mode - works similarly to visual mode. However, if a printable character, carriage return, or newline (or line feed) is entered, Vim inserts the character, and starts insert mode.
    
    [[34]](https://en.wikipedia.org/wiki/Vim_(text_editor))
    
- **Insert** mode - similar to editing in most modern editors. In insert mode, buffers can be modified with the text inserted.
- **Command-line** or **Cmdline** mode - supports a single line input at the bottom of the Vim window. Normal commands (beginning with `:`), and some other specific letters corresponding to different actions (including pattern search and the filter command) activate this mode.
- **Ex** mode - similarly to Cmdline mode, it takes a single line input at the bottom of the window. However, in Cmdline mode, entering a command exits the mode when the command is executed. Entering a command in Ex mode doesn't cause the mode to change.

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-commands-history.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-commands-history.png)

Commands history below: we can edit every command and/or run it again

## Customization[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=4)]

Vim is highly customizable and extensible, making it an attractive tool for users who demand a large amount of control and flexibility over their text editing environment.[[35]](https://en.wikipedia.org/wiki/Vim_(text_editor)) Text input is facilitated by a variety of features designed to increase keyboard efficiency. Users can execute complex commands with "key mappings," which can be customized and extended. The "recording" feature allows for the creation of [macros](https://en.wikipedia.org/wiki/Macro_(computer_science)) to automate sequences of keystrokes and call internal or user-defined functions and mappings. Abbreviations, similar to macros and key mappings, facilitate the expansion of short strings of text into longer ones and can also be used to correct mistakes. Vim also features an "easy" mode for users looking for a simpler text editing solution.[[36]](https://en.wikipedia.org/wiki/Vim_(text_editor))

There are many [plugins](https://en.wikipedia.org/wiki/Plug-in_(computing)) available that extend or add new functionality to Vim, such as [linters](https://github.com/dense-analysis/ale), [integration with Git](https://github.com/airblade/vim-gitgutter), [showing colors in CSS](https://github.com/ap/vim-css-color). These complex scripts are usually written in Vim's internal scripting language, vimscript (also known as VimL),[[37]](https://en.wikipedia.org/wiki/Vim_(text_editor)) but can be written in other languages as well.

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-javascript-with-plugin-gitgutter.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-javascript-with-plugin-gitgutter.png)

Vim editing JavaScript, with installed plugin GitGutter: pluses at the left shows new lines (according to information from Git).

There are projects bundling together complex scripts and customizations and aimed at turning Vim into a tool for a specific task or adding a major flavour to its behaviour. Examples include [Cream](https://en.wikipedia.org/wiki/Cream_(software)), which makes Vim behave like a click-and-type editor, or VimOutliner, which provides a comfortable [outliner](https://en.wikipedia.org/wiki/Outliner) for users of Unix-like systems.

## Features and improvements over vi[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=5)]

Vim has a vi compatibility mode, but when that mode isn't used, Vim has many enhancements over vi.[[38]](https://en.wikipedia.org/wiki/Vim_(text_editor)) However, even in compatibility mode, Vim is not entirely compatible with vi as defined in the [Single Unix Specification](https://en.wikipedia.org/wiki/Single_UNIX_Specification)[[39]](https://en.wikipedia.org/wiki/Vim_(text_editor)) and [POSIX](https://en.wikipedia.org/wiki/POSIX) (e.g., Vim does not support vi's open mode, only visual mode). Vim has nevertheless been described as "very much compatible with Vi".[[40]](https://en.wikipedia.org/wiki/Vim_(text_editor))

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-netrw.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-netrw.png)

File manager inside vim

Some of Vim's enhancements include [completion](https://en.wikipedia.org/wiki/Autocomplete), [comparison](https://en.wikipedia.org/wiki/Data_comparison) and [merging](https://en.wikipedia.org/wiki/Merge_(revision_control)) of files (known as vimdiff), a comprehensive integrated help system, extended [regular expressions](https://en.wikipedia.org/wiki/Regular_expression), [scripting languages](https://en.wikipedia.org/wiki/Scripting_language) (both native and through alternative scripting interpreters such as Perl, Python, Ruby, Tcl, etc.) including support for [plugins](https://en.wikipedia.org/wiki/Plug-in_(computing)), a [graphical user interface](https://en.wikipedia.org/wiki/Graphical_user_interface) (known as gvim), limited [integrated development environment](https://en.wikipedia.org/wiki/Integrated_development_environment)like features, [mouse](https://en.wikipedia.org/wiki/Mouse_(computing)) interaction (both with and without the GUI), [folding](https://en.wikipedia.org/wiki/Folding_editor), editing of compressed or archived files in [gzip](https://en.wikipedia.org/wiki/Gzip), [bzip2](https://en.wikipedia.org/wiki/Bzip2), [zip](https://en.wikipedia.org/wiki/ZIP_(file_format)), and [tar](https://en.wikipedia.org/wiki/Tar_(computing)) format and files over network protocols such as [SSH](https://en.wikipedia.org/wiki/Secure_Shell), [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol), and [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol), session state preservation, [spell checking](https://en.wikipedia.org/wiki/Spell_checker), split (horizontal and vertical) and tabbed windows, [Unicode](https://en.wikipedia.org/wiki/Unicode) and other multi-language support, [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting), trans-session command, search and cursor position [histories](https://en.wikipedia.org/wiki/Command_history), multiple level and branching [undo/redo](https://en.wikipedia.org/wiki/Undo) history which can persist across editing sessions, and visual mode.

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-version.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Vim-version.png)

:version command display compilation flags (supported features)

## Vim script[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=6)]

**Vim script** (also called **vimscript** or **VimL**)[[41]](https://en.wikipedia.org/wiki/Vim_(text_editor)) is the [scripting language](https://en.wikipedia.org/wiki/Scripting_language) built into Vim.[[42]](https://en.wikipedia.org/wiki/Vim_(text_editor)) Based on the [ex](https://en.wikipedia.org/wiki/Ex_(text_editor)) editor language of the original [vi](https://en.wikipedia.org/wiki/Vi) editor, early versions of Vim added commands for control flow and function definitions. Since version 7, Vim script also supports more advanced data types such as [lists](https://en.wikipedia.org/wiki/List_(computing)) and [dictionaries](https://en.wikipedia.org/wiki/Associative_array) and (a simple form of) [object-oriented programming](https://en.wikipedia.org/wiki/Object-oriented_programming). Built-in functions such as `map()` and `filter()` allow a basic form of [functional programming](https://en.wikipedia.org/wiki/Functional_programming), and Vim script has [lambda](https://en.wikipedia.org/wiki/Anonymous_function) since version 8.0. Vim script is mostly written in an [imperative programming style](https://en.wikipedia.org/wiki/Imperative_programming).

Vim [macros](https://en.wikipedia.org/wiki/Macro_(computer_science)) can contain a sequence of normal-mode commands, but can also invoke ex commands or functions written in Vim script for more complex tasks. Almost all extensions (called plugins or more commonly scripts) of the core Vim functionality are written in Vim script, but plugins can also utilize other languages like [Perl](https://en.wikipedia.org/wiki/Perl)[[43]](https://en.wikipedia.org/wiki/Vim_(text_editor)), [Python](https://en.wikipedia.org/wiki/Python_(programming_language))[[44]](https://en.wikipedia.org/wiki/Vim_(text_editor)), [Lua](https://en.wikipedia.org/wiki/Lua_(programming_language))[[45]](https://en.wikipedia.org/wiki/Vim_(text_editor)), [Ruby](https://en.wikipedia.org/wiki/Ruby_(programming_language))[[46]](https://en.wikipedia.org/wiki/Vim_(text_editor)), [Tcl](https://en.wikipedia.org/wiki/Tcl)[[47]](https://en.wikipedia.org/wiki/Vim_(text_editor)), or [Racket](https://en.wikipedia.org/wiki/Racket_(programming_language)).[[48]](https://en.wikipedia.org/wiki/Vim_(text_editor)) These plugins can be installed manually, or through a plugin manager such as Vundle, Pathogen, or Vim-Plug.

Vim script files are stored as plain text, similarly to other code, and the filename extension is usually `.vim`. One notable exception to that is Vim's config file, `.vimrc`.

### Examples[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=7)]

```
" This is the Hello World program in Vim script.
echo "Hello, world!"

" This is a simple while loop in Vim script.
let i = 1
while i < 5
 echo "count is" i
 let i += 1
endwhile
unlet i

```

## Availability[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=8)]

Whereas vi was originally available only on [Unix](https://en.wikipedia.org/wiki/Unix) operating systems, Vim has been [ported](https://en.wikipedia.org/wiki/Porting) to many operating systems including [AmigaOS](https://en.wikipedia.org/wiki/AmigaOS) (the initial target platform), [Atari](https://en.wikipedia.org/wiki/Atari) [MiNT](https://en.wikipedia.org/wiki/MiNT), [BeOS](https://en.wikipedia.org/wiki/BeOS), [DOS](https://en.wikipedia.org/wiki/DOS), [Windows](https://en.wikipedia.org/wiki/Microsoft_Windows) starting from [Windows NT 3.1](https://en.wikipedia.org/wiki/Windows_NT_3.1), [OS/2](https://en.wikipedia.org/wiki/OS/2), [OS/390](https://en.wikipedia.org/wiki/OS/390), [MorphOS](https://en.wikipedia.org/wiki/MorphOS), [OpenVMS](https://en.wikipedia.org/wiki/OpenVMS), [QNX](https://en.wikipedia.org/wiki/QNX), [RISC OS](https://en.wikipedia.org/wiki/RISC_OS), [Linux](https://en.wikipedia.org/wiki/Linux), [BSD](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution), and [Classic Mac OS](https://en.wikipedia.org/wiki/Classic_Mac_OS).[[49]](https://en.wikipedia.org/wiki/Vim_(text_editor)) Also, Vim is shipped with every copy of [Apple](https://en.wikipedia.org/wiki/Apple_Inc.) [macOS](https://en.wikipedia.org/wiki/MacOS).[[50]](https://en.wikipedia.org/wiki/Vim_(text_editor))

Independent ports of Vim are available both for [Android](https://en.wikipedia.org/wiki/Android_(operating_system))[[51][52]](https://en.wikipedia.org/wiki/Vim_(text_editor)) and [iOS](https://en.wikipedia.org/wiki/IOS).[[53]](https://en.wikipedia.org/wiki/Vim_(text_editor))

## Neovim[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=9)]

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/221px-Neovim-logo.svg.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/221px-Neovim-logo.svg.png)

Neovim

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Neovim_0.3.7_running_under_GNOME_Terminal.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Neovim_0.3.7_running_under_GNOME_Terminal.png)

Screenshot of Neovim

![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Neovim_being_used_to_edit_its_own_configuration_file.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/220px-Neovim_being_used_to_edit_its_own_configuration_file.png)

Neovim with a status bar plugin

**Neovim**[[54]](https://en.wikipedia.org/wiki/Vim_(text_editor)) is a fork – with additions[[55]](https://en.wikipedia.org/wiki/Vim_(text_editor)) – of Vim that strives to improve the extensibility and maintainability of Vim.[[56]](https://en.wikipedia.org/wiki/Vim_(text_editor)) Neovim shares the same configuration syntax with Vim; as a result, the same [configuration file](https://en.wikipedia.org/wiki/Configuration_file) can be used with both editors, although there are minor differences between the exact options used between the two.[[57]](https://en.wikipedia.org/wiki/Vim_(text_editor)) If the added features of Neovim are not used, Neovim is compatible with almost all of Vim's features.[[58]](https://en.wikipedia.org/wiki/Vim_(text_editor))

The Neovim project was started in 2014, with some Vim community members offering early support of the high-level refactoring effort to provide better scripting, plugins, and integration with modern [GUIs](https://en.wikipedia.org/wiki/GUI) .[[59][60]](https://en.wikipedia.org/wiki/Vim_(text_editor)) The project is [free software](https://en.wikipedia.org/wiki/Free_software) and its [source code](https://en.wikipedia.org/wiki/Source_code) is available on [GitHub](https://en.wikipedia.org/wiki/GitHub).[[61]](https://en.wikipedia.org/wiki/Vim_(text_editor))

Neovim had a successful fundraiser on 23 March 2014,[[62]](https://en.wikipedia.org/wiki/Vim_(text_editor)) supporting at least one full-time developer. Several frontends are under development, making use of Neovim's capabilities.[[63][64][65]](https://en.wikipedia.org/wiki/Vim_(text_editor))

The Neovim editor is available in Ubuntu's PPAs,[[66]](https://en.wikipedia.org/wiki/Vim_(text_editor)) and several other package managers,[[67]](https://en.wikipedia.org/wiki/Vim_(text_editor)) making it possible to install on a variety of operating systems.

## See also[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=10)]

- [Learning the vi and Vim Editors](https://en.wikipedia.org/wiki/Learning_the_vi_and_Vim_Editors), a tutorial book for vi and vim, published by O'Reilly Media.
- [Editor war](https://en.wikipedia.org/wiki/Editor_war) – the rivalry between users of the Emacs and vi (Vim) text editors
- [List of text editors](https://en.wikipedia.org/wiki/List_of_text_editors)
- [Comparison of text editors](https://en.wikipedia.org/wiki/Comparison_of_text_editors)
- [Vimperator](https://en.wikipedia.org/wiki/Vimperator)
- [Pentadactyl](https://en.wikipedia.org/wiki/Pentadactyl)
- [Vimium](https://en.wikipedia.org/w/index.php?title=Vimium&action=edit&redlink=1)

## [[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=11)]

## External links[[edit](https://en.wikipedia.org/w/index.php?title=Vim_(text_editor)&action=edit&section=12)]

- [Official website](https://www.vim.org/)
    
    ![Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/10px-OOjs_UI_icon_edit-ltr-progressive.svg.png](Vim%20e712bbbc3dc14fb3bdf3ae622d3cf757/10px-OOjs_UI_icon_edit-ltr-progressive.svg.png)
    
- [TechTalk by Bram Moolenaar held on 25th Anniversary of first vim release](https://www.youtube.com/watch?v=ayc_qpB-93o) on [YouTube](https://en.wikipedia.org/wiki/YouTube)