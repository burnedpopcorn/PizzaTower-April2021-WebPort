# Pizza Tower April 2021 Build Web Port

A Port of the April 2021 Build of Pizza Tower to the Web Browser

Demo Site: http://dummydomain.x10.mx/pt-april-build/PizzaTower_GM2.html

Made it because @BFDIFirey requested it, and I had some free time

# I will be Archiving this Repo!
  
  Why? Because I'm just not very interested in it

  But I will be keeping the website up because I can

## Download for Self-Hosting
Download the Latest (and probably only) release from the Releases Tab

## To Compile and Run it for Yourself

> [!IMPORTANT]
> Use Gamemaker Studio Version 2023.4.0.84-113, because anything lower will simply not compile and anything newer fucks up when compiling
- Download the source code from @Angelos2008, where he has the code hosted [here](https://github.com/Angelos2008/PizzaTowerApril2021)
- Use GX.GAMES and VM options to compile it, and to obtain the compiled files from GameMaker Studio for free, just go to C:/Users/(your username)/AppData/Local/GameMakerStudio2/GMS2TEMP while locally running the game
- In which you will find a folder called PizzaTower_GM2_(some numbers)_VM after you compiled the project
- The files you use to run the project on a server are within the /runner subdirectory

The said files will NOT run locally as file:// will just result in CORS errors and will not allow runner.html (the main file that runs this build of Pizza Tower) to read the game files (Limitation of Emscripten, which is used when compiling with these settings)

The only way for them to work is if you have a web server running this, or a local server using something like python
- Which you can do by entering the directory containing runner.html and other files and typing the command python3 -m http.server in the linux terminal or py -m http.server for windows powershell given you installed python
- At which point you can enter http://localhost:8000/runner.html to play the game locally

## Shout-outs to
- BFDIFirey, for requesting it over at my [1.1.0 Web Port](https://github.com/burnedpopcorn/Pizza-Tower-1.1.0-Web-Port)
- Angelos2008, for the source code, and later specifing the Gamemaker Version (You can find it [Here](https://github.com/Angelos2008/PizzaTowerApril2021))
- And of course Tour de Pizza for the base game

And music works, unsurprising considering that FMOD wasn't used yet (Honestly fuck FMOD)
