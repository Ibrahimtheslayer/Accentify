<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Accentify

Final project for the Building AI course

## Summary
Personal AI speech tutor that helps users learn any accent or language around the globe. It guides your pronounciation,tone and rythm, giving immediate response. It is just like your accent coach. It builds confidence and fluency. It works with any language and lets you chooose any accent.

Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length! 


## Background
Access to professional accent and language coaching is expensive. You might know a language but struggle to sound natural, this affects confidence and job prospects. There are some language apps like Duolingo but they do not offer accent coaching and personalized corrections. Accentify, an AI tutor that teaches any accent or language anywhere anytime.

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?
User Flow:
 1. The user selects the language or accent he wants to learn.
 2. The AI starts by greetings in the selected accent.
 3. User repeats it and the AI gives instant feedback on how close it was 
 4. The user repeats till perfection.
Users:
 1. Students for interviews
 2. Travelers to learn a local accent
 3. Voiceover artists
 4. Anyone improving accents at home

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Data sources:
 -> Uses Mozilla Commonvoice and OpenSLR
AI techniques:
 -> Uses speech recognition to detect what user said 
 -> Uses accent classification models to comparre users accent to native accent
 -> Uses speech generation to speak back in the correct accent for repitition

Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges
 1. Hard to get high quality accent labelled data for every language
 2. Needs to support regional variations (American Southern English vs Mideastern English)
 3. Responsiveness must be fine-tuned
What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?
Accentify could add AI speech avatars to simulate conversation with different regional speakers. It could become part of online classrooms for pronounciation grading. Moreover, it could integrate with VR to create real and captivating training experiences. Eventually, Accentify could power professional style real-time accent coaching, making every global citizen feel at home, no matter where they are from or whom they are speaking to. 

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments
Sources of Inspiration:
 -> Speech models inspired by MozillaTTS and Whisper
 -> Accent feedback techniques inspired by Google's Project Relate
 -> Dataset contributions from Commonvoice and Multilingual linguistics on YouTube 

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
