<h3>Build system for sublime for the following languages</h3>
<ol>
<li>Python3</li>
<li>Java</li>
<li>Cpp</li>
</ol>

<p><b>Note :</b> It requires terminus plugin because sublime console doesn't take any input</p>

<p>Put his to terminus command pallete</p>
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
