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
  
  
  
---

#### Unity Example

Almost anything in Unity can be assigned to a variables if available in the framework

Transform playerTransform; // accesses the transform of an object (the position x,y,z)
Gameobject playerLaser; // access the gameobject within the scene
Animation playerAnim; // access the animation attached or assigned

You can drag and drop items 

//INSERT DIAGRAM HERE//

- TRY creating each. 

---

###PROJECT TIME

You know variable basics for both unity and C#. You know 
