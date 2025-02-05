---
UID: NF:qnetwork.IAMNetShowConfig.get_EnableHTTP
title: IAMNetShowConfig::get_EnableHTTP (qnetwork.h)
description: The get_EnableHTTP method queries whether HTTP-type streaming is enabled.
helpviewer_keywords: ["IAMNetShowConfig interface [DirectShow]","get_EnableHTTP method","IAMNetShowConfig.get_EnableHTTP","IAMNetShowConfig::get_EnableHTTP","IAMNetShowConfigget_EnableHTTP","dshow.iamnetshowconfig_get_enablehttp","get_EnableHTTP","get_EnableHTTP method [DirectShow]","get_EnableHTTP method [DirectShow]","IAMNetShowConfig interface","qnetwork/IAMNetShowConfig::get_EnableHTTP"]
old-location: dshow\iamnetshowconfig_get_enablehttp.htm
tech.root: dshow
ms.assetid: 29495a89-644f-4c55-a740-efb0cbf6d581
ms.date: 4/26/2023
ms.keywords: IAMNetShowConfig interface [DirectShow],get_EnableHTTP method, IAMNetShowConfig.get_EnableHTTP, IAMNetShowConfig::get_EnableHTTP, IAMNetShowConfigget_EnableHTTP, dshow.iamnetshowconfig_get_enablehttp, get_EnableHTTP, get_EnableHTTP method [DirectShow], get_EnableHTTP method [DirectShow],IAMNetShowConfig interface, qnetwork/IAMNetShowConfig::get_EnableHTTP
req.header: qnetwork.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IAMNetShowConfig::get_EnableHTTP
 - qnetwork/IAMNetShowConfig::get_EnableHTTP
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Qnetwork.h
api_name:
 - IAMNetShowConfig.get_EnableHTTP
---

# IAMNetShowConfig::get_EnableHTTP


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>get_EnableHTTP</code> method queries whether HTTP-type streaming is enabled.

## -parameters

### -param pEnableHTTP

Pointer to a variable that receives a Boolean value.

## -returns

If the method succeeds, it returns S_OK. If it fails, it returns an <b>HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/api/qnetwork/nn-qnetwork-iamnetshowconfig">IAMNetShowConfig Interface</a>