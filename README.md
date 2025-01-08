## Build

You can build against all target versions by running:\
`./build-fully.ps1 -BasePath . -ProjectPath src -Configuration "Release"`
this will output the the finished package to the folder `output`, you can specify the output folder using `-OutputPath <pathtofolder>`, e.g.\
`./build-fully.ps1 -BasePath . -ProjectPath src -OutputPath $BANNERLORD_GAME_DIR -Configuration "Release"`
