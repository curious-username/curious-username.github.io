# Unity Focused C#
# 1
### Variables
##### Items Used: common variables in most languages, Unity, and Debug.Log();

---

Variables are containers that store data

#### Common variable types:
int, string, float, bool.

---

#### Example 1:

  int first = 1;

  string greeting = "hi";

  float speed = 1.5f;

  bool isActive = false;
  
  ![image](https://user-images.githubusercontent.com/62562456/183476627-a8b1ec0d-3c14-48e2-9f91-ee10f2f83b68.png)


  Debug.Log(first); // first can be replaced with any variable above
  
---

#### Example 2
Almost anything in Unity can be assigned to a variables if available in the framework

Transform playerTransform; // accesses the transform of an object (the x,y,z)
Gameobject playerLaser; // access the gameobject within the scene
Animation playerAnim; // access the animation attached or assigned

