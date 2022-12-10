<h3>Build system for sublime for the following languages</h3>
<ol>
<li>Python3</li>
</ol>

2] Java
3] Cpp
Note : It requires terminus plugin because sublime console doesn't take any input

Steps:
1)

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
