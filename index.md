![A picture of me](/pictures/SS_profilepicture.jpeg)

# Oh, hey! Didn't see you there...
## I am **Seeraj Somla**, a 3rd year Computer Engineering transfer student at UCSD. Let me tell you a bit about myself.
### I've been programming for almost a decade - started waaay back in sixth grade. Time really flies, but honestly, I feel like I really only began taking programming seriously around 4 years ago. I started programming in Java, and slowly made my way to Python and C++. In high school, I was part of a FIRST Robotics team, where I worked on the design and software teams. When I started community college, I started dabbling in Arduinos, Raspberry Pis, and the likes, which is where I found a deeper passion for embedded systems. I was also part of a couple Robosub teams (San Diego City Robotics & Triton Robosub), where I primarily worked on hardware and low level programming. I wrote a sensor testing program, which plotted data from numerous sensors using _matplotlib_ and _numpy_ and outputted Pixhawk header values to an on-board display. I also designed and prototyped a 4-way hydrophone array utilizing an _FPGA_ and C/Verilog. Over the pandemic, I dabbled in web development and audio plugin development, as one of my main hobbies is producing music. Needless to say, I fell in love with building my own audio plugins and eventually hope to turn it into my career.
## One of my favorite quotes of all time:
>I see now that the circumstances of one's birth are irrelevant; it is what you do with the gift of life that determines who you are - Mewtwo

## Here is the first reverb algorithm I implemented (adapted from [stackoverflow](https://stackoverflow.com/questions/5318989/reverb-algorithm)):
```
{
int delayMilliseconds = 100; // half a second
int delaySamples = 
    (int)((float)delayMilliseconds * 44.1f); 
float decay = 0.33f;
for (int i = 0; i < buffer.length - delaySamples - 1; i++)
{
    buffer[i + delaySamples] += (short)((float)buffer[i] * decay);
}
}
```

## These are my favorite snacks:
- Cheez-its
- Tim-Tam
- Almond-Joy

## These are my top 3 most played artists on Spotify:
1. quickly, quickly
2. medasin
3. Brasstracks


