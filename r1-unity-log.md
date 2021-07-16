**#100DaysOfCode Log - Round 1 - Anubis Lockward**
**The log of my #100DaysOfCode challenge. Started on [August 8, Thursday, 2019].**

**Log**

**R1D1 - August 15th, 2019**
Set up VSCode to work with Unity and managed to start working on the first challenge of the Udemy Unity course called Complete C# Unity Developer 2D: Learn to Code Making Games.

**R1D2 - August 16th, 2019**
Learned how to handle User Input through the keyboard and worked a little with updating variables, decision making and creating methods to handle calculations and prompts to users.

**R1D3 - August 19th, 2019**
Finished Section 2 of the Complete C# Unity Developer 2D: Learn to Code Making Games course on Udemy. Looking forward to the upcoming section.

**R1D4 - August 23th, 2019**
Started Section 3 of the C# Unity Developer course, learned about how to make sprites in Unity and got introduced to the next project, we're supposed to create a text based adventure, looking forward to it.

**R1D5 - August 25th, 2019**
Completed the sprite challenge from section 3. I have been noticing that I have to push myself to keep on advancing on this course. My motivation is at an all time low, I rather be wasting time doing stupid stuff, don't know why this is since making games has always been a dream of mine.

**R1D6 - October 10th, 2020**
Had to do the Canvas and setup the GameObject for the Choose Your Own Journey project. Have everything up and running, and tidied up a bit the assets of the game into their respective folders.

**R1D7 - October 11th, 2020**
Started porting all of the Story Design cards I had online and implemented them on Unity, making a somewhat workable game. Everything is ready to the first path that you would be taking, but now I have realized that I still have to implement Paths two and three, before moving on with the game. Also, I have to translate all of the text that's in Spanish as well as complete the cards with some better worded text.

**R1D8 - November 3rd, 2020**
I don't really remember when was the last time I worked in Unity, but I know I have been working on it for several days. I managed to finish with my Story Design, translated all the text that was in Spanish, and replaced all the dummy text with proper dialogue and options. Added all the options for each one of the clues, and completed three different endings for the game. Tried adding some choices that were optional and appeared depending on other choices, but the game seemed to break down when I implemented that, so I scratched it for now. Now I want to implement the capacity of using different items and have that influence how the game is played.

**R1D9 & 10 - November 4th-5th, 2020**
I have been learning and working on improving the overall look of my Text based game. I finally did it and I'm pretty happy with the overall look it has right now. I am thinking of changing it and making it look different, but for now I am more focused on advancing the course. I have also been working with a friend in doing a sort of "pair" project, where I'm helping him with some aspects of his game, while I can also ask him questions about things that I don't know about Unity that he does. I have seen some projects that other people have posted on the forum for the course, and that got me really inspired into what aspects of the game I can improve on, and how far I can push it.

**R1D10 - November 7th, 2020**
Simplified nextState selection code. Also gave a few finishing touches to the game and published it. You can play it at: https://sharemygame.com/@ColdDog/monster-hunting-feast please keep in mind that it's my first game. But any feedback or suggestions are welcome.

**R1D11 - November 8th, 2020**
Not much done today. Just set up github to work with my Unity project in preparation to start the NumberWizard project of the Unity course.

**R1D12 - November 9th, 2020**
Setup remote repository for the Monster Hunting Feast game. Also started adding new states, and modyfing existing ones to the Clue 3, to make it more epic and exciting, as well as giving more choices to the player and help establish how much of a badass The Stone character is.

**R1D13 - November 10th, 2020**
Worked a bit more on expanding the choices for the third clue. Adding more sequences to the fight against the brothers.

**R1D14 - November 11th, 2020**
Added a few more options, continuing with the fight against the brothers.

**R1D15 - November 12th, 2020**
Continued adding more choices to the fight against the Waverly Brothers, and I'm pretty happy with the result. I think I'm done with that part, but now I have to correct some of the text, and polish the wording a little since some of the choices only have draft text. Also started working with implementing a way to implement choices that active or deactivate certain events within the story.

**R1D16 - November 14th, 2020**
Have been organizing the story design document to make it look better and help me when I want to add new pieces to the story.

**R1D17 - November 16th, 2020**
Finished organizing all three branches of the story on the Story Design document. Also managed to finish adding to Unity two out of three fight scenarios against the Waverly Brothers. I have yet to polish the text a little more, and add the last fight against Bruno and Reg.

**R1D18 - November 19th, 2020**
Started working with the Number Wizard UI game, managed to implement a few of the screens and the script to change scenes. I'm about halfway through Section #4 of the Unity Game Developer course.

**R1D19 - November 20th, 2020**
Finished Section 4 of the Unity course and completed the Number Wizard UI. I learned how to create various Scenes and connect them together using SceneManager and connecting them to Buttons on the UI, as well as how to call functions when a Button is clicked. Also learned how to use Anchors, TextMesh Pro to make the text look cooler and how to anchor elements within another so that they look good even when resized, as well as making the Canvas scale up or down with the screen where it is being displayed. Last but not least, I learned how to deploy the application from Unity, to an OS.

**R1D20 - December 10th, 2020**
I stepped away for a bit from working on my project because I was on vacation, but now we are back. Today I started working on the last bit of Story Design, finishing a missing bit of the fight against the Waverly Brothers. I also modified the story cards of the Text game on Unity and separated the Options from the Story Text. I also made the text resizable by adding two Components to the images I use as backgrounds for the text. The components were Vertical Layoug Group and Content Size Fitter.

**R1D21 - December 11th, 2020**
Kept working on the last part of the battle against the Waverly Brothers. This time The Stone vs Reg The Shinning Moon and Toothless Bruno. It's still missing a couple of parts and there are some parts that I need to translate from Spanish to English. Also added most of the extra options to Unity. I still have to organize the Story Design a bit more since I'm not happy with the way it's looking right now.

**R1D22 - December 14th, 2020**
Added a rustic inventory manager Scriptable Object and managed to make it activate an State based on whether the player picked a weapon or not. I tested it without picking the weapon, and when I picked it and it worked fine. Also added an script to reset the game each time the player started the game, or picked the option to start the game over. I also completed the remaining text for the last part of the fight against the Weaverly brothers.

**R1D23 - December 15th, 2020**
Created two new types of States, one for One Time States, which are states that can only be picked once and then are disabled, and another one for Loot States, which are States that add a specific item to the Inventory. The Inventory also enables other States that depend on which item you have, but this functionality is going to be transferred to the Game Manager, since the inventory only knows about storing, removing and retrieving items. I also modified the States related to the Jackpot state, to make them either One Time States or Loot States. Now I also have to add the proper descriptions to the items you find, and finish a tiny bit in the last fight with the Weaverly Brothers, which is the one where Toothless Bruno runs away and you slash him with either the sword, the axe, or both. I'm also thinking of adding an image instead of text to the Loot States, or maybe a combination of both.

**R1D24-26, December 18th, 2020**
Have been working in creating a few new options in the Story Design document to describe the items you find in the Jackpot, and what you do with them.