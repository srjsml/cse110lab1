#### Directory:
[Programming Experience](#programming-experience)
[Miscellaneous Facts](#miscellaneous-facts)
[Comedic Relief](#lol)

# Oh, hey! Didn't see you there...
![A picture of me](/pictures/SS_profilepicture.jpeg)

# I am **Seeraj Somla** (he/him), a 3rd year Computer Engineering transfer student at UCSD. Let me tell you a bit about myself.

### Programming Experience

#### I've been programming for almost a decade now -- started waaay back in sixth grade. Now that I think about it... time really flies, but honestly, I really only took programming seriously around ~4 years ago. Being avid gamers, my friends and I thought it would be a cool idea to learn Java and build our own game. To be honest, we never really finished the project. But the process was loads of fun, and we eventually got back together and built a small game (in _Java_) for our AP Computer Science class. For all four years of high school, I was part of my school's FIRST Robotics team, where I helped the design and software teams. I spent long hours figuring out how _C++_ and the _Robot Operating System_ worked. When I started community college, I dabbled with Arduinos, Raspberry Pis, and the likes, which is where I found a deeper passion for embedded systems. For my Honors Project, I built a "self-driving" car using a dismantled RC car, an Arduino, and proximity sensors. Essentially, the car would detect how close it was to a wall and any approaching obstacles, and slow down before avoiding the obstacle or making a full stop if it could not find a potential path forward. 

#### I was also part of a couple Robosub teams (San Diego City Robotics & Triton Robosub), where I primarily worked on hardware design and low-level programming. I wrote a sensor testing program, which plotted data from numerous sensors using _matplotlib_, applied numerous analysis techniques to the data using _numpy_, and outputted Pixhawk header values to an on-board display. I also designed, prototyped, and built a hydrophone array utilizing an _FPGA_ board and custom PCBs. I'm currently using _C_ and _Verilog_ to build the entire DSP system on the FPGA (still in development). 

#### Over the pandemic, I spent some of my free time learning web development and audio plugin development, as one of my main hobbies is producing music. Unfortunately, I realized pretty quickly that I'm not a fan of webdev. I do think it is a great "canvas" to showcase projects (which is now what I'm thinking of doing). On the otherhand, audio plugin development is what really caught my eyes for the past few months. Being able to use your own plugins to make music is such a gratifying feeling. Currently, I'm working on my own reverb and sample splicing plugin using C++, the _JUCE SDK_, and _MaxMSP_.

### Miscellaneous Facts:

### One of my favorite quotes of all time:
>I see now that the circumstances of one's birth are irrelevant; it is what you do with the gift of life that determines who you are - Mewtwo

### Here is the first reverb algorithm I implemented (adapted from [stackoverflow](https://stackoverflow.com/questions/5318989/reverb-algorithm)):
```
{
int delayMilliseconds = 100; 
int delaySamples = 
    (int)((float)delayMilliseconds * 44.1f); 
float decay = 0.33f;
for (int i = 0; i < buffer.length - delaySamples - 1; i++)
{
    buffer[i + delaySamples] += (short)((float)buffer[i] * decay);
}
}
```

### These are my favorite snacks:
- Cheez-its
- Tim-Tams
- Almond-Joy

### These are my top 3 most played artists on Spotify:
1. [quickly, quickly](https://open.spotify.com/artist/5XTn5Az9AcSKu0oaauC5ES)
2. [Medasin](https://open.spotify.com/artist/62vbsDRAq0qHdezaCOzB0T)
3. [Brasstracks](https://open.spotify.com/artist/5sKvgmG84C0bIMWeS2SRPr)

### LOL
[Here is a page full of my favorite memes!](memes.md)


