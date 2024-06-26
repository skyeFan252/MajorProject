# IDEA9103 Creative coding Individual Project

### Instructions

You may click anywhere on the screen to play the music and start the music visualisation effects immediately. Click again to pause and stop the music visualisation effects.

### Each group member's task

One of my teammates chose the **Perlin noise and randomness** method. She plans to animate the grasses to make them move around and change colour like jellyfishes. Another teammate chose the **User Input** method. He plans to add mouse drag interactions, the user can use the mouse to drag the grass. It should be noted that while I was writing this document, neither of my teammates had finished their projects, so these are only their design plans, their final work might be different from their plans. I chose the **Audio** method, using the music level parameter to animate the shape and colour of the grasses. All of our individual projects are unique and different from each other.

### Inspirations

![Yayoi Kusama's work](assets/work.jpg)
_Yayoi Kusama's work_

I was inspired by Yayoi Kusama's polka dot work, as shown in the image above (Manual Jakarta, 2018), featuring a black background with colourful polka dots. Inspired by this, I changed the background of my group project design to black, the dots to white, and made the grass colourful. The colour of the grass changes with the sound. The black background enhances the contrast with the white dots and the colourful grass, creating a visually striking effect.

![Original design of group work](assets/Screenshot0.png)
_Original design of the group work_

![Individual's design screenshot 1](assets/Screenshot1.png)
_Individual's design screenshot 1_

![Individual's design screenshot 2](assets/Screenshot2.png)
_Individual's design screenshot 2_

![Individual's design screenshot 3](assets/Screenshot3.png)
_Individual's design screenshot 3_

![Individual's design screenshot 4](assets/Screenshot4.png)
_Individual's design screenshot 4_

Reference:
Manual Jakarta, 2018. _Museum Macan Yayoi Kusama_. [online] Available at: <https://manual.co.id/wp-content/uploads/2018/05/Museum-Macan-Yayoi-Kusama-20-980x719.jpg> [Accessed 31 May 2024].

### Project explanations

- Task 1: Add the song.
  - Preload the song to the project.
  - Mouse interaction is added so when i click on the screen, the music and the corresponding visualisation effects will be played or paused.
- Task 2: Add music visualisation effects
  - Get the current sound level by analyzer.getLevel().
  - Calculate the Coefficient to scale the length of the curves based on the current sound level.
  - Map the sound level to determine the hue values of the colour of the grasses.
  - Therefore, the length and colour of the curves of the grass will change according to the current level of the music.
- Task 3: Adjust the background visual effects.
  - Adjust the background colour to the black colour to highlight the colourful music visualisations.
  - Adjust the background dots to the white colour and make them smaller in size.
