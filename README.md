# Return-
 ElseIf StringRegExp($sStr, '^[^[:cntrl:]x7F]+$') Then         $iH = 6.5699     ElseIf _StringRegExp($sStr, '^[^[:cntrl:]x7Fx81x8Dx8Fx90x9D]+$') Then         $iH = 7.7682     EndIf     Return $iH * $iLen EndFunc
