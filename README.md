<h3>Build system for sublime for the following languages</h3>
<ol>
<li>Python3</li>
<li>Java</li>
<li>Cpp</li>
</ol>

<p><b>Note :</b> It requires terminus plugin because sublime console doesn't take any input</p>
<ol>
<li>install package control using ctrl+shift+p.</li>
<li>install package > terminus using ctrl+shift+p.</li>
<li>then go to preference > package > terminus > command pallete and
<p>Put this to terminus command pallete</p>
<code>
[
	{
        "caption": "Terminal",
        "command": "terminus_open",
        "args"   : {
           "cmd": "bash",
           "cwd": "${file_path:${folder}}",
           "title": "Command Prompt",
           "panel_name": "Terminal"
        }
   }
]

</code>
</li>
<li>then go to preference > package > terminus > keybinding and
<p>Put this to terminus keybinding</p>
<code>
[
	{
       "keys": ["ctrl+`"],
       "command": "terminus_open",
       "args" : {
           "cmd": "bash",
           "cwd": "${file_path:${folder}}",
           "panel_name": "Terminal"
       }
   },
   { 
    "keys": ["ctrl+`"], "command": "terminus_close", "context": [{ "key": "terminus_view"}]
   },   
]

</code>
</li>
<li>then create a build for the above language and paste the code for the following <b>I've already uploaded the build command code for specific lang in dir below is the link.</li>
</ol>

<a href="https://github.com/moyasir/build-system-for-sublime/blob/main/Python3.sublime-build">python3</a>
<a href="https://github.com/moyasir/build-system-for-sublime/blob/main/Java.sublime-build">java</a>
<a href="https://github.com/moyasir/build-system-for-sublime/blob/main/cpp.sublime-build">cpp</a>





