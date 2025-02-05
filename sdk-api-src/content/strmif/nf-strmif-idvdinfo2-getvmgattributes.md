---
UID: NF:strmif.IDvdInfo2.GetVMGAttributes
title: IDvdInfo2::GetVMGAttributes (strmif.h)
description: The GetVMGAttributes method retrieves attributes of all video, audio, and subpicture streams for the Video Manager Menu.
helpviewer_keywords: ["GetVMGAttributes","GetVMGAttributes method [DirectShow]","GetVMGAttributes method [DirectShow]","IDvdInfo2 interface","IDvdInfo2 interface [DirectShow]","GetVMGAttributes method","IDvdInfo2.GetVMGAttributes","IDvdInfo2::GetVMGAttributes","IDvdInfo2GetVMGAttributes","dshow.idvdinfo2_getvmgattributes","strmif/IDvdInfo2::GetVMGAttributes"]
old-location: dshow\idvdinfo2_getvmgattributes.htm
tech.root: dshow
ms.assetid: ddb1059a-e1c5-4506-b565-fd871ad8385f
ms.date: 4/26/2023
ms.keywords: GetVMGAttributes, GetVMGAttributes method [DirectShow], GetVMGAttributes method [DirectShow],IDvdInfo2 interface, IDvdInfo2 interface [DirectShow],GetVMGAttributes method, IDvdInfo2.GetVMGAttributes, IDvdInfo2::GetVMGAttributes, IDvdInfo2GetVMGAttributes, dshow.idvdinfo2_getvmgattributes, strmif/IDvdInfo2::GetVMGAttributes
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IDvdInfo2::GetVMGAttributes
 - strmif/IDvdInfo2::GetVMGAttributes
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Strmiids.lib
 - Strmiids.dll
api_name:
 - IDvdInfo2.GetVMGAttributes
---

# IDvdInfo2::GetVMGAttributes


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>GetVMGAttributes</code> method retrieves attributes of all video, audio, and subpicture streams for the Video Manager Menu.

## -parameters

### -param pATR [out]

Pointer to a [DVD_MenuAttributes](/windows/desktop/api/strmif/ns-strmif-dvd_menuattributes) structure that receives the attributes.

## -returns

Returns one of the following <b>HRESULT</b> values.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
Invalid argument.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_UNEXPECTED</b></dt>
</dl>
</td>
<td width="60%">
The <a href="/windows/desktop/DirectShow/dvd-navigator-filter">DVD Navigator</a> is not initialized.

</td>
</tr>
</table>

## -remarks

The Video Manager Menu is not associated with any particular title number.

## -see-also

<a href="/windows/desktop/DirectShow/dvd-applications">DVD Applications</a>



<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/strmif/nn-strmif-idvdinfo2">IDvdInfo2 Interface</a>