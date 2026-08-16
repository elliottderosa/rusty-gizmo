# Rusty Gizmo
The Gizmo language written in rust.

## Examples
Check out the examples folder for some programs to show you the ropes.

## How do Compilers work?
Check out the LEARN.md file in the codes section above to see an outline for how a compiler works (with examples).

I failed miserably in so many aspects and then tried to work through them. Let's just say that my experience was akin to a sword being hammered and bent in the forge. But the difficulty was what made it fun. And because of it, I was shaped and made stronger through the challenges. I may have also just written way too many Gizmo compilers in different languages. I think the most beneficial thing you can learn from compilers is how to bridge the gap between modern programming languages and the assembly languages and software that are closer to the operating system level. LLVM was a very useful stepping stone as well if writing out your own assembly code generator doesn't seem worth it. I think I've done both... Anyway, I hope you feel inspired to delve just a little bit deeper into the realm of compiler design!

## Building
To clone the project from github, use:  
```shell
git clone https://github.com/ELLDER054/rusty-gizmo.git
```
Then, go to the directory and use cargo to build it.  
```shell
cd rusty-gizmo
cargo install --path .
```
Now you can use the `gizmoc` command to run gizmo files.  
```
gizmoc file.gizmo
```
