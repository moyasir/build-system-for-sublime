<h3>Build system for sublime for the following languages</h3>
<ol>
<li>Python3</li>
<li>Java</li>
<li>Cpp</li>
</ol>

<p><b>Note :</b> It requires terminus plugin because sublime console doesn't take any input</p>

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


