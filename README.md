# NanoflowCommonsMxTechies
Javascript Action for Native application.

**Description**
Additional JavaScript actions geared around retrieving data in Native apps using Mendix Client API. Also Additional stuff that can be quite usable in other situations as well. The individual actions are documented in the Below.



**Typical usage scenario**
Mendix Native apps.

 

To retrieve over an association from Owner:

Use the object should own (have the dot) for the reference set using NanoflowCommonsMxTechies.RefSet_RetrieveFromOwner
Use the name of the reference set, including the module. i.e. MyFirstModule.Parent_Child

To retrieve over an association From Reference:

Use the object should own (have the dot) for the reference set using NanoflowCommonsMxTechies.RefSet_RetrieveFromReference
Use the name of the reference set, including the module. i.e. MyFirstModule.Parent_Child

To retrieve over an many-to-many association (Add List and Remove List):

Use the object with the reference set you want to add using NanoflowCommonsMxTechies.RefSet_Add_List
Use the list of objects to add to the reference set

Use the object with the reference set you want to remove using NanoflowCommonsMxTechies.RefSet_Remove_List
Use the list of objects to remove from the reference set, if found

To retrieve over an many-to-many association (Add Object and Remove Object):

Use the object with the reference set you want to add using NanoflowCommonsMxTechies.RefSet_Add_Single
Use the object to add to the reference set

Use the object with the reference set you want to remove using NanoflowCommonsMxTechies.RefSet_Remove_Single
Use the object to remove from the reference set, if found


To retrieve over an many-to-many association (Reset List):

Use the object with the reference set you want to Reset using NanoflowCommonsMxTechies.RefSet_Set
Use the list of object to set as the reference set.

To retrieve over an many-to-many association (Clear List):

Use the object with the reference set you want to clear using NanoflowCommonsMxTechies.RefSet_Clear







**Features and limitations**
Available actions:

Retrieve From Owner
Retrieve From Reference
ReferenceSetList(add,remove)
ReferenceSetObject(add,remove)
ReferenceSetList(Reset,clear)

