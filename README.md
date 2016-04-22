# Swift Progress Dialog
![asdasdasd](https://cloud.githubusercontent.com/assets/18617350/14747602/ceec4ca4-08bd-11e6-9cdc-00b5f7225eb4.jpg)

##Get Properties
```swift
GetDialogColor() -> UIColor
GetDialogBackground() -> UIColor
GetDialogSize() -> Size
GetOpacity() -> Float
GetBorderColor() -> UIColor
GetBorderWidth() -> Float
GetBorderRadius() -> Float
```
###Set Properties
```swift
SetDialogColor(color: UIColor)
SetDialogBackground(color: UIColor)
SetDialogSize(size: Size)
SetOpacity(opacity: Float)
SetBorderColor(color: UIColor)
SetBorderWidth(width: Float)
SetBorderRadius(radius: Float)
```
###Bonus
```swift
class Size {
    internal var Width:CGFloat!
    internal var Height:CGFloat!
    init(width:CGFloat, height:CGFloat) {
        Width = width;
        Height = height
    }
}
```
##How to use?
Swift progress dialog code library
```swift
  var progress = ProgressDialog(delegate: self)
  //progress.Show(animate:Bool, mesaj: String)
 progress.Show(true, mesaj: "")
```
or
```swift
progress.Show(true, mesaj: "Loading")
```
and hide dialog.
```swift
progress.Close()
```
Powerd by fukoapps.com
