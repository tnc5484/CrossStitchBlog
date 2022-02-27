## High Fives and Cross Stitch

### Welcome

The primary purpose of this blog is to serve as a space where I can document my learning as I work on my passion project. I'm taking this project on as a way to try out new areas of tech that I'm not regularly exposed to, so that I can get closer to being "full stack". Along the way, I'd like to showcase the things I'm learning, and leave notes to future me about what my thought process was. I suspect it might be fun to look back on the way I was thinking about things later and see how I've grown.

If you happen to stumble across this and want to scroll through my notes, please be my guest. Just know that I am likely not an expert on any of these topics.


### Project

I would like to create a cross stitch pattern generator. I'll provide a very high level overview of the goal here, but in future sections will dive into more detail.

Cross stitch is a type of embroidery where you create an X (or cross) in a tiled pattern. I like to think of this as filing in "the pixels" of an image.


Below is a picture of my first cross project:
![Cross stitched car created by me](car.png "Cross stitch car")

The generator will need to be able to take an image from a web page and translate it to an array of pixels.

Then it will need to determine how to translate the colors of those pixels to the closest floss color, because embroidery floss is not sold in an infinite range of colors. To start, it will work with DMC floss colors. The process of figuring out how to best translate the pixel color to embroidery floss color is called dithering.

Once the translation is made, the generator will show the new array in the form of a pattern on the web page.

### What to Expect

Some areas that I currently plan to focus my learning time on this project include:

- Front end: a simple site running that can take in a picture and display a pattern
- Processing: a deep(ish) dive on dithering and how to make sure we are getting the best quality picture from our pattern
- Infra: Figure out how to host the site, potentially databases for storing patterns for future use
- Reliability/Observability/Security: while this not intended to be a production application, I will likely use it as a way to practice other things I want to learn.

### Template for future posts

As I said, these will primarily be for my own learning, so I am going to try to include an explanation of my learning goal along with the following

- Options I considered
- Roadblocks I ran into
- Resources I ended up using to learn and get unstuck
- Link to a git commit where I actually *did the thing*
- Pictures and/or diagrams (White board scribbles) I may have
