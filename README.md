<h3>Build system for sublime for the following languages</h3>
<ol>
<li>Python3</li>
<li>Java</li>
<li>Cpp</li>
</ol>

<p><b>Note :</b> It requires terminus plugin because sublime console doesn't take any input</p>

<h5>Steps:</h5>
<ol>
<li></li>
</ol>

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
