# consolas-font-for-powerline
Powerline is a nice vim plugin, consolas is a nice font under windows, in order to use consolas in putty or securecrt to work with powerline, the font must be patched.
windows下使用putty在vim中的airline插件里显示只读文件存在问题，需要字体支持powerline字体。安装这个字体并在vim的.vimrc.before.local中配置
let g:airline_powerline_fonts=1就可以正常使用了。
