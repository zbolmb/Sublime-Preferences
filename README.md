# Sublime-Preferences
Personal Sublime preferences

List of dependences added for better usage of sublime.

First Off, use Ctrl + ` to open the sublime text console
Then copy paste below into console

Plugins:
- BracketHighlighter
- Git gutter
- Sublime Linter
- Material Theme
- Trailing Whitespace


Preference Edits:

~~~~
{
	"always_show_minimap_viewport": true,
	"bold_folder_labels": true,
	"theme": "Material-Theme.sublime-theme",
	"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
	"fade_fold_buttons": false,
	"font-face": "Operator Mono",
	"font-size": 18,
	"font_options":
	[
		"gray_antialias",
		"subpixel_antialias"
	],
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_guide_options":
	[
		"draw_normal",
		"draw_active"
	],
	"line_padding_bottom": 3,
	"line_padding_top": 3,
	"overlay_scroll_bars": "enabled",
	"trim_trailing_white_space_on_save": true,
	"word_wrap": true
}
~~~~

Keybindings:

~~~~
{ "keys": ["super+r"], "command": "reindent" }
~~~~

Package Control:

"Ctrl + `" to open console
(Sublime 3)
~~~~
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
~~~~
