[<img src="../../images/home.png"> Home ](https://github.com/VFPX/Win32API)  

## Function name : SwitchDesktop
Group: Window Station and Desktop - Library: user32    
***  


#### Makes a desktop visible and activates it. This enables the desktop to receive input from the user.
***  


## Code examples:
[How to prevent users from accessing the Windows Desktop and from switching to other applications](../../samples/sample_492.md)  

## Declaration:
```foxpro  
BOOL SwitchDesktop(
	HDESK hDesktop
);
  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER SwitchDesktop IN user32;
	INTEGER hDesktop  
```  
***  


## Parameters:
hDesktop 
[in] Handle to the desktop to be made visible and active. This handle is returned by the CreateDesktop and OpenDesktop functions.  
***  


## Return value:
If the function succeeds, the return value is nonzero.  
***  


## Comments:
See also: CreateDesktop, OpenDesktop   
  
***  

