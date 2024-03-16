# stremio-m1

Hey, this is the compiled version of stremio-shell (Stremio app) for M1 (apple silicon or arm64)

It works only if you've dependencies installed on your system. You need to have HomeBrew installed and dependencies in it, if you don't know any of this just don't try to run it. 

run in a terminal (after installing brew):

brew install mpv node qt@5 ffmpeg openssl@3

With that, it'll work. 

If you run into some error like "The app is damaged", run in a terminal:

sudo xattr -r -d com.apple.quarantine /Applications/Stremio.app

Obviously run that after you've moved Stremio.app to /Applications folder. 

