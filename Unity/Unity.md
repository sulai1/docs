#Unity

#Events
To use your custom Events you simply have to declare a class that inherits UnityEvent and make it serializable with the [[Serializble]] Attribute.
You can then add functions to it as you would do it with the standard UI-Objects.

#Attributes
Attributes in C# are like java annotations. You can use Unity Attributes to customize your gameobjects inspector and add advanced functionality.
See the list of Attributes and there usage at [Unity Documentation](https://docs.unity3d.com/ScriptReference/) under UnityEditor -> Attributes.
* Use [[SerializeField]] to make private Fields visible in the inspectors, public fields are visible in the inspector by default.
* Use [[[RequireComponent(typeof(Object))]]] to ensure that this Gameobject has such a component attached
* Use [[Tooltip("Tooltip Message")]] to add a tooltip message to the field


