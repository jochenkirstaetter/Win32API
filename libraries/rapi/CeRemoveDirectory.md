[<img src="../../images/home.png"> Home ](https://github.com/VFPX/Win32API)  

## Function name : CeRemoveDirectory
Group: Remote Application Programming (RAPI) - Library: rapi    
***  


#### This function deletes an existing empty directory.
***  


## Code examples:
[Pocket PC: custom RAPI class for operating with files and folders on mobile device](../../samples/sample_448.md)  

## Declaration:
```foxpro  
BOOL CeRemoveDirectory(
  LPCWSTR lpPathName
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER CeRemoveDirectory IN rapi;
	STRING lpPathName  
```  
***  


## Parameters:
lpPathName 
[in] Long pointer to a null-terminated string that specifies the path of the directory to be removed.  
***  


## Return value:
Nonzero indicates success.  
***  


## Comments:
The path must specify an empty directory, and the calling process must have delete access to the directory.   
  
See also CeCreateDirectory, CeCreateFile and CeDeleteFile functions.  
  
***  

