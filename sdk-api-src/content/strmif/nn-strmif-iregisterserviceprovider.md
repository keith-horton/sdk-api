---
UID: NN:strmif.IRegisterServiceProvider
title: IRegisterServiceProvider (strmif.h)
description: The IRegisterServiceProvider interface registers an object as a service with the Filter Graph Manager. For more information, see IRegisterServiceProvider::RegisterService.
helpviewer_keywords: ["IRegisterServiceProvider","IRegisterServiceProvider interface [DirectShow]","IRegisterServiceProvider interface [DirectShow]","described","IRegisterServiceProviderInterface","dshow.iregisterserviceprovider","strmif/IRegisterServiceProvider"]
old-location: dshow\iregisterserviceprovider.htm
tech.root: dshow
ms.assetid: 1097fa4c-d81d-4268-8492-c0d9f4888733
ms.date: 4/26/2023
ms.keywords: IRegisterServiceProvider, IRegisterServiceProvider interface [DirectShow], IRegisterServiceProvider interface [DirectShow],described, IRegisterServiceProviderInterface, dshow.iregisterserviceprovider, strmif/IRegisterServiceProvider
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
 - IRegisterServiceProvider
 - strmif/IRegisterServiceProvider
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
 - IRegisterServiceProvider
---

# IRegisterServiceProvider interface


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>IRegisterServiceProvider</code> interface registers an object as a service with the <a href="/windows/desktop/DirectShow/filter-graph-manager">Filter Graph Manager</a>. For more information, see <a href="/windows/desktop/api/strmif/nf-strmif-iregisterserviceprovider-registerservice">IRegisterServiceProvider::RegisterService</a>.

## -inheritance

The <b>IRegisterServiceProvider</b> interface inherits from the <a href="/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IRegisterServiceProvider</b> also has these types of members:

