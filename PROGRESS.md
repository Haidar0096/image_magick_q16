### The purpose of this file is to track the progress of implementing the bindings to the ImageMagick C API.

# [MagickWand Methods](https://imagemagick.org/script/magick-wand.php#:~:text=are%20found%20here%3A-,Magick%20Wand%20Methods,-Set%20or%20Get)

- [x] ClearMagickWand
- [x] CloneMagickWand
- [x] DestroyMagickWand
- [x] IsMagickWand
- [x] MagickClearException
- [x] MagickGetException
- [x] MagickGetExceptionType
- [x] MagickGetIteratorIndex
- [x] MagickQueryConfigureOption
- [x] MagickQueryConfigureOptions
- [x] MagickQueryFontMetrics
- [x] MagickQueryMultilineFontMetrics
- [x] MagickQueryFonts
- [x] MagickQueryFormats
- [x] MagickRelinquishMemory (private)
- [x] MagickResetIterator
- [x] MagickSetFirstIterator
- [x] MagickSetIteratorIndex
- [x] MagickSetLastIterator
- [x] MagickWandGenesis (private)
- [x] MagickWandTerminus (private)
- [x] NewMagickWand
- [ ] NewMagickWandFromImage
- [x] IsMagickWandInstantiated

# [Set or Get Magick Wand Properties](https://imagemagick.org/script/magick-wand.php#:~:text=Set%20or%20Get%20Magick%20Wand%20Properties)

- [x] MagickDeleteImageArtifact
- [x] MagickDeleteImageProperty
- [x] MagickDeleteOption
- [x] MagickGetAntialias
- [x] MagickGetBackgroundColor
- [x] MagickGetColorspace
- [x] MagickGetCompression
- [x] MagickGetCompressionQuality
- [x] MagickGetCopyright
- [x] MagickGetFilename
- [x] MagickGetFont
- [x] MagickGetFormat
- [x] MagickGetFilter
- [x] MagickGetGravity
- [x] MagickGetHomeURL
- [x] MagickGetImageArtifact
- [x] MagickGetImageArtifacts
- [x] MagickGetImageProfile
- [x] MagickGetImageProfiles
- [x] MagickGetImageProperty
- [x] MagickGetImageProperties
- [x] MagickGetInterlaceScheme
- [x] MagickGetInterpolateMethod
- [x] MagickGetOption
- [x] MagickGetOptions
- [x] MagickGetOrientation
- [x] MagickGetPackageName
- [x] MagickGetPage
- [x] MagickGetPointsize
- [x] MagickGetQuantumDepth
- [x] MagickGetQuantumRange
- [x] MagickGetReleaseDate
- [x] MagickGetResolution
- [x] MagickGetResource
- [x] MagickGetResourceLimit
- [x] MagickGetSamplingFactors
- [x] MagickGetSize
- [x] MagickGetSizeOffset
- [x] MagickGetType
- [x] MagickGetVersion
- [x] MagickProfileImage
- [x] MagickRemoveImageProfile
- [x] MagickSetAntialias
- [x] MagickSetBackgroundColor
- [x] MagickSetColorspace
- [x] MagickSetCompression
- [x] MagickSetCompressionQuality
- [x] MagickSetDepth
- [x] MagickSetExtract
- [x] MagickSetFilename
- [x] MagickSetFont
- [x] MagickSetFormat
- [x] MagickSetFilter
- [x] MagickSetGravity
- [x] MagickSetImageArtifact
- [x] MagickSetImageProfile
- [x] MagickSetImageProperty
- [x] MagickSetInterlaceScheme
- [x] MagickSetInterpolateMethod
- [x] MagickSetOption
- [x] MagickSetOrientation
- [x] MagickSetPage
- [x] MagickSetPassphrase
- [x] MagickSetPointsize
- [x] MagickSetProgressMonitor
- [x] MagickSetResourceLimit
- [x] MagickSetResolution
- [x] MagickSetSamplingFactors
- [x] MagickSetSeed
- [x] MagickSetSecurityPolicy
- [x] MagickSetSize
- [x] MagickSetSizeOffset
- [x] MagickSetType

# [Magick Wand Image Methods](https://imagemagick.org/script/magick-wand.php#:~:text=Magick%20Wand%20Image%20Methods)

- [ ] GetImageFromMagickWand
- [x] MagickAdaptiveBlurImage
- [x] MagickAdaptiveResizeImage
- [x] MagickAdaptiveSharpenImage
- [x] MagickAdaptiveThresholdImage
- [x] MagickAddImage
- [x] MagickAddNoiseImage
- [x] MagickAffineTransformImage
- [x] MagickAnnotateImage
- [ ] MagickAnimateImages
- [x] MagickAppendImages
- [x] MagickAutoGammaImage
- [x] MagickAutoLevelImage
- [x] MagickAutoOrientImage
- [x] MagickAutoThresholdImage
- [x] MagickBilateralBlurImage
- [x] MagickBlackThresholdImage
- [x] MagickBlueShiftImage
- [x] MagickBlurImage
- [x] MagickBorderImage
- [x] MagickBrightnessContrastImage
- [x] MagickCannyEdgeImage
- [x] MagickChannelFxImage
- [x] MagickCharcoalImage
- [x] MagickChopImage
- [x] MagickCLAHEImage
- [x] MagickClampImage
- [x] MagickClipImage
- [x] MagickClipImagePath
- [x] MagickClutImage
- [x] MagickCoalesceImages
- [x] MagickColorDecisionListImage
- [x] MagickColorizeImage
- [x] MagickColorMatrixImage
- [x] MagickColorThresholdImage
- [x] MagickCombineImages
- [x] MagickCommentImage
- [x] MagickCompareImagesLayers
- [x] MagickCompareImages
- [x] MagickComplexImages
- [x] MagickCompositeImage
- [x] MagickCompositeImageGravity
- [x] MagickCompositeLayers
- [ ] MagickConnectedComponentsImage
- [x] MagickContrastImage
- [x] MagickContrastStretchImage
- [x] MagickConvolveImage
- [x] MagickCropImage
- [x] MagickCycleColormapImage
- [x] MagickConstituteImage
- [x] MagickDecipherImage
- [x] MagickDeconstructImages
- [x] MagickDeskewImage
- [x] MagickDespeckleImage
- [ ] MagickDestroyImage
- [ ] MagickDisplayImage
- [ ] MagickDisplayImages
- [x] MagickDistortImage
- [x] MagickDrawImage
- [x] MagickEdgeImage
- [x] MagickEmbossImage
- [x] MagickEncipherImage
- [x] MagickEnhanceImage
- [x] MagickEqualizeImage
- [x] MagickEvaluateImage
- [ ] MagickEvaluateImages
- [x] MagickExportImagePixels
- [x] MagickExtentImage
- [x] MagickFlipImage
- [x] MagickFloodfillPaintImage
- [x] MagickFlopImage
- [ ] MagickForwardFourierTransformImage
- [x] MagickFrameImage
- [x] MagickFunctionImage
- [x] MagickFxImage
- [x] MagickGammaImage
- [x] MagickGaussianBlurImage
- [x] MagickGetImage
- [x] MagickGetImageAlphaChannel
- [x] MagickGetImageMask
- [x] MagickGetImageBackgroundColor
- [x] MagickGetImageBlob
- [x] MagickGetImagesBlob
- [x] MagickGetImageBluePrimary
- [x] MagickGetImageBorderColor
- [x] MagickGetImageFeatures
- [x] MagickGetImageKurtosis
- [x] magickGetImageMean
- [x] MagickGetImageRange
- [x] MagickGetImageStatistics
- [x] MagickGetImageColormapColor
- [x] MagickGetImageColors
- [x] MagickGetImageColorspace
- [x] MagickGetImageCompose
- [x] MagickGetImageCompression
- [x] MagickGetImageCompressionQuality
- [x] MagickGetImageDelay
- [x] MagickGetImageDepth
- [x] MagickGetImageDispose
- [ ] MagickGetImageDistortion
- [ ] MagickGetImageDistortions
- [x] MagickGetImageEndian
- [x] MagickGetImageFilename
- [ ] MagickGetImageFilter [needs updating ImageMagick's version]
- [x] MagickGetImageFormat
- [x] MagickGetImageFuzz
- [x] MagickGetImageGamma
- [x] MagickGetImageGravity
- [x] MagickGetImageGreenPrimary
- [x] MagickGetImageHeight
- [x] MagickGetImageHistogram
- [x] MagickGetImageInterlaceScheme
- [x] MagickGetImageInterpolateMethod
- [x] MagickGetImageIterations
- [x] MagickGetImageLength
- [x] MagickGetImageMatteColor
- [x] MagickGetImageOrientation
- [x] MagickGetImagePage
- [x] MagickGetImagePixelColor
- [x] MagickGetImageRedPrimary
- [x] MagickGetImageRegion
- [x] MagickGetImageRenderingIntent
- [x] MagickGetImageResolution
- [x] MagickGetImageScene
- [x] MagickGetImageSignature
- [x] MagickGetImageTicksPerSecond
- [x] MagickGetImageType
- [x] MagickGetImageUnits
- [x] MagickGetImageVirtualPixelMethod
- [x] MagickGetImageWhitePoint
- [x] MagickGetImageWidth
- [x] MagickGetNumberImages
- [x] MagickGetImageTotalInkDensity
- [x] MagickHaldClutImage
- [x] MagickHasNextImage
- [x] MagickHasPreviousImage
- [x] MagickHoughLineImage
- [x] MagickIdentifyImage
- [x] MagickIdentifyImageType
- [x] MagickImplodeImage
- [x] MagickImportImagePixels
- [x] MagickInterpolativeResizeImage
- [ ] MagickInverseFourierTransformImage
- [x] MagickKMeansImage
- [x] MagickKuwaharaImage
- [x] MagickLabelImage
- [x] MagickLevelImage
- [x] MagickLevelImageColors
- [x] MagickLevelizeImage
- [x] MagickLinearStretchImage
- [x] MagickLiquidRescaleImage
- [x] MagickLocalContrastImage
- [x] MagickMagnifyImage
- [x] MagickMeanShiftImage
- [x] MagickMergeImageLayers
- [x] MagickMinifyImage
- [x] MagickModulateImage
- [x] MagickMontageImage
- [x] MagickMorphImages
- [x] MagickMorphologyImage
- [x] MagickMotionBlurImage
- [x] MagickNegateImage
- [x] MagickNewImage
- [x] MagickNextImage
- [x] MagickNormalizeImage
- [x] MagickOilPaintImage
- [x] MagickOpaquePaintImage
- [x] MagickOptimizeImageLayers
- [x] MagickOptimizeImageTransparency
- [x] MagickOrderedDitherImage
- [x] MagickPingImage
- [ ] MagickPingImageBlob
- [ ] MagickPingImageFile
- [x] MagickPolaroidImage
- [ ] MagickPolynomialImage
- [x] MagickPosterizeImage
- [x] MagickPreviewImages
- [x] MagickPreviousImage
- [x] MagickQuantizeImage
- [ ] MagickQuantizeImages
- [x] MagickRangeThresholdImage 
- [x] MagickRotationalBlurImage 
- [x] MagickRaiseImage 
- [x] MagickRandomThresholdImage 
- [x] MagickReadImage 
- [x] MagickReadImageBlob 
- [ ] MagickReadImageFile
- [x] MagickRemapImage 
- [x] MagickRemoveImage 
- [x] MagickResampleImage 
- [x] MagickResetImagePage 
- [x] MagickResizeImage 
- [x] MagickRollImage 
- [x] MagickRotateImage 
- [x] MagickSampleImage 
- [x] MagickScaleImage 
- [x] MagickSegmentImage 
- [x] MagickSelectiveBlurImage 
- [x] MagickSeparateImage 
- [x] MagickSepiaToneImage 
- [x] MagickSetImage 
- [x] MagickSetImageAlphaChannel 
- [x] MagickSetImageBackgroundColor 
- [x] MagickSetImageBluePrimary 
- [x] MagickSetImageBorderColor 
- [x] MagickSetImageChannelMask 
- [x] MagickSetImageMask 
- [x] MagickSetImageColor 
- [x] MagickSetImageColormapColor 
- [x] MagickSetImageColorspace
- [x] MagickSetImageCompose
- [x] MagickSetImageCompression
- [x] MagickSetImageCompressionQuality
- [x] MagickSetImageDelay
- [x] MagickSetImageDepth
- [x] MagickSetImageDispose
- [x] MagickSetImageEndian
- [x] MagickSetImageExtent
- [x] MagickSetImageFilename
- [ ] MagickSetImageFilter [needs updating ImageMagick's version]
- [x] MagickSetImageFormat
- [x] MagickSetImageFuzz
- [x] MagickSetImageGamma
- [x] MagickSetImageGravity
- [x] MagickSetImageGreenPrimary
- [x] MagickSetImageInterlaceScheme
- [x] MagickSetImageInterpolateMethod
- [x] MagickSetImageIterations
- [x] MagickSetImageMatte
- [x] MagickSetImageMatteColor
- [x] MagickSetImageAlpha
- [x] MagickSetImageOrientation
- [x] MagickSetImagePage
- [x] MagickSetImagePixelColor
- [ ] MagickSetImageProgressMonitor [tedious, will only implement if enough people ask]
- [x] MagickSetImageRedPrimary
- [x] MagickSetImageRenderingIntent
- [x] MagickSetImageResolution
- [x] MagickSetImageScene
- [x] MagickSetImageTicksPerSecond
- [x] MagickSetImageType
- [x] MagickSetImageUnits
- [x] MagickSetImageVirtualPixelMethod
- [x] MagickSetImageWhitePoint
- [x] MagickShadeImage
- [x] MagickShadowImage
- [x] MagickSharpenImage
- [x] MagickShaveImage
- [x] MagickShearImage
- [x] MagickSigmoidalContrastImage
- [ ] MagickSimilarityImage
- [x] MagickSketchImage
- [x] MagickSmushImages
- [x] MagickSolarizeImage
- [x] MagickSparseColorImage
- [x] MagickSpliceImage
- [x] MagickSpreadImage
- [x] MagickStatisticImage
- [x] MagickSteganoImage
- [x] MagickStereoImage
- [x] MagickStripImage
- [x] MagickSwirlImage
- [x] MagickTextureImage
- [x] MagickThresholdImage
- [x] MagickThresholdImageChannel
- [x] MagickThumbnailImage
- [x] MagickTintImage
- [x] MagickTransformImageColorspace
- [x] MagickTransparentPaintImage
- [x] MagickTransposeImage
- [x] MagickTransverseImage
- [x] MagickTrimImage
- [x] MagickUniqueImageColors
- [x] MagickUnsharpMaskImage
- [x] MagickVignetteImage
- [x] MagickWaveImage
- [x] MagickWaveletDenoiseImage
- [x] MagickWhiteBalanceImage
- [x] MagickWhiteThresholdImage
- [x] MagickWriteImage
- [ ] MagickWriteImageFile
- [x] MagickWriteImages
- [ ] MagickWriteImagesFile

# [Pixel Iterator Methods](https://imagemagick.org/api/pixel-iterator.php)

- [x] ClearPixelIterator
- [x] ClonePixelIterator
- [x] DestroyPixelIterator
- [x] IsPixelIterator
- [x] NewPixelIterator
- [x] PixelClearIteratorException
- [x] NewPixelRegionIterator
- [x] PixelGetCurrentIteratorRow
- [x] PixelGetIteratorException
- [x] PixelGetIteratorExceptionType
- [x] PixelGetIteratorRow
- [x] PixelGetNextIteratorRow
- [x] PixelGetPreviousIteratorRow
- [x] PixelResetIterator
- [x] PixelSetFirstIteratorRow
- [x] PixelSetIteratorRow
- [x] PixelSetLastIteratorRow
- [x] PixelSyncIterator

# [Pixel Wand Methods](https://imagemagick.org/api/pixel-wand.php)

- [x] ClearPixelWand
- [x] ClonePixelWand
- [ ] ClonePixelWands
- [x] DestroyPixelWand
- [ ] DestroyPixelWands
- [x] IsPixelWandSimilar
- [x] IsPixelWand
- [x] NewPixelWand
- [x] NewPixelWands
- [x] PixelClearException
- [x] PixelGetAlpha
- [ ] PixelGetAlphaQuantum
- [x] PixelGetBlack
- [ ] PixelGetBlackQuantum
- [x] PixelGetBlue
- [ ] PixelGetBlueQuantum
- [x] PixelGetColorAsString
- [x] PixelGetColorAsNormalizedString
- [x] PixelGetColorCount
- [x] PixelGetCyan
- [ ] PixelGetCyanQuantum
- [x] PixelGetException
- [x] PixelGetExceptionType
- [x] PixelGetFuzz
- [x] PixelGetGreen
- [ ] PixelGetGreenQuantum
- [x] PixelGetHSL
- [ ] PixelGetIndex
- [x] PixelGetMagenta
- [ ] PixelGetMagentaQuantum
- [x] PixelGetMagickColor
- [x] PixelGetPixel
- [x] PixelGetQuantumPacket
- [ ] PixelGetQuantumPixel
- [x] PixelGetRed
- [ ] PixelGetRedQuantum
- [x] PixelGetYellow
- [ ] PixelGetYellowQuantum
- [x] PixelSetAlpha
- [ ] PixelSetAlphaQuantum
- [x] PixelSetBlack
- [ ] PixelSetBlackQuantum
- [x] PixelSetBlue
- [ ] PixelSetBlueQuantum
- [x] PixelSetColor
- [x] PixelSetColorCount
- [x] PixelSetColorFromWand
- [x] PixelSetCyan
- [ ] PixelSetCyanQuantum
- [x] PixelSetFuzz
- [x] PixelSetGreen
- [ ] PixelSetGreenQuantum
- [x] PixelSetHSL
- [ ] PixelSetIndex
- [x] PixelSetMagenta
- [ ] PixelSetMagentaQuantum
- [x] PixelSetPixelColor
- [ ] PixelSetQuantumPixel
- [x] PixelSetRed
- [ ] PixelSetRedQuantum
- [x] PixelSetYellow
- [ ] PixelSetYellowQuantum

# [Drawing Wand Methods](https://imagemagick.org/api/drawing-wand.php)

- [x] ClearDrawingWand
- [x] CloneDrawingWand
- [x] DestroyDrawingWand
- [x] DrawAffine
- [x] DrawAlpha
- [x] DrawAnnotation
- [x] DrawArc
- [x] DrawBezier
- [x] DrawCircle
- [x] DrawClearException
- [ ] DrawCloneExceptionInfo
- [x] DrawColor
- [x] DrawComposite
- [x] DrawComment
- [x] DrawEllipse
- [x] DrawGetBorderColor
- [x] DrawGetClipPath
- [x] DrawGetClipRule
- [x] DrawGetClipUnits
- [x] DrawGetDensity
- [x] DrawGetException
- [x] DrawGetExceptionType
- [x] DrawGetFillColor
- [x] DrawGetFillOpacity
- [x] DrawGetFillRule
- [x] DrawGetFont
- [x] DrawGetFontFamily
- [x] DrawGetFontResolution
- [x] DrawGetFontSize
- [x] DrawGetFontStretch
- [x] DrawGetFontStyle
- [x] DrawGetFontWeight
- [x] DrawGetGravity
- [x] DrawGetOpacity
- [x] DrawGetStrokeAntialias
- [x] DrawGetStrokeColor
- [x] DrawGetStrokeDashArray
- [x] DrawGetStrokeDashOffset
- [x] DrawGetStrokeLineCap
- [x] DrawGetStrokeLineJoin
- [x] DrawGetStrokeMiterLimit
- [x] DrawGetStrokeOpacity
- [x] DrawGetStrokeWidth
- [x] DrawGetTextAlignment
- [x] DrawGetTextAntialias
- [x] DrawGetTextDecoration
- [x] DrawGetTextDirection
- [x] DrawGetTextEncoding
- [x] DrawGetTextKerning
- [x] DrawGetTextInterlineSpacing
- [x] DrawGetTextInterwordSpacing
- [x] DrawGetTypeMetrics
- [x] DrawGetVectorGraphics
- [x] DrawGetTextUnderColor
- [x] DrawLine
- [x] DrawPathClose
- [x] DrawPathCurveToAbsolute
- [x] DrawPathCurveToRelative
- [x] DrawPathCurveToQuadraticBezierAbsolute
- [x] DrawPathCurveToQuadraticBezierRelative
- [x] DrawPathCurveToQuadraticBezierSmoothAbsolute
- [x] DrawPathCurveToQuadraticBezierSmoothRelative
- [x] DrawPathCurveToSmoothAbsolute
- [x] DrawPathCurveToSmoothRelative
- [x] DrawPathEllipticArcAbsolute
- [x] DrawPathEllipticArcRelative
- [x] DrawPathFinish
- [x] DrawPathLineToAbsolute
- [x] DrawPathLineToRelative
- [x] DrawPathLineToHorizontalAbsolute
- [x] DrawPathLineToHorizontalRelative
- [x] DrawPathLineToVerticalAbsolute
- [x] DrawPathLineToVerticalRelative
- [x] DrawPathMoveToAbsolute
- [x] DrawPathMoveToRelative
- [x] DrawPathStart
- [x] DrawPoint
- [x] DrawPolygon
- [x] DrawPolyline
- [x] DrawPopClipPath
- [x] DrawPopDefs
- [x] DrawPopPattern
- [x] DrawPushClipPath
- [x] DrawPushDefs
- [x] DrawPushPattern
- [x] DrawRectangle
- [x] DrawResetVectorGraphics
- [x] DrawRotate
- [x] DrawRoundRectangle
- [x] DrawScale
- [x] DrawSetBorderColor
- [x] DrawSetClipPath
- [x] DrawSetClipRule
- [x] DrawSetClipUnits
- [x] DrawSetDensity
- [x] DrawSetFillColor
- [x] DrawSetFillOpacity
- [x] DrawSetFontResolution
- [x] DrawSetOpacity
- [ ] DrawSetFillPatternURL
- [x] DrawSetFillRule
- [x] DrawSetFont
- [x] DrawSetFontFamily
- [x] DrawSetFontSize
- [x] DrawSetFontStretch
- [x] DrawSetFontStyle
- [x] DrawSetFontWeight
- [x] DrawSetGravity
- [x] DrawSetStrokeColor
- [ ] DrawSetStrokePatternURL
- [x] DrawSetStrokeAntialias
- [x] DrawSetStrokeDashArray
- [x] DrawSetStrokeDashOffset
- [x] DrawSetStrokeLineCap
- [x] DrawSetStrokeLineJoin
- [x] DrawSetStrokeMiterLimit
- [x] DrawSetStrokeOpacity
- [x] DrawSetStrokeWidth
- [x] DrawSetTextAlignment
- [x] DrawSetTextAntialias
- [x] DrawSetTextDecoration
- [x] DrawSetTextDirection
- [x] DrawSetTextEncoding
- [x] DrawSetTextKerning
- [x] DrawSetTextInterlineSpacing
- [x] DrawSetTextInterwordSpacing
- [x] DrawSetTextUnderColor
- [x] DrawSetVectorGraphics
- [x] DrawSkewX
- [x] DrawSkewY
- [x] DrawTranslate
- [x] DrawSetViewbox
- [x] IsDrawingWand
- [x] NewDrawingWand
- [ ] PeekDrawingWand [tedious, will only implement if enough people ask]
- [x] PopDrawingWand
- [x] PushDrawingWand

# [WandView](https://imagemagick.org/api/wand-view.php)

- [ ] CloneWandView
- [ ] DestroyWandView
- [ ] DuplexTransferWandViewIterator
- [ ] GetWandViewException
- [ ] GetWandViewExtent
- [ ] GetWandViewIterator
- [ ] GetWandViewIterator
- [ ] GetWandViewWand
- [ ] IsWandView
- [ ] NewWandView
- [ ] NewWandViewExtent
- [ ] SetWandViewDescription
- [ ] SetWandViewIterator
- [ ] TransferWandViewIterator
- [ ] UpdateWandViewIterator
