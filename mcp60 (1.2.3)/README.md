# mcp60 (1.2.3)

[Minecraft 1.2.3](https://minecraft.fandom.com/wiki/Java_Edition_1.2.3)

## Instructions

Download `mcp60.zip` and extract.<br/>
Set up `jars` folder as usual.<br/>
Download `mcp60-idea.rar` and extract into mcp60's folder.<br/>

Now for the hard part.

Copy the `resources` folder in the `jars` folder, in mcp60's root folder.<br/>
Open the `idea` folder (extracted from `mcp60-idea.rar` earlier) and go into the `client` folder.<br/>
Paste the `resources` folder into `run` folder.<br/>

Extract these folders / files from the `minecraft.jar` to the `resources` folder in `idea/client`.<br/>
This is **NOT** the same `resouces` folder as in `idea/client/run`!!!

<details>

`achievement`<br/>
`armor`<br/>
`art`<br/>
`environment`<br/>
`font`<br/>
`gui`<br/>
`item`<br/>
`lang`<br/>
`misc`<br/>
`mob`<br/>
`terrain`<br/>
`title`<br/><br/>

`font.txt`<br/>
`pack.png`<br/>
`pack.txt`<br/>
`particles.png`<br/>
`terrain.png`<br/>

</details>

Obtain jar files (usually in `.minecraft/libraries`):
<details>

- `argo-3.2-small.jar`
- `codecjorbis-20101023.jar`
- `codecwav-20101023.jar`
- `librarylwjglopenal-20100824.jar`
- `soundsystem-20120107.jar`
</details>

Then move them into the `lib` folder that is in the root MCP folder.<br/>

Run `decompile.bat` or `decompile.sh` (depends on your platform)<br/>
Open IntelliJ IDEA and use the `idea` folder

Notes
--
Each time you run the MCP decompile script, you'll run into a build error, regarding a function in one of Minecraft's classes overriding a codec library. I recommend commenting it out. This most likely happens due to improper library files.<br/>
The game will still run fine with this function commented out.
