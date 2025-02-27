---
UID: NF:vidcap.ICameraControl.getRange_Tilt
title: ICameraControl::getRange_Tilt (vidcap.h)
description: The getRange_Tilt method returns the range of tilt angles supported by the camera.
helpviewer_keywords: ["ICameraControl interface [DirectShow]","getRange_Tilt method","ICameraControl.getRange_Tilt","ICameraControl::getRange_Tilt","ICameraControlgetRange_Tilt","dshow.icameracontrol_getrange_tilt","getRange_Tilt","getRange_Tilt method [DirectShow]","getRange_Tilt method [DirectShow]","ICameraControl interface","vidcap/ICameraControl::getRange_Tilt"]
old-location: dshow\icameracontrol_getrange_tilt.htm
tech.root: dshow
ms.assetid: d48920cf-677e-4014-a998-426bb45d1b46
ms.date: 12/05/2018
ms.keywords: ICameraControl interface [DirectShow],getRange_Tilt method, ICameraControl.getRange_Tilt, ICameraControl::getRange_Tilt, ICameraControlgetRange_Tilt, dshow.icameracontrol_getrange_tilt, getRange_Tilt, getRange_Tilt method [DirectShow], getRange_Tilt method [DirectShow],ICameraControl interface, vidcap/ICameraControl::getRange_Tilt
req.header: vidcap.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2 [desktop apps only]
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
 - ICameraControl::getRange_Tilt
 - vidcap/ICameraControl::getRange_Tilt
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
 - ICameraControl.getRange_Tilt
---

# ICameraControl::getRange_Tilt


## -description

The <code>getRange_Tilt</code> method returns the range of tilt angles supported by the camera.

## -parameters

### -param pMin [out]

Receives the minimum tilt angle, in units of 1 arc second.

### -param pMax [out]

Receives the maximum tilt angle, in units of 1 arc second.

### -param pSteppingDelta [out]

Receives the smallest step between settings.

### -param pDefault [out]

Receives the default tilt angle, in units of 1 arc second.

### -param pCapsFlag [out]

Receives one or more flags. See <a href="/previous-versions/windows/desktop/api/strmif/ne-strmif-cameracontrolflags">CameraControlFlags</a>.

## -returns

Returns an <b>HRESULT</b> value.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/vidcap/nn-vidcap-icameracontrol">ICameraControl Interface</a>