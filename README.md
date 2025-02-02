Plugins for the [orchid text editor](https://github.com/Dream-Imperium/orchid)

*Note: if you make a pull request, the table should be updated and kept in
alphabetical order. If your plugin is large (or you'd otherwise prefer it to
have its own repo), the table can simply be updated to add a link to the repo;
otherwise the plugin file itself can be submitted. If a plugin's link resolves
to something other than a raw file it should be marked with an asterisk.*

---

Plugin | Description
-------|-----------------------------------------
[`autoinsert`](plugins/autoinsert.lua?raw=1) | Automatically inserts closing brackets and quotes
[`autowrap`](plugins/autowrap.lua?raw=1) | Automatically hardwraps lines when typing
[`bigclock`](plugins/bigclock.lua?raw=1) | Shows the current time and date in a view with large text
[`bracketmatch`](plugins/bracketmatch.lua?raw=1) | Underlines matching pair for bracket under the caret
[`centerdoc`](plugins/centerdoc.lua?raw=1) | Centers document's content on the screen
[`colorpreview`](plugins/colorpreview.lua?raw=1) | Underlays color values (eg. `#ff00ff` or `rgb(255, 0, 255)`) with their resultant color. 
[`console`](plugins/console.lua?raw=1)* | A console for running external commands and capturing their output
[`copyfilelocation`](plugins/copyfilelocation.lua?raw=1) | Copy file location to clipboard
[`datetimestamps`](plugins/datetimestamps.lua?raw=1) | Insert date-, time- and date-time-stamps
[`detectindent`](plugins/detectindent.lua?raw=1) | Automatically detects and uses the indentation size and tab type of a loaded file
[`dragdropselected`](plugins/dragdropselected.lua?raw=1) | Provides basic drag and drop of selected text (in same document)
[`drawwhitespace`](plugins/drawwhitespace.lua?raw=1) | Draws tabs and spaces 
[`eval`](plugins/eval.lua?raw=1) | Replaces selected Lua code with its evaluated result
[`exec`](plugins/exec.lua?raw=1) | Runs selected text through shell command and replaces with result
[`ghmarkdown`](plugins/ghmarkdown.lua?raw=1) | Opens a preview of the current markdown file in a browser window 
[`gitstatus`](plugins/gitstatus.lua?raw=1) | Displays git branch and insert/delete count in status bar
[`gofmt`](plugins/gofmt.lua?raw=1) | Auto-formats the current go file, adds the missing imports and the missing return cases
[`hidelinenumbers`](plugins/hidelinenumbers.lua?raw=1) | Hides the line numbers on the left of documents 
[`hidestatus`](plugins/hidestatus.lua?raw=1) | Hides the status bar at the bottom of the window
[`inanimate`](plugins/inanimate.lua?raw=1) | Disables all transition animations
[`indentguide`](plugins/indentguide.lua?raw=1) | Adds indent guides
[`language_angelscript`](plugins/language_angelscript.lua?raw=1) | Syntax for the [Angelscript](https://www.angelcode.com/angelscript/) programming language
[`language_batch`](plugins/language_batch.lua?raw=1) | Syntax for Windows [Batch Files](https://en.wikipedia.org/wiki/Batch_file)
[`language_cmake`](plugins/language_cmake.lua?raw=1) | Syntax for the CMake build system language
[`language_cpp`](plugins/language_cpp.lua?raw=1) | Syntax for the [C++](https://isocpp.org/) programming language
[`language_csharp`](plugins/language_csharp.lua?raw=1) | Syntax for the [C#](http://csharp.net) programming language
[`language_d`](plugins/language_d.lua?raw=1) | Syntax for the [D](https://dlang.org/) programming language
[`language_elixir`](plugins/language_elixir.lua?raw=1) | Syntax for the [Elixir](https://elixir-lang.org) programming language
[`language_elm`](plugins/language_elm.lua?raw=1) | Syntax for the [Elm](https://elm-lang.org) programming language
[`language_fe`](plugins/language_fe.lua?raw=1) | Syntax for the [fe](https://github.com/rxi/fe) programming language
[`language_fennel`](plugins/language_fennel.lua?raw=1) | Syntax for the [fennel](https://fennel-lang.org) programming language
[`language_gdscript`](plugins/language_gdscript.lua?raw=1) | Syntax for the [Godot Engine](https://godotengine.org/)'s GDScript scripting language
[`language_glsl`](plugins/language_glsl.lua?raw=1) | Syntax for the [GLSL](https://www.khronos.org/registry/OpenGL/specs/gl/) programming language
[`language_go`](plugins/language_go.lua?raw=1) | Syntax for the [Go](https://golang.org/) programming language
[`language_hlsl`](plugins/language_hlsl.lua?raw=1) | Syntax for the [HLSL](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl) programming language
[`language_hs`](plugins/language_hs.lua?raw=1) | Syntax for the [Haskell](https://www.haskell.org/) programming language
[`language_java`](plugins/language_java.lua?raw=1) | Syntax for the [Java](https://en.wikipedia.org/wiki/Java_(programming_language)) programming language
[`language_jiyu`](plugins/language_jiyu.lua?raw=1) | Syntax for the [jiyu](https://github.com/machinamentum/jiyu) programming language
[`language_make`](plugins/language_make.lua?raw=1) | Syntax for the Make build system language
[`language_meson`](plugins/language_meson.lua?raw=1) | Syntax for the [Meson](https://mesonbuild.com) build system language
[`language_nim`](plugins/language_nim.lua?raw=1) | Syntax for the [Nim](https://nim-lang.org) programming language
[`language_odin`](plugins/language_odin.lua?raw=1) | Syntax for the [Odin](https://github.com/odin-lang/Odin) programming language
[`language_php`](plugins/language_php.lua?raw=1) | Syntax for the [PHP](https://php.net) programming language
[`language_pico8`](plugins/language_pico8.lua?raw=1) | Syntax for [Pico-8](https://www.lexaloffle.com/pico-8.php) cartridge files
[`language_powershell`](plugins/language_powershell.lua?raw=1) | Syntax for [PowerShell](https://docs.microsoft.com/en-us/powershell) scripting language
[`language_psql`](plugins/language_psql.lua?raw=1) | Syntax for the postgresql database access language
[`language_rust`](plugins/language_rust.lua?raw=1) | Syntax for the [Rust](https://rust-lang.org/) programming language
[`language_sh`](plugins/language_sh.lua?raw=1) | Syntax for shell scripting language
[`language_tex`](plugins/language_tex.lua?raw=1) | Syntax for the [LaTeX](https://www.latex-project.org/) typesetting language
[`language_wren`](plugins/language_wren.lua?raw=1) | Syntax for the [Wren](http://wren.io/) programming language
[`lastproject`](plugins/lastproject.lua?raw=1) | Loads the last loaded project if orchid is launched without any arguments
[`lfautoinsert`](plugins/lfautoinsert.lua?raw=1) | Automatically inserts indentation and closing bracket/text after newline
[`linecopypaste`](plugins/linecopypaste.lua?raw=1) | Copy, cut and paste the current line when nothing is selected
[`lineguide`](plugins/lineguide.lua?raw=1) | Displays a line-guide at the line limit offset
[`linter`](plugins/linter.lua?raw=1)* | Linters 
[`macmodkeys`](plugins/macmodkeys.lua?raw=1) | Remaps mac modkeys `command/option` to `ctrl/alt`
[`markers`](plugins/markers.lua?raw=1) | Add markers to docs and jump between them quickly
[`motiontrail`](plugins/motiontrail.lua?raw=1) | Adds a motion-trail to the caret 
[`openfilelocation`](plugins/openfilelocation.lua?raw=1) | Opens the parent directory of the current file in the file manager
[`openselected`](plugins/openselected.lua?raw=1) | Opens the selected filename or url
[`projectmanager`](plugins/projectmanager.lua?raw=1) | Save projects and load/reload them quickly
[`rainbowparen`](plugins/rainbowparen.lua?raw=1) | Show nesting of parentheses with rainbow colours
[`scale`](plugins/scale.lua?raw=1) | Provides support for dynamically adjusting the scale of the code font / UI (`ctrl+-`, `ctrl+=`)
[`scalestatus`](plugins/scalestatus.lua?raw=1) | Displays current scale (zoom) in status view (depends on scale plugin)
[`selectionhighlight`](plugins/selectionhighlight.lua?raw=1) | Highlights regions of code that match the current selection 
[`sort`](plugins/sort.lua?raw=1) | Sorts selected lines alphabetically
[`spellcheck`](plugins/spellcheck.lua?raw=1) | Underlines misspelt words *dictionary file must be placed beside the executable*
[`theme16`](https://github.com/monolifed/theme16)* | Theme manager with base16 themes
[`titleize`](plugins/titleize.lua?raw=1) | Titleizes selected string (`hello world` => `Hello World`)
[`todotreeview`](https://github.com/drmargarido/TodoTreeView)* | Todo tree viewer for annotations in code like `TODO`, `BUG`, `FIX`, `IMPROVEMENT`
[`togglesnakecamel`](plugins/togglesnakecamel.lua?raw=1) | Toggles symbols between `snake_case` and `camelCase`
[`unboundedscroll`](plugins/unboundedscroll.lua?raw=1) | Allows scrolling outside the bounds of a document
[`workspace`](plugins/workspace.lua?raw=1) | Retains project's layout and open documents between sessions
