# pbqrcode
powerbuilder(pb)生成二维码
通过调用MakeQRBarcode.dll生成二维码
pb10调用     Subroutine Make(string ucData, long nDataLen,long nErrLevel,long nMask, integer nBarEdition,  string szBmpFileName, long nScale) library "MakeQRBarcode.dll" alias for "Make;Ansi"
pb9调用     Subroutine Make(string ucData, long nDataLen,long nErrLevel,long nMask, integer nBarEdition,  string szBmpFileName, long nScale) library "MakeQRBarcode.dll"
