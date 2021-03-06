[<img src="../../images/home.png"> Home ](https://github.com/VFPX/Win32API)  

## Function name : CLSIDFromString
Group: COM - Library: ole32    
***  


#### Converts a string generated by the StringFromCLSID function back into the original CLSID.
***  


## Code examples:
[Custom GDI+ class](../../samples/sample_450.md)  
[How to generate GUID values](../../samples/sample_456.md)  
[Enumerating devices installed on the local machine](../../samples/sample_545.md)  

## Declaration:
```foxpro  
HRESULT CLSIDFromString(
  LPOLESTR lpsz,
  LPCLSID pclsid
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER CLSIDFromString IN ole32;
	STRING   lpsz,;
	STRING @ pclsid
  
```  
***  


## Parameters:
lpsz 
[in] Pointer to the string representation of the CLSID. 

pclsid 
[out] Pointer to the CLSID on return.   
***  


## Return value:
Returns NOERROR (0) if the CLSID was obtained successfully.   
***  


## Comments:
<div class="precode">LOCAL cBuffer, iidImageList  
  
cBuffer = REPLICATE(CHR(0), 16)  
iidImageList = "{46EB5926-582E-4017-9FDF-E8998DAA0950}"  
  
= CLSIDFromString(STRCONV(iidImageList,5), @cBuffer)  
? cBuffer  
</div>  
See also: StringFromGUID2   
  
***  

