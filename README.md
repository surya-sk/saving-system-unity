# saving-system-unity
A generic saving system for games made in the Unity Engine. I initially wrote this for one of my games but decided to go with a system more specific to my game. 

To implement this, 
1. Paste the files in this repository into the Scripts folder
2. Add the interface to each class you have saveable objects in
3. Implement the methods in the interface (Visual Studio will warn you)
4. You will see 2 methods, Save and Load
5. return the serialiazable object you want to save in the Save() method
6. Assign the object in the parameter of the Load() method to the serializable object. Be sure to cast it
7. Trigger the Save() and Load() methods however you see fit for your game 
