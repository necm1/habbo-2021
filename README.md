# Habbo 2021

Special thanks to:
- [@ntuative](https://github.com/ntuative)
- [@Dooeha](https://devbest.com/members/doeha.105220/)

Version: WIN63-202111081545-75921380

## Build

Required files:

- [Flex SDK](http://fpdownload.adobe.com/pub/flex/sdk/builds/flex4.6/flex_sdk_4.6.0.23201B.zip)
- [Adobe AIR SDK](https://airsdk.harman.com/)
- JRE

1. Clone the repository
`git clone https://github.com/necm1/habbo-2021.git`
2. Update `build.bat` with the path to **Flex SDK 4.6**
3. Open a terminal and run `build.bat` or run the compiler directly:
```ps
flex_sdk_4.6.0.23201B\bin\mxmlc -target-player=11.1 --incremental=true -output bin\Habbo.swf -source-path src -default-background-color=#000000 -omit-trace-statements=false -optimize=true src\HabboAir.as
```

The bin folder should now contain `Habbo.swf`.

## Source
- https://github.com/ntuative/habbo-2021
- https://devbest.com/threads/recompilable-habbo-swf-2021-11-10.92485/
