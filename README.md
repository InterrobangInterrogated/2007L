# 2007L
12/29/2007 roblox client pulled from https://archive.roblonium.com/Client/Windows/ChromeAddersDump/Clients/2007/12.2007/December%2029%20%280.3.676.0%29/
patched using guides from https://github.com/Yosh1002/rblx-scripts

# IMPORTANT
As of writing this (4/29/2024 @ 4:28 PM, UTC -8:00) I have not been able to get multiplayer functionality to work. 

# SHADERS
To enable shaders, scroll to the bottom of https://github.com/Yosh1002/rblx-scripts/blob/master/2009/2009PatchingGuide.txt

You may have noticed the shaders do not function by default. To fix this, click "Tools", then in the menu that drops down, click "Settings". When it
prompts you if you really want to continue, click OK. Once it opens the settings menu, click the "Rendering" tab and scroll down until you see
"graphicsMode". Click on the dropdown next to it, and select "OpenGL stable".

Do NOT select OpenGL experimental, as shaders are broken in that graphics mode. I tested it out myself as of writing this (4/29/2024 @ 3:15 PM, UTC -8:00).

Once selected, click the Close button. A popup should appear reading, "Some setting changes will not take effect until you restart ROBLOX". Click the "OK"
button, then restart the client. Once it reopens, load into testplace.rbxl, and if you followed the steps correctly, it should work!

To switch back to the default rendering engine, repeat the steps listed above, but instead of selecting "OpenGL stable", select "Automatic" or whatever
you previous had it set to.
