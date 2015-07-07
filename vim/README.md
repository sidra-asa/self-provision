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

#TO DO in doc:

## nerdtree
## airline
## easymotion
## python-mode
## vim-markdown
## vim-json

#TO be installed

##comment
