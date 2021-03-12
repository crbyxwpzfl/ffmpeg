# personal portable ffmpeg 2020-12-09
setup for cli add path\to\dir to PATH enviornment variable

## ffplay web embeded video
	```powershell
	youtube-dl -g url | Tee-Object -Variable Var | ffplay $Var
	```

## ffplay smal
	```batch
	@echo off
	
	ffplay -x 720 %1
	```

# [source from](https://github.com/GyanD/codexffmpeg)

