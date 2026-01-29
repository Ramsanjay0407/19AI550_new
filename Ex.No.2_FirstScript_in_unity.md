# Ex.No: 2  Welcome Script in Unity
### DATE:29/01/2026                                                                          
### REGISTER NUMBER : 
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to Unity");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
### Output:
<img width="1920" height="1200" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/d3bf1688-e5eb-4662-9915-35b48b194de1" />
<img width="1920" height="1200" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/59ae6800-413b-43fe-92b7-9373b054807f" />



### Result:
Thus the welcome script was printed on Console Window  sucessfully.

