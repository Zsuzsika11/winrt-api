---
-api-id: M:Windows.Devices.PointOfService.SlipPrintJob.PrintCustomAlignedBitmap(Windows.Graphics.Imaging.BitmapFrame,System.UInt32)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public void PrintCustomAlignedBitmap(Windows.Graphics.Imaging.BitmapFrame bitmap, System.UInt32 alignmentDistance)
-->

# Windows.Devices.PointOfService.SlipPrintJob.PrintCustomAlignedBitmap

## -description
Adds an instruction to the print job to print the specified bitmap at the specified distance from the leftmost print column on the slip printer station.

## -parameters
### -param bitmap
Information about the bitmap that you want to print.

### -param alignmentDistance
The distance from the leftmost print column to the start of the bitmap, expressed in the unit of measurement indicated by the [ClaimedPosPrinter.MapMode](claimedposprinter_mapmode.md) property.

## -remarks

## -examples

## -see-also
[PrintCustomAlignedBitmap(BitmapFrame, UInt32, UInt32)](slipprintjob_printcustomalignedbitmap_417648213.md), [PrintBitmap(BitmapFrame, PosPrinterAlignment)](slipprintjob_printbitmap_1311643772.md), [PrintBitmap(BitmapFrame, PosPrinterAlignment, UInt32)](slipprintjob_printbitmap_1103111072.md), [ClaimedPosPrinter.MapMode](claimedposprinter_mapmode.md)