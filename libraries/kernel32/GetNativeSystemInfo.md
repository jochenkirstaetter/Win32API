
## Function name : GetNativeSystemInfo
Group: System Information - Library: kernel32    
***  


#### Retrieves information about the current system to an application running under WOW64. 
***  


## Declaration:
```foxpro  
void WINAPI GetNativeSystemInfo(
  __out  LPSYSTEM_INFO lpSystemInfo
);
  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE GetNativeSystemInfo IN kernel32;
	STRING @lpSystemInfo
  
```  
***  


## Parameters:
lpSystemInfo 
A pointer to a SYSTEM_INFO structure that receives the information.
  
***  


## Return value:
This function does not return a value.  
***  


## Comments:
If the function is called from a 64-bit application, it is equivalent to the GetSystemInfo function.  
  
See also: GetSystemWow64Directory   
  
***  
