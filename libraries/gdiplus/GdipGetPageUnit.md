[<img src="../../images/home.png"> Home ](https://github.com/VFPX/Win32API)  

## Function name : GdipGetPageUnit
Group: GDI+ Graphics - Library: gdiplus    
***  


#### Returns an element of the Unit enumeration that indicates the unit of measure currently set for this Graphics handle.
***  


## Declaration:
```foxpro  
GpStatus WINGDIPAPI GdipGetPageUnit(
	GpGraphics *graphics,
	GpUnit *unit
)  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER GdipGetPageUnit IN gdiplus;
	INTEGER graphics,;
	INTEGER @unit  
```  
***  


## Parameters:
graphics
[in] Handle to the Graphics object.

unit
[out] Element of the Unit enumeration that specifies the unit of measure currently set for this Graphics handle.  
***  


## Return value:
Returns GpStatus value, 0 means success.  
***  


## Comments:
<a href="http://msdn.microsoft.com/en-us/library/ms534405(VS.85).aspx">Unit Enumerated Type</a>  
<div class="precode">typedef enum {  
	UnitWorld = 0,  
	UnitDisplay = 1,  
	UnitPixel = 2,  
	UnitPoint = 3,  
	UnitInch = 4,  
	UnitDocument = 5,  
	UnitMillimeter = 6  
} Unit;</div>  
1 Point Unit = 1/72 inch.  
1 Document Unit = 1/300 inch.  
  
See also: GdipSetPageUnit   
  
***  

