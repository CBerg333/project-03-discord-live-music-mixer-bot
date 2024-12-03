JOCKEYBOT 
This project is a music bot for Discord that allows for an increasingly customized listening experience, such as audio reversal, increased/decreased playback speed, and other effects such as flangers, gain, reverb, and high/low pass filters. It will have a functional queue system and will support tracks across several streaming services to ensure an extensive music library will be available for all music tastes. It will also have a mashup feature, which will automatically lock the BPM of one track to another.
  

The most important class in this program will be a Player class which will wait for user input. It will frequently cite a Storage class which contains the tracks themselves, as well as a neighboring Web class dedicated to scraping the track from whichever streaming service is being requested (Soundcloud, Youtube, etc). Once the track is stored, it will be placed in the Storage queue if another track is playing, and it will be deleted as soon as the track is finished playing to save space. The storage class will operate in two loops; one will be dedicated to waiting for a track to be queued, and the other will allow users to queue for effects as a track plays. Most effects will have their own classes, however some effects (like playback speed or filtering) will be contained in the same class, assuming they accomplish essentially the same function in different directions. If the track queue loop in the Player class is quit, that will be the bot’s sign to leave the voice chat. That loop will effectively be the bot’s Main.

![This is a screenshot.](images.png)
# How to run
Provide here instructions on how to use your application.   
- Download the latest binary from the Release section on the right on GitHub.  
- On the command line uncompress using
```
tar -xzf  
```
- On the command line run with
```
./hello
```
- You will see Hello World! on your terminal. 

# How to contribute
Follow this project board to know the latest status of the project: [http://...]([http://...])  

### How to build
- Use this github repository: ... 
- Specify what branch to use for a more stable release or for cutting edge development.  
- Use InteliJ 11
- Specify additional library to download if needed 
- What file and target to compile and run. 
- What is expected to happen when the app start. 
