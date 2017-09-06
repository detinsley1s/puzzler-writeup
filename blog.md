# A Puzzling Adventure in "Puzzler"

## Introduction

Hello, I'm Dan Tinsley, and I'm about to tell you about an incredible new game that I developed entitled "Puzzler." You appear in a strange, new world wondering, "What am I doing here?" and hope for escape. However, there is no escape. There is only an endless cycle of deciphering a puzzle within a creepy, desolate shack over and over again. So, with that as an introduction, let's dive deeper into how this exciting new experience came into life.

---

## How to Play

The player begins at a Start Panel, where he/she clicks on a button to begin. He/she moves into a shack where two rows of orbs exist, with two on top and three on bottom. They then glow in a random sequence five times, which the user has to repeat to beat the puzzle. After completing it, he/she moves to a Restart Panel, with a button that sends the user back to the beginning so that he/she can play again.

---

## Planning Stage
### Persona

My initial step was determining who my target audience was for the game. I knew that my game could potentially be played by anyone from all ages and demographics, but I wanted to focus on who the main group would be and what a typical member would be like. I came up with someone like this:

![Image of Joe Schenkler](./images/persona-student.jpg)

**Name:** Joe Schenkler

**Age:** 19

**Gender:** Male

**Hobbies:** Video games, especially puzzle games; Virtual Reality

**Quote:** Anytime he completes a puzzle, he exclaims: "I am the greatest puzzle master ever!"

**Occupation:** Part-time in fast food; College student

**VR Experience:** Loves VR, but currently can only afford mobile VR devices, such as Google Cardboard

### Sketch of Game Environment

Now that I had a sample persona in mind, I next needed to brainstorm about where my Puzzler game would be located. Initially, I thought big, by sketching out two possibilities of a tent and of a giant tree:

![Image of sketches](./images/puzzler-sketches.jpg)

However, I decided to keep it simple and instead went with a comfortable little shack in the middle of nowhere, as can be seen in the finished game.

---

## Building Stage
### Stage 1

I started by building my shack piece by piece until it seemed large enough not to feel claustrophobic, while also cozy enough to feel secluded. I then added the game orbs, which would be used for the puzzle mechanic; some barrels as decoration; and finally torches on the walls that emitted enough light to give the room a creepy aesthetic.

![Left Side](./screenshots/Stage-1/Screenshot_20170825-222500.png)

![Center](./screenshots/Stage-1/Screenshot_20170825-222527.png)

![Right Side](./screenshots/Stage-1/Screenshot_20170825-222537.png)

* #### User Test
Two sample questions I asked in my first test were:
 1. **Describe the environment. What feeling does it give off?**

   It's dark and mysterious. The purple light on the orbs makes them seem special somehow. They seem magical in a room of shadows.

 2. **How about its size?**

   It feels just right, not too big, and not too small. Its size helps me to focus on the orbs which must be the central aspect of the scene. Any bigger and it would be difficult to focus on them because I would want to look around a lot. Any smaller and I would feel cramped.

 The user seemed to like how my game was starting out, so it was time to move onto Stage 2.

### Stage 2

In this stage, I tested out my UI for the Start Panel that the user sees at the beginning of the game, as well as my Restart Panel, which the user sees at the end of the game to restart it after completing the puzzle. I essentially verified that the UI of each was clear and that only one would display at a time.

![Start Panel](./screenshots/Stage-2/Screenshot_20170828-221440.png)

![Restart Panel](./screenshots/Stage-2/Screenshot_20170828-221452.png)

* #### User Test
The user felt that the panels were clear and thus had no confusion over their usage.

### Stage 3

Now it was time to develop the motion mechanic in which the user moves from the start position, to the gameplay position, and ends at the restart position. I had to make certain that the movement speed felt smooth, mainly to help prevent potential simulator sickness, since not everyone deals with VR experiences in the same way. A sample of my motion mechanic can be found here:

[Motion Mechanic Video on YouTube](https://youtu.be/LhbmNCU8yco)

* #### User Test
The user noted that he moved fine through the level and that he didn't feel sick. He said he moved smoothly, with no jerkiness. However, the user also claimed that he felt like he was too close to the panels and to the puzzle globes, so I adjusted them until he felt like they were in the best position. After those changes, I felt confident I could move on to the final stage in my development.

### Final Stage

To conclude Puzzler's development, I finally added the logic to make the orbs light up in a random pattern, which the user has to repeat to beat the puzzle. I also added sound effects on the orbs and panel buttons for feedback and ambient audio for mood. The orbs also change color when the user gazes at them for feedback purposes. Finally, once the user wins the puzzle and clicks on the Restart Panel, he or she transitions back to the starting point again, instead of abruptly being teleported back to it, like in the last iteration of my game.

![Start](./screenshots/final/Screenshot_20170905-020636.png)

![In Shack](./screenshots/final/Screenshot_20170905-020647.png)

![Choosing Orb](./screenshots/final/Screenshot_20170905-021421.png)

![End](./screenshots/final/Screenshot_20170905-020845.png)

* #### User Test
I lowered the heights of the orbs to bring them down more to eye level, since the user felt he had to crane his neck too much upwards to gaze at the top row of orbs. He felt the panels were too high, as well, so I lowered them a little. I also disabled the orbs when the user beats the puzzle, since he didn't like that when he moved forwards or backwards he traveled directly through them, which seemed odd. I had to agree. I also added music that plays when the player wins.

---

## Final Result

And, without further ado, here is one playthrough of the final product:

[Playthrough of Final Product on YouTube](https://youtu.be/K4_CFhI6YFg)

---

## Conclusion

Now that the game is finished, I can say I learned a lot about design work. Going through developing a user persona, sketching what the game could look like, and doing multiple stages of user testing along the way helped to solidify the lessons in this course. As for the game itself, after some more work on it, such as implementing my original vision of placing the puzzle in a giant tree and adding more puzzle types, maybe it will be ready to put into an app store. We shall see.