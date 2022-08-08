# Unity Focused on C#

#### You already understand your way around Unity. How to create gameobjects, using the q,w,e,r,t,y keys to manipulate gameobjects. You know how to assign scripts to gameobjects in Unity. I will not cover every single aspect of Unity, only the C# part. Honestly, this is to reinforce my knowledge of C# in Unity.

###### Create a new 3D scene, place a cube in game, create a script called variables, assign it to the cube.


### Variables
##### Items Used: common variables in C#, Unity, Debug.Log(), [SerializeField];

---

Variables are containers that store data, could be an animation could be a number.

#### Common variable types:
int, string, float, bool.

#### Unity specific variables:
GameObject, Animation, AudioSource

---

#### Common variable types:

  int first = 1; // no decimal allowed

  string greeting = "hi";

  float speed = 1.5f; //don't forget the f

  bool isActive = false; // true or false
  
  Debug.Log(first); // first can be replaced with any variable above
  
  - TRY each variable and print it out through Debug.Log(); You can see your result in the console window.
  
  //INSERT DIAGRAM HERE//  
  
  ##### MINI-PROJECTS
  
  a) Create any variable and use Debug.Log(). Use different types and see what you see in Console.
  
  b) really nothing crazy here, basic printing and variables. **Move on.**
  
  
---

#### Unity Example

Almost anything in Unity can be assigned to a variables if available in the framework

Transform playerTransform; // accesses the transform of an object (the position x,y,z)

Gameobject playerLaser; // access the gameobject within the scene

Animation playerAnim; // access the animation attached or assigned

Unity has a cool feature called [SerializeField]. This attribute allowed you to drag and drop that variable type into a field within the Unity GUI.

  ie. [SerializeField] GameObject playerLaser;

//INSERT DIAGRAM HERE//

- TRY creating various Unity specific variables and serialize them to see how it looks like in Unity.

##### MINI-PROJECTS

a)  Create various unity variables, serialize them, and see what it's like

---

###PROJECT TIME

##### Idea keeps evolving. It's getting RPG'ish. Create a script where your cube will use everyone of these IN GAME.

#### ITEMS AVAILABLE: common C# and Unity variables, serializefield, debug.log();

``` example here, i am burned blah.
