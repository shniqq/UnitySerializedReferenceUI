# UnitySerializedReferenceUI
The UI for Unity's SerealizedReference attribute. It allows to change the instance type of field right in editor.

Project is provided under Mit license which you can find in inner main folder ("SerializedReferenceUI")

Known limitations.
Custom property drawer has no effect. Becouse property is drawn from custom attribute drawer custom property drawer is not applied (unity default behaviour).

Known Issues of serialized reference. 
Renaming used type can produce data loss and throws unknown managed type exception. This is unity's bug.


Future plans:
Possibly
- copy / paste.
- menu with searchbar.
