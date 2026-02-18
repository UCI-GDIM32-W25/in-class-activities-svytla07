# GDIM32 In Class Activities
## W1
### Activity 1: 

Playtest all iterations of the game, not just the "finished" version. Make sure to double check if the link to your game works. 



### Activity 2: 

1. 10

2. 2

3. It puts a message in the consolde when the method PrintMessage runs.

4. MonoBehavior

5.  Prints x = 10 in the console.

6. Parameters and arguments that are passed into methods.

7. Transform.Translate(_direction) is invalid and will not work

8. _playerTransform.Translate(_direction)



### Activity 3:

[MG1 Break-Down Document](https://docs.google.com/document/d/1MR5s2MD1t6kFIP1PlwggtskA_hNJPmX335sJPT-4Uuw/edit?usp=sharing)

## W2
### Activity 1:

<img width="847" height="640" alt="Screenshot 2026-01-13 at 5 59 40 PM" src="https://github.com/user-attachments/assets/65bed15d-b441-4562-a4d7-78812d229635" />

### Activity 2: 

[MG2 Commit](https://github.com/UCI-GDIM32-W25/mg2-oop-review-svytla07/commit/244ebcda222947fc34c24316996723783ada5ff5)

I created the canvas and the player object as well as made the player script and a s cript for the GameController and for the HUD. I made sure to attach the player script to the player object and then I added a rigidbody and capsule collider that i made sure to assign to variables that I created in the script. 

## W3
### Activities 0-2: 
Mira Liu

### Activity 3: 
<img width="833" height="623" alt="Screenshot 2026-01-20 at 6 32 05 PM" src="https://github.com/user-attachments/assets/36b05d12-c2fb-4b5b-8a3f-7afba17a0561" />

## W4
### Activity 0:
Mira Liu

### Activity 1:
When we add mutiple objects with the locator script component, after we run the game it gets rid of the locator script component on all of the objects except one since the code in the class is making it so there is only one instance of the locator script component. 

### Activity 2:
<img width="844" height="633" alt="Screenshot 2026-01-27 at 6 34 13 PM" src="https://github.com/user-attachments/assets/5a8779f5-9289-4b07-8d4f-c1f309ab2524" />

### Activity 3:
[MG4 Commit](https://github.com/svytla07/HW4/commit/bbd61fc867360404001fd4a2b2b73c0de721ad42)

I created the project and imported spritesheets which I then spilt in the Sprite Editor to make them usuable. Then I created a player object and gave it a sprite renderer component and a rigidbody2d component. I also made a ground object and gave it a boxcollider component. I also made two prefabs for the top and bottom parts of the platform and gave them spriterenderer components. Lastly I made a player script and attached it to the player object, a platform script that I attached to platform prefabs and a game controller script that I attached to an empty game object for the game controller. 

## W5
### Activity 1:

I think I would keep it very similar as it makes sense to have items be able to inherit from an parent class since all the items will share at least one attribute in common. However I think it might be easier to then have two parent classes that inherit from the item class, Breakable and NonBreakable so that the breakable items can be grouped together and the nonbreakable ones could be too.

### Activity 2:

The class that represents the model is the PlayerW5Demo2 class. The class that represents the view is EnemyStats and the class that represents the controller is the ItemW5Demo2 class.

### Activity 3:

#### Scenario 1

Nemo could use prefabs to represent the beats in code and they could have a script attached to it and have a sprite. The type of beat could be represented with an enum and a Finate State Machince could be used to determine whether the beat was hit on time or missed. They could use scriptableobjects too.

#### Scenario 2

Leo could use inheritance and polymorphism to create the agents. He could make a parent class for all of the agents where the common behavior is stored such as movement, shooting, and getting hurt. Then for each agent he could make a child class that inherits from the parent class and thats where all the unique attacks are stored as well as the specific animations and different modes of movement that override the parent class if needed. A finate state machine could be used to determine if a player is alive or dead or is a round is ongoin or over and whether or not it was a loss/win.

#### Scenario 3

Willow could use a Finate State Machine to represent the growth of the plant and the different stages of plant growth.

### Activity 4:

Attendence: Mira Liu, Beiduo Jin, Luis Alberto Jr. Chavarin

Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/1KHzQUOe_9pFKEXuYQW5sSsAkWXeVOPrjhrICp1-lh7M/edit?usp=sharing)

## W6

Talk: Game Writing, Cory Lanham

Notes:
- Game writers do not make all the creative choices in the story
- Collaboration is key in game writing
- In house writers can only work on one project because of conflicting interests
- In house writers are going to be in a a lot of meetings with other roles that have a say in the creative process
- A high level narrative summary is created during pre production
- It has all key plot points of the story
- Pre production will also be where you come up with narrative delivery methods which are also known as how the story will be told
- During production is when the cinematic scripts are written and will also be rewritten a lot
- Systemic dialogue includes dialogue barks, ambient dialogue, and specialized dialogue systems 
- Post production is a lot of final edits and revisions and fixing any mistakes that might have been overlooked in the other stages
- To break in the game writing industry, you might have to look for work in other departments
- QA is most common way people break in to the industry
- In house QA > Outsourced team
- Contract/Project hire only part of the team for the the length of a project and then you’ll probably get let go
- Internships are also another common way
- Look for opportunities to help the narrative team
- Build your portfolio
- Make games by yourself or with others (better with others since it shows you can work with a team)
- Develop skills
- Participate in GameJams
- Networking/Making connections

## W7

### Activity 1:

Notes:
- raycast is an arrow being thrown into the scene and seeing if it hits something
- raycasting can work as a line of sight
- the color can be changed to see better
- raycasting can be attached to an object

### Activity 2:

Attendence: Mira Liu, Beiduo Jin, Luis Chavarin

### Activity 3:

### Activity 4:

https://trello.com/invite/b/69951d12a3e1a6e8a0974e38/ATTI2f2d83280b373b2dd9fb05985fb2f01fF7648ECA/-

### Activity 5:

https://github.com/svytla07/GDIM32-Final/commit/b0d883744f7acac127a8612c9430272d58d80a35

I created the repo, made the project in unity and created folders to organize the scripts, audio and sprites. I also made a player script. 