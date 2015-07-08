# How to use each Plugin

## Vundle

### Install configured plugins

put the plugin in ~/.vimrc:

	Plugin 'gmarik/Vundle.vim'

and launch vim and run: 

	:PluginInstall

### Update configured plugins

launch vim and run: 

	:PluginUpdate

### Search plugins

Search plugins in vundle,<br>
usages:

	:PluginSearch <plugin name>

### Clean configured plugins

Requests confirmation for the removal of all plugins no longered configured
in your `.vimrc` but present in your bundle installation directory
(default: `.vim/bundle/`).

launch vim and run: 

	:PluginClean!

## fugitive.vim

<table>
<tr>
	<th>GIT command</th>
    <th>command in fugitive</th>
</tr>
<tr>
	<td>git status</td>
    <td>:Gstatus</td>
</tr>
<tr>
	<td>git log</td>
    <td>:Glog</td>
</tr>
<tr>
	<td>git add</td>
    <td>:Gwrite</td>
</tr>
<tr>
	<td>git commit</td>
    <td>:Gcommit</td>
</tr>
<tr>
	<td>git diff</td>
    <td>:Gdiff</td>
</tr>
</table>

or you can use git command in vim:

	:Git <Git command>

## NERDTree

I use following settings:

	autocmd vimenter * NERDTree
	" Keymap settings
	nnoremap    <leader>n :NERDTreeToggle<CR>
    " Type \n: open/close NERDTree

NERDTree will open automatically when vim starts up.<br>
And you can open/close NERDTree typing "\n".<br>

Followings are some shortcut about opening file in NERDTree:

* t: Open the selected file in a new tab
* i: Open the selected file in a horizontal split window
* s: Open the selected file in a vertical split window
* I: Toggle hidden files
* m: Show the NERD Tree menu
* R: Refresh the tree, useful if files change outside of Vim
* ?: Toggle NERD Tree's quick help

#TO DO in doc:

## airline
## easymotion
## python-mode
## vim-markdown
## vim-json

#TO be installed

##comment
