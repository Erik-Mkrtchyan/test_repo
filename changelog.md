
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [abc] - 2021-04-29

### Added
* Workflow for distributing PicsartImage IOS app to Firebase ([#1502](https://github.com/PicsArt/pi-libs/pull/1502))
* Rolled back CPU Mesh kernel ([#1499](https://github.com/PicsArt/pi-libs/pull/1499))
* Threshold kernel. ([#1488](https://github.com/PicsArt/pi-libs/pull/1488))
* Skeletonize kernel. (#[1488](https://github.com/PicsArt/pi-libs/pull/1488))
* changeInputValue public API to FX (#[1478](https://github.com/PicsArt/pi-libs/pull/1478))
* [WASM] gpu session wrappers (#[1477](https://github.com/PicsArt/pi-libs/pull/1477))
* opacity and blend mode to quad kernel (#[1459](https://github.com/PicsArt/pi-libs/pull/1459))
* cancel() api to PhxImageView (android only) (#[1459](https://github.com/PicsArt/pi-libs/pull/1459))
* FxEffect: inputWithName api (#[1457](https://github.com/PicsArt/pi-libs/pull/1457))
* Checkers after GL texture creation to make crashlog more readable (validity check for texture cache and image buffer validity check messages will be available to user once they are not valid)  (#[1456](https://github.com/PicsArt/pi-libs/pull/1456))
* premultipliedMesh kernel.  (#[1455](https://github.com/PicsArt/pi-libs/pull/1455))
* Nodes invalidation handling in lua  (#[1452](https://github.com/PicsArt/pi-libs/pull/1452))
* Float type in lua (connected with C++) (#[1433](https://github.com/PicsArt/pi-libs/pull/1433))
* Support for several before/after/always/once scripts in lua (#[1433](https://github.com/PicsArt/pi-libs/pull/1433))
* Add logging functional to write logs into file on linux. (#[1424](https://github.com/PicsArt/pi-libs/pull/1424))
* Add functional to set verbosity of console outputs on linux. (#[1424](https://github.com/PicsArt/pi-libs/pull/1424))
* SVGRasterizer kernel (#[1423](https://github.com/PicsArt/pi-libs/pull/1423))
* Compiled Metal Shader Library to the framework resources (#[1404](https://github.com/PicsArt/pi-libs/pull/1404))
* Android APK signature check mechanism (#[1402](https://github.com/PicsArt/pi-libs/pull/1402))
* Depth buffer support. (#[1399](https://github.com/PicsArt/pi-libs/pull/1399))
* FX Effects test to nightly tests. (#[1369](https://github.com/PicsArt/pi-libs/pull/1369))
* Lua values support for RXNode (#[1352](https://github.com/PicsArt/pi-libs/pull/1352))
* Grouping/Ungrouping feature for iexplorer (#[1298](https://github.com/PicsArt/pi-libs/pull/1298))
* Slice kernel with rect input. (#[1297](https://github.com/PicsArt/pi-libs/pull/1297))
* BufferInt overloading for At kernel. (#[1297](https://github.com/PicsArt/pi-libs/pull/1297))
* Support pilibs build with python version from 3.6 to 3.9. (#[1236](https://github.com/PicsArt/pi-libs/pull/1236))
* Add CPU Implementation for CopySourceAlpha kernel (#[1225](https://github.com/PicsArt/pi-libs/pull/1225))
* New class Shape which fully covers the functionality of RShape, added new test cases for class Shape (#[1213](https://github.com/PicsArt/pi-libs/pull/1213))
* Wrappers for FX effects buffer outputs [All Platforms]. (#[1207](https://github.com/PicsArt/pi-libs/pull/1207))
* GPU Session support for iOS RXImageView (#[1191](https://github.com/PicsArt/pi-libs/pull/1191))
* Bounding rectangle kernel which calculates the bounding rectangle of non-zero pixels of a grayscale image. (#[1188](https://github.com/PicsArt/pi-libs/pull/1188))
* Add Buffer8, BufferFloat, BufferPoint to effects outputs (#[1179](https://github.com/PicsArt/pi-libs/pull/1179))
* Add Effects exceptions to python (#[1179](https://github.com/PicsArt/pi-libs/pull/1179))
* Added eyeshadows and blushes warping points kernels. (#[1178](https://github.com/PicsArt/pi-libs/pull/1178))
* Migrated GL Kernels to the new GPU Engine. (#[1167](https://github.com/PicsArt/pi-libs/pull/1167))
* Changgelog for version 12.17 (#[1166](https://github.com/PicsArt/pi-libs/pull/1166))
* Add VERSION_NAME env var to the android iOS and Linux release builds to correctly assemble message text. (#[1162](https://github.com/PicsArt/pi-libs/pull/1162))
* Add Reshape kernel (#[1134](https://github.com/PicsArt/pi-libs/pull/1134))
* Add WarpAffine2d kernel (#[1134](https://github.com/PicsArt/pi-libs/pull/1134))
* Add Sqrt kernel (#[1134](https://github.com/PicsArt/pi-libs/pull/1134))
* Add Atan2 kernel (#[1134](https://github.com/PicsArt/pi-libs/pull/1134))
* Add Sum kernel for buffers (#[1134](https://github.com/PicsArt/pi-libs/pull/1134))
* Add FX effects testing to PicsartImage test app [IOS] (#[1107](https://github.com/PicsArt/pi-libs/pull/1107))
* Add DetectLandmarks kernel (#[1101](https://github.com/PicsArt/pi-libs/pull/1101))
* Add LandmarksSplitBuffer kernel (#[1101](https://github.com/PicsArt/pi-libs/pull/1101))
* Box blur for Image_8 (#[1056](https://github.com/PicsArt/pi-libs/pull/1056))
* Image morphing for Image_8 (#[1056](https://github.com/PicsArt/pi-libs/pull/1056))
* Public API for pilib startup from user required point. (#[797](https://github.com/PicsArt/pi-libs/pull/797))

### Changed
* PhxImageView setDrawCallback argument changed to nullable (#[1548](https://github.com/PicsArt/pi-libs/pull/1548))
* Effects quick change crash fix (#[1537](https://github.com/PicsArt/pi-libs/pull/1537))
* Integrate and use libunwind for our arm64-v8a build to collect stacks from all running threads when crashing. (#[1513](https://github.com/PicsArt/pi-libs/pull/1513))
* Improved kernel selection error messages (#[1511](https://github.com/PicsArt/pi-libs/pull/1511))
* Effects quick change crash fix (#[1497](https://github.com/PicsArt/pi-libs/pull/1497))
* Changed LOG_FATAL message format from stream to fmt (https://fmt.dev). (#[1491](https://github.com/PicsArt/pi-libs/pull/1491))
* Changed logic to abort in the same frame where LOG_FATAL is used. (#[1491](https://github.com/PicsArt/pi-libs/pull/1491))
* RXNode::moveDestination crash fix (#[1478](https://github.com/PicsArt/pi-libs/pull/1478))
* Make dispersion effect direction parameter change depends on the selected mask when AutoDirection is enabled (#[1472](https://github.com/PicsArt/pi-libs/pull/1472))
* Disabled some NSAssertions in release mode (#[1471](https://github.com/PicsArt/pi-libs/pull/1471))
* Replace LOG_FATAL with exception in FXBuilderFactory.  (#[1469](https://github.com/PicsArt/pi-libs/pull/1469))
* face mesh fitting parameters (#[1466](https://github.com/PicsArt/pi-libs/pull/1466))
* FxEffect android api: inputs method returns Map instead of HashMap. (#[1457](https://github.com/PicsArt/pi-libs/pull/1457))
* Fixed beautify smooth bug. (#[1455](https://github.com/PicsArt/pi-libs/pull/1455))
* Fixes color scheme android and web bug on HSL tool  (#[1445](https://github.com/PicsArt/pi-libs/pull/1445))
* ndk updated to version 21.4.7075529 (#[1442](https://github.com/PicsArt/pi-libs/pull/1442))
* iOS Crash extra information reporting mechanism with callback registration. (#[1429](https://github.com/PicsArt/pi-libs/pull/1429))
* Add checks for MNN session creation (#[1426](https://github.com/PicsArt/pi-libs/pull/1426))
* Added id="svg" attribute to <svg> element and removed stroke="none" from <g> elements in Vectorizer output. (#[1423](https://github.com/PicsArt/pi-libs/pull/1423))
* fixed: the result wasn't updating when using chained gpu image kernels (#[1422](https://github.com/PicsArt/pi-libs/pull/1422))
* fixed: stack use after free in java FxEffect parameterWithName() API (#[1422](https://github.com/PicsArt/pi-libs/pull/1422))
* rximageview's cancelation api in android is no longer synchronized (#[1418](https://github.com/PicsArt/pi-libs/pull/1418))
* Fixed crash in `Warp` kernel, caused by destination points including repeating values. (#[1396](https://github.com/PicsArt/pi-libs/pull/1396))
* Fixed GPU OilPainting kernel (#[1368](https://github.com/PicsArt/pi-libs/pull/1368))
* Fixed GPU Resize kernel issue. (#[1368](https://github.com/PicsArt/pi-libs/pull/1368))
* fix crash while creating facemorphing kernel (#[1302](https://github.com/PicsArt/pi-libs/pull/1302))
* fix corrupted image when trying to get value from image kernel of gpu session on Linux (#[1302](https://github.com/PicsArt/pi-libs/pull/1302))
* Show RXImageView graph as grouped by default (#[1298](https://github.com/PicsArt/pi-libs/pull/1298))
* Fix pil command for RXNode in Swift (#[1270](https://github.com/PicsArt/pi-libs/pull/1270))
* Update DetectFace: new and more accurate face detector model (#[1267](https://github.com/PicsArt/pi-libs/pull/1267))
* Update DetectLandmarks: now landmarks may have zero confidence which means they are not detected (#[1267](https://github.com/PicsArt/pi-libs/pull/1267))
* Changed MNN ios library to static (#[1231](https://github.com/PicsArt/pi-libs/pull/1231))
* Fix bug in eyelashes warp landmarks kernel (#[1224](https://github.com/PicsArt/pi-libs/pull/1224))
* The output shape of PSBlend function matches that of the bottom image (#[1212](https://github.com/PicsArt/pi-libs/pull/1212))
* Fix issue on If kernel  (#[1211](https://github.com/PicsArt/pi-libs/pull/1211))
* Fix library build with python version 3.6 (#[1210](https://github.com/PicsArt/pi-libs/pull/1210))
* Fix the bug concerning calculating the output shape for BufferFromImage Kernel (#[1206](https://github.com/PicsArt/pi-libs/pull/1206))
* Fixed buffer incorrect copying in "effect_file_resource" kernel (#[1199](https://github.com/PicsArt/pi-libs/pull/1199))
* Changed kernel matching logic, to not match when none of the kernels has the same shape, which in turn will force new kernel creation (#[1189](https://github.com/PicsArt/pi-libs/pull/1189))
* Fix dispersion effect (#[1175](https://github.com/PicsArt/pi-libs/pull/1175))
* Fixed alpha channel not blurring issue in android CPU BoxBlur kernel. (#[1136](https://github.com/PicsArt/pi-libs/pull/1136))
* change Reallocate to fill new elements with value (#[1134](https://github.com/PicsArt/pi-libs/pull/1134))
* Vertical gaussian blur (CPU) rotates the image and makes horizontal blur for not iOS builds for fast execution. Increases RAM usage. (#[1120](https://github.com/PicsArt/pi-libs/pull/1120))
* Fix bug in MapToRange kernel (#[1104](https://github.com/PicsArt/pi-libs/pull/1104))
* Graph optimization mechanism is implemented, so from now on the user created graph and actual executed graph may be different.  (#[1013](https://github.com/PicsArt/pi-libs/pull/1013))
* Change factory generator to merge wrapper functions that have the same signature (#[768](https://github.com/PicsArt/pi-libs/pull/768))

### Removed
* CPU Mesh kernel. (#[1368](https://github.com/PicsArt/pi-libs/pull/1368))
* Remove effects tests section from the PicsArtImage test app (#[1107](https://github.com/PicsArt/pi-libs/pull/1107))

### Depricated
* `InputSwitch` kernel (#[1384](https://github.com/PicsArt/pi-libs/pull/1384))
* TensorflowImageInferenceKernel (#[1361](https://github.com/PicsArt/pi-libs/pull/1361))

## [12.23] - 2021-04-29

### Added
* Threshold kernel.
* Skeletonize kernel.
* GPU session wrappers / WASM.
* premultipliedMesh kernel. 
* SVGRasterizer kernel.
* Depth buffer support.
* changeInputValue public API to FX.
* Grouping/Ungrouping feature for iexplorer.
* libunwind integration for our arm64-v8a build to collect stacks from all running threads when crashing.
* Workflow for distributing PicsartImage IOS app to Firebase.

### Changed
* Rolled back CPU Mesh kernel.
* Improved kernel selection error messages.
* Changed LOG_FATAL message format from stream to fmt (https://fmt.dev).
* Changed logic to abort in the same frame where LOG_FATAL is used.
* RXNode::moveDestination crash fix.
* Make dispersion effect direction parameter change depends on the selected mask when AutoDirection is enabled.
* Added id="svg" attribute to <svg> element and removed stroke="none" from <g> elements in Vectorizer output.
* Show RXImageView graph as grouped by default.
* Change factory generator to merge wrapper functions that have the same signature.

## [12.22] - 2021-04-15

### Added
* Opacity and blend mode to quad kernel.
* cancel() api to PhxImageView / Android.
* inputWithName API.
* premultipliedMesh kernel.
* Nodes invalidation handling in lua.
* Float type in lua (connected with C++).
* Support for several before/after/always/once scripts in lua.
* Logging functionality to write logs into file on linux.
* Functionality to set verbosity of console outputs on linux.
* Public API for pilib startup from user required point.
* Checks for MNN session creation.
* iOS Crash extra information reporting mechanism with callback registration.

### Changed
* Effects quick change crash fix
* Make dispersion effect direction parameter change depends on the selected mask when AutoDirection is enabled.
* Replace LOG_FATAL with exception in FXBuilderFactory. 
* Face mesh fitting parameters.
* FxEffect api inputs method returns Map instead of HashMap / Android.
* Fixed color scheme on HSL tool / Android, Wasm. 
* Fixed the result updating when using chained gpu image kernels.
* Fixed stack use after free in java FxEffect parameterWithName() API.
* Fixed crash in Warp kernel, caused by destination points including repeating values.
* Updated ndk version to 21.4.7075529 .
* Depricated InputSwitch kernel.

## [12.21] - 2021-04-01

### Added
* Compiled Metal Shader Library to the framework resources.
* FX Effects test to nightly tests.
* Lua values support for RXNode.
* APK signature check mechanism.
* Checkers after GL texture creation to make crashlog more readable (validity check for texture cache and image buffer validity check messages will be available to user once they are not valid).

### Changed
* Fixed GPU OilPainting kernel.
* Fixed GPU Resize kernel issue.
* rximageview's cancelation api in android is no longer synchronized.
* Depricated TensorflowImageInferenceKernel.
* Disabled some NSAssertions in release mode.

### Removed
* CPU Mesh kernel.

## [12.20] - 2021-03-18

### Added
* Slice kernel with rect input.
* BufferInt overloading for At kernel.

### Changed
* Fix crash while creating facemorphing kernel.
* Fix corrupted image when trying to get value from image kernel of gpu session on Linux.

## [12.19] - 2021-03-05

### Added
* Migrated GL Kernels to the new GPU Engine
* Support pilibs build with python version from 3.6 to 3.9.
* CPU Implementation for CopySourceAlpha kernel
* New class Shape which fully covers the functionality of RShape, added also tests
* GPU Session support for iOS RXImageView


### Changed
* Fix pil command for RXNode in Swift
* Update DetectFace: new and more accurate face detector model
* Update DetectLandmarks: now landmarks may have zero confidence which means they are not detected
* Changed MNN ios library to static
* Fix bug in eyelashes warp landmarks kernel
* The output shape of PSBlend function matches that of the bottom image
* Fix the bug concerning calculating the output shape for BufferFromImage Kernel
* Changed kernel matching logic, to not match when none of the kernels has the same shape, which in turn will force new kernel creation
* Fix dispersion effect

## [12.18] - 2021-02-19

### Added
* Wrappers for FX effects buffer outputs.
* Bounding rectangle kernel which calculates the bounding rectangle of non-zero pixels of a grayscale image.
* Buffer8, BufferFloat, BufferPoint to effects outputs.
* Add Effects exceptions to python.
* New eyeshadows and blushes warping points kernels.
* Reshape kernel.
* WarpAffine2d kernel.
* Sqrt kernel.
* Atan2 kernel.
* Sum kernel for buffers.
* DetectLandmarks kernel.
* LandmarksSplitBuffer kernel.

### Changed
* Fixed issue on If kernel. 
* Fixed library build with python version 3.6.
* Fixed buffer incorrect copying in "effect_file_resource" kernel.
* Fixed alpha channel not blurring issue in android CPU BoxBlur kernel.
* Reallocate to fill new elements with value.

## [12.17] - 2021-02-04

### Added
* Add VERSION_NAME env var to the android iOS and Linux release builds to correctly assemble message text.
* Add FX effects testing to PicsartImage test app [IOS]

### Changed
* Vertical gaussian blur (CPU) rotates the image and makes horizontal blur for not iOS builds for fast execution.

### Removed
* Remove effects tests section from the PicsArtImage test app.

## [12.16] - 2021-01-21

### Added
* Phoenix engine
* Box blur for Image_8
* Image morphing for Image_8
* GPU session ( currently experimental )

### Changed
* Fix bug in MapToRange kernel
* Reduce Fattal1, Fattal2 effects kernel execution time significantly.
* Graph optimization mechanism is implemented, so from now on the user created graph and actual executed graph may be different. 

## [12.15] - 2020-12-25

### Added
* Add bmp encoder
* test sample for dispersion effect (iOS)
* HSLKernenl cpu and gl implementations. 
* Pixel_LUV, Pixel_XYZ types and conversions to Pixel_RGB and vice versa.

### Changed
* Fix graph fps drop.
* RXImageview preview fix
* Separates moves pixel types form types.hpp to pixel_types.hpp. 
* Replaces static functions of ThinPlateSplineWarping class with member functions.

### Removed
* Remove android object's parcelable implementation

## [12.14] - 2020-12-11

### Added
* api for creating and copying image buffer from bitmap with rect argument
* MNN image inference kernel.

### Changed
* Fixed json property issue on EffectParameter
* Fixed RXImageView rotation issue
* More optimization on encodeToPNG function in javascript.
* FaceMesh kernel projectedCoords output type (BufferInt -> BufferPoint2f)
* 4dfm version
* Fix error in RXSession cancelation(iOS)
* Fix cancellation token assignment race condition in RXImageView
* Updated build docs: more details & fixed formatting

## [12.13.0] - 2020-11-27

### Added
* nearest Z output to face mesh kernel.
* "set string value" method to all FXParameters.
* Ability to save resources and overrideParameters in the builder.
* **_Inputs_** read-only property for iOS and Android platforms.

### Changed
* matrix transpose bug fix in lighting kernel
* Fix invalid shape order for Slice kernel in BasicOperations section

## [12.12] - 2020-11-16

### Added
* nearest Z output to face mesh kernel
* Runed image parameter to RXImageVIew didRun delegate method.
* Image_8 overloading for "copy source alpha" kernel
* "default_case" to switch kernel inputs
* Matrix multiplication kernel: Gemm
* Point transformation kernel: TransformPoint
* Second output to NewTransformMatrix: inverse of transformation matrix

### Changed
* Update setup-maven 
* Fix deadlock issue on removeNode
* Fix bug in the kernel overloading checking algorithm
* Kernel overloading requirements
* Matrix layout for RXImageView, Lighting, Mesh kernels to row major layout
* Deprecate com.picsart.picore.Matrix4. Use mat3x3->mat4x4 conversion function in core/MatrixUtils.kt instead
* Deprecate Android RXImageView set transform with com.picsart.picore.Matrix4. Use android.graphics.Matrix instead
* Merge RXContext with RXExecutionNode, from now on RXContext is typedef of RXExecutionNode

### Removed
* RXContext class

## [12.11.0] - 2020-10-30

### Added
* Ability to merge effects with several inputs, by passing those inputs to merger patch.
* Show parameters (width,height, size) of image in node preview screen
* Skia library to WASM project
* Warp Kernel
* Wasm uploading mechanism.
* GaussianBlur kernel overloading for Image_8
* Image based lighting for relight and 3D face masks.
* Three modes for ImageBuffer<TPixel>.at(int i, int j, **_EdgeMode, TPixel_**), which means that instead of only raising an exception it can handle it in some new ways.

### Changed
* `RXGLSession`s will now automatically cancel run requests when the target is iOS Simulator
* `RXImageView` will display a warning about automatic cancellation logic with GL sessions on the iOS Simulator thus preventing the applications to crush at run-time on Simulator.

### Removed
* WarpedCoord kernel
* Gif_encoder thirdparty library, because there is no usage.

## [12.10] - 2020-10-16

### Added
* isRegistered method to BuilderFactory which checks builder with given name has been already registered or not.
* Utility to search specified kernel in json effects
* & qualifier to all kernel's defaulted parameters

### Changed
* Fixed already executed and supposed to be deleted graphs lifetime issues in session, this will fix memory related issues too.
* EAGLContext is not extending RCObject anymore
* Fixed lots of unused variable warnings

## [12.9] - 2020-10-02

### Added
* Added face mesh kernel to factory
* Added trigonometry kernel
* AlphaDstOpaque enum in android BlendMode

### Changed
* Fixed algorithmic issue in Water effect
* Replaced `ImageBuffer(int32 width, int32 height, const TPixel& pixelValue)` constructor with `initWithPixel(int32 width, int32 height, const TPixel& pixelValue)` factory method.

## [12.8.0] - 2020-09-18

### Added
* GitHub workflow for ios.
* kBlendModeAlphaDstOpaque(30) which is only correct when source and dest are not premultiplied and dest is opaque
* Add FaceDetector kernel
* MNN library for DNN inference

### Changed
* Fix some colors appear on the background in Stretch in Replay issue

## [12.7.0] - 2020-09-04

### Added
* Split channels test
* PSBlendif kernels for CPU and GL.
* Backend API integration with FX tests
* Kernel for getting landmark points for makeup warping.
* Bounding box kernel.
* InsetRect kernel for inseting rectangle with given size.
* MakeBorder kernel for adding borders to given image with given size and given color or texture.
* Accelerates warping by adding multithreading.
- DisplacementMap kernel.
- BilateralFilter gl kernel.
- AddWeighted kernel for calculating the weighted sum of two images.

### Changed
* Fix live crash related PIEffectView with glcontext(iOS)
* Minimum deployment target for iOS platform from 11.0 to 12.0
* Fix memory issue in Beautify tools 
* Alpha blending of GL:PSBlend to match CPU one.

### Removed
* `std::any_cast` method implementation for iOS versions lower then 12.0

## [12.6.0] - 2020-08-20

### Added
* Zoom support in Graph View tool.
* New Graph States tool to visualize memory/run states of the graph.
* Cached value is added to fx parameters to prevent FXParameter.getValue from thread locking
* Kernels automated registration and de-registration mechanism is added based on Services. It will allow to register a needed subset of kernels and de-register them once no more needed.

### Changed
* Fixed possible crash reason in patchbasedInpaint kernel. Related to https://picsart.atlassian.net/browse/PI-1443
* Fix a bug causing a crush for unhandled gl image types
* Document the best practice on getting output image from FX effect.
* Graph is spitted to execution and presentation layer. This will allow to make execution layer side optimizations in feature.

## [12.5.0] - 2020-08-07

### Added
* Convert method from ImageBuffer8 to ImageBufferARGB8 in java
* Allocation details in InvalidIdException
* Patch that create cache node at this place where you declare it in "patches" section.
* Testing mechanism for fx effects (without backend integration)
* New FileContentResource resource type which is a file content holder intended for the cases when file open and read can't be handled on our side.
* Custom fonts support for "Text Drawing " kernel
* New Node's preview screen in IEXplorer to preview Node's all data.
* Added search feature in IEXplorer Graph Viewer tool.
* Kernel which draw text in Image
* IEXplorer debugging tool first release (version 0.0.1)
* MakeBorder kernel for adding border to image. The kernel output is image with extended size and the extended areas are filled with original image by reading it with GL REPEAT, CLAMP_TO_EDGE, MIRRORED_REPEAT interpolation modes. 
*  FxEffect captureBuilder api
* New equality methods for all pixel values in _iOS_. Now pixel values in **Swift** can be just compared like this **_pixel1: PixelARGB8 == pixel2: PixelARGB8_**
* Nightly testing environment for ios.
* +, -, *, / operations for Buffer_Point2f and Point2f
* "at" kernels for Buffer_Point2f and Buffer_Point2i
* Point cast kernel for int to float and float to int
* Buffer_from kernel for getting Buffer from specified indexes of other Buffer
* FillPolygon kernel
* Invert kernel for Image_8
* Added documentation for CopySourceAlpha kernel.
* New constructor to RCPUKernel, RGLKernel, RGLFilterKernel with (std::vector\<InputInfo\> inputs, std::vector\

### Changed
* Fix data alignment in updateSubregion method for Image8 Buffer
* fixed memory allocation issues
* improved Image8 kernel memory allocation size
* Fix Beautify autotool
* Fix sketch effect distortion
* Fix rectangle appearing in the middle of the image in Tiny Planet effect
* Handling android rximageview surface callbacks on a separate thread
* Fix color1 param bug in doubleSketch effect
* Fix mode parameter not changing issue in CrossProcessing effect
* Fix layout issue in IEXplorer when there are useless nodes in graph connected to other nodes.
* Free CVPixelBuffers' kept memory.
* Rename FileResource to FileReaderResource.
* NDK updated to version 21.3.6528147
* FxBuilder implements Parcelable

### Removed
* Removed applying unnecessary “None” effect before the current effect when application returns from background. That avoids effect glitching. [IOS]

### Depricated
* 

## [12.4.0] - 2020-07-24

### Added
* Add patch that create cache node at this place where you declare it in "patches" section.
* Custom fonts support for "Text Drawing " kernel
* Added new Node's preview screen in IEXplorer to preview Node's all data.
* Added search feature in IEXplorer Graph Viewer tool.
* Added Nightly testing environment for ios.

### Changed
* Fix rectangle appearing in the middle of the image in Tiny Planet effect
* handling android rximageview surface callbacks on a separate thread
* Fix color1 param bug in doubleSketch effect
* Fix mode parameter not changing issue in CrossProcessing effect
* Fix layout issue in IEXplorer when there are useless nodes in graph connected to other nodes.
* Free CVPixelBuffers' kept memory.

### Depricated
* 

## [12.3] - 2020-07-10

### Added
* New **TextDrawing** kernel that draws a text on the image
* Alpha version of IEXplorer(v0.0.1) debugging tool. That allows real-time monitoring of the active sessions and their graphs
* `FXEffect` `captureBuilder` API
* New equality methods for all pixel values in _iOS_. Now pixel values in **Swift** can be just compared like this `pixel1: PixelARGB8 == pixel2: PixelARGB8`
* `+`, `-`, `*`, `/` operations for `Buffer_Point2f` and `Point2f`
* "**at**" kernels for `Buffer_Point2f` and `Buffer_Point2i`
* Point cast kernel for `int` to `float` and `float` to `int`
* "**Buffer_from**" kernel for creating a new buffer from the specified indexes of the given buffer
* "**FillPolygon**" kernel
* Invert kernel for `Image_8`

### Changed
* NDK updated to version _21.3.6528147_
* Fixed a crush on Sketch effect(PI-1323)
* Make `FXBuilder` to implement `Parcelable`

### Removed
* Redundant appliance of the “None” effect before the current effect when application returns from background. That avoids effect glitching. [**PicsArt Image iOS**]

## [12.2] - 2020-06-26

### Added

* Build step for the wasm in the main build flow.
* Bazel toolchain for wasm target, and buildable wasm target
* Binding of base functionality to the javascript
* Sample javascript project with simple B&W + fade example
* API allowing partial image updates on Android (provided only partial image writing API)
* Kernel for calculating the sum of the buffer elements
* Kernel for Colors Category Black And White Effect
* Sticker border kernel for Linux 
* Support for specific platform resources.
* Benchmark module for android
* Configuration in the android module to run with ASAN
* Flag to disable VM heap allocation (will be useful if we discover problems after integration)
* Photo saving as png with PHPhotoLibrary.
* Exposed some additional APIs from the C++

### Changed

* Fixed bug in case then "PatchbasedInpaint" input mask is not binary(This fix bug in wrinkle kernel)
* Fixed issue on "Switch" kernel when source of 'condition' input is not a value kernel
* Fixed file type checking in the image_compressor.
- Rolled back `setContextIfNeeded` function and its usages (This will cause Canvas and Beautify effects to work correctly in replays).
* Make 'delegate' property of RXImageView class weak (This fix memory leak if class is delegate of RXImageView).
* Switched places of input top and bottom images of blendPst function in following blend modes to match the photoshop version - ColorBurn, ColorDodge, LinearLight, PinLight, VividLight, Subtract, Negation, Difference
* Fixed deprecations in android tests
* Fixed 'lighting' shader compiling errors
* Rewrited Sticker border kernel to work via Skia
- Decreased cpp warnings, (approx. 190000 -> 7000)
- Changed image buffer similarity calculation to run with graphs
- Transfered faceMesh changes from ai-hackathon branch
### Removed
* Old implementation, when the photo was saved as a jpeg.

### Depricated
* RNativeObject's isAsyncFree method

#### **Also**

Benchmarked allocations on VM heap, the test was allocating image buffer and disposing

- Current implementation 18,351 ns-20,847 ns
- New implementation 34,801 ns - 44,854 ns
The overall increase is about 80%-115%

## [12.1] - 2020-15-06

### [Closed 32 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20fixVersion%20%3D%2012.1%20AND%20status%20in%20(Close%2C%20Done%2C%20DONE)%20order%20by%20%22Epic%20Link%22)

### Added

- Add Skia library to Android project
- Added NodeReplacer class which is inherited from Patch
- Added static_casts in types.hpp
- New unit tests for effects
- Added blend_mode as param to "Popart" kernels
- Added param, which can specify, if that patch must be removed from slave effect (by default is set to false)
- Debug information for Effect API classes
- Wrappers for IOS and AND
- Debug information for Effect API classes
- Stop method to stop httplib::Server
- Listening life cycle events to start server again when app appears on foreground
- Documentation

### Changed

- Make NodeReplacer Fade, Blend, and BlendFade's member
- Ability to specify "bottom" input for Blend, Fade, BlendFade, and InvertFade patches
- Changed comparators to work for float + int.
- Changed Vec class to work with size_t instead of int.
- Changed compare operations for Point class.
- Moved Check size!=0 Java side exception
- fixed float constants in shaders
- Change RXImageView reset function implementation from asynchrony resetting to synchronized
- Replaced dchek in start server with stop server. Now every time before start server stops previous one if there is
- retrieveParamValue to retrieve params output value instead of rxValue.
- ndk version to 21.2.6472646
- agp version to 4.0.0
- gradle version to 6.4.1
- warning fix

### Deleted

- Removed unnecessary declarations from types.h.

## [12.0] - 2020-06-01

Integration ready version of Graph Effects Library, several live crash fixes, improved PicsartIimage test app.
Additionally version delivers several fixes and improvements.

### [Closed 32 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20fixVersion%20%3D%2012.0%20AND%20status%20in%20(Close%2C%20Done)%20order%20by%20%22Epic%20Link%22)

### Added

- Python API
- Graph effects library
  - Added replaceParameter() function, which will find and replace parameter in effect
  - Unit tests
- Skia Library integration
  - Add Skia for iOS in dependencies
  - Link Skia library to iOS project
  - Integrated Skia library to Linux and MacOS projects

### Changed

- Graph effects library
  - Replace param in master effect instead of adding it in merge patch
  - Changed alpha resource handling in effect.cpp to only get resource image's alpha channel
- Code quality 
  - Effect's parameterWithName can return nullable object
  - Replaced C-style cast with UnsafeRefFromLong and static_cast
  - Changed OutputDescriptors' getter to fill and return member vector instead of local
  - Neew unit tests for memory allocation

### Deleted

- Graph effects library
  - Removed auto_value from slave effect's param, when "merge" patch is changing value

## [11.8] - 2020-05-19

The version delivers several live crash fixes and crash reporting improvements. PicsArtImage test app build improvements.

### [Closed 52 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20fixVersion%20%3D%2011.8%20AND%20status%20in%20(Close%2C%20Done)%20order%20by%20%22Epic%20Link%22)

### Added

- Added possibility to build the test app for Release mode
- Check for surface to be created before the gltexture creation. 
This check will prevent the creation of texture with invalid   size, such scenario will happen in case of effect applying interruption before GL surface creation
  
### Changed

- Java method names for being compatible with Kotlin properties
- Moved param creation to constructor in Effects
- Log files will be created with lazy strategy
- Throwing exception for Int, Float, Point parameters when default value is not in [min,max] range in EffectsTestApp
- bgu apply transform to not merge channels anymore

### Deleted

- Removed pi::universal_cast function

## [11.7] - 2020-05-06

The version delivers several live crash fixes, Kernel logical and overloading fixes. Improved PicsArtImage test app.

### [Closed 58 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20fixVersion%20%3D%2011.7%20AND%20status%20in%20(Close%2C%20Done)%20order%20by%20%22Epic%20Link%22)

### Added

- Enabled logging on PicsArtImage test app
- Added defines for Linux and Darwin
- Added makeCache() method to all virtual values, now you can simply call it instead of manually creating new nodes and assigning  previous values
- Crashlytics integration to iOS PicsArtImage app to report crashes from the deployed versions

### Changed

- Changed clang debug flags to not optimize
- Updated ndk version
- Rename RContext::hasInput to RContext::isInputConnected
- Rename RContext::isConnectedOutput to RContext::isOutputConnected
- RKernel::bytesCount() function have been moved to Object class. It have been overridden for classes derived from Object. Function was changed to be const

### Deleted

- Deleting the previously static pointer to oil_painting's context, which is now non static

## [11.6] - 2020-04-20

The version delivers improvements to graph engine, translation of all reminding effects to the Graph effects library, several live crash fixes, improved Picsart image test app, and improved developer productivity tools.

### [Closed 56 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20status%20in%20(close%2C%20done)%20AND%20fixVersion%20in%20(11.6)%20order%20by%20%22Epic%20Link%22)

### Added

- Graph effects library
  - Added Image8 output type to the API
  - Added Dispersion effect
  - Added Doxygen style commenting for C++, iOS, and Android APIs
- Graph Engine
  - Added mirroring library to enable object convenient transition from JNI to C++
- Kernels
  - Added new border kernel to be used to generate borders for the stickers

### Changed

- Graph effects library
  - Fixed transparency issues for all effects. Now transparency behavior is much better than in the old library
  - Removed file extension check when creating ImageBuffer from file
  - Fix for Dispersion effects on iOS
  - Fixed transparency and premultiplication for Canvas effects
  - Fixed thumbnails of the Picsart Image test app to correspond to effect visually
  - Fixed registration of default patches with the patch registry
  - Improvements to graph pre/post enqueue logic
- Graph Engine
  - Eliminated C-style casts from JNI level
  - Improved debug logging for ImageBuffer class
- Developer productivity
  - Migration to Bazel build system for Python support
  - Improved build scripting for Picsart image test app on Android for 
- Will now throw an exception instead of an abortion when allocation is failing, to allow the app to relaunch on Android
- Number of crash fixes and improvements

### Removed

## [11.5] - 2020-04-06

Version largely delivers polishing for the Graph effects library and translation of the remaining effects to the graph-based APIs.
It also includes improvements for the library's debugging tools, unit testing, and quite a few crash fixes and improvements.

### [Closed 73 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20status%20in%20(close%2C%20done)%20AND%20fixVersion%20in%20(11.5)%20order%20by%20%22Epic%20Link%22)

### Added

- Graph effects library
  - Noticeably improved effect behavior on transparent images using the new graph effects library
  - Migrated new Canvas, BRNZ, VNYL, Sketch and Oil painting effects to the new graph effects library as well
  - Added a tool which can be used to change parameters from effect's JSON used for merge and patch
  - Added hardcoded input for magic effects for Android test app to be able to test the integration
  - Added Int, Float, Point2f array type parameters to the graph effect library
  - Added support for GL3 for Graph 2.1 library to be able to implement effects like the oil painting
  - Added multiple inputs support for the test apps to support several effects like sketches
- Image Engine profiler trigger configuration is now available as a public API
- Graph resource freeing method is now available as a public API
- Kernels
  - Implemented Kernel to wrap the functionality of C++ Vectorizer library inside Image Engine
  - Added new calculateMagicImageSize kernel
- CI / CD
  - Moved Bazel build to GitHub actions
  - Created Google Test based unit tests system and used for Bazel build validation

### Changed

- Graph effects library
  - Changed ColorPreserved kernel and added a function to work with two inputs instead of changing the destination
  - Optimized Fade CPU Kernel for Image8
  - Updated user [documentation](https://docip.picsart.tools/master/fx_api/introduction/)
- Other improvements and fixes
  - Added namespace for the basic types like integers, size, point, image buffer and matrixes
  - Conducted OpenCV include dependency cleanup in the library
  - Delivered a fix for Video Editor square fit issue after stressing
  - Fixed a crash with the solarization effect with new effects graph API
  - Improved several kernels during graph effects API testing
  - A number of other fixes

### Removed

## [11.4] - 2020-03-23

Integration ready version of Graph Effects Library and new Adjust tools.   
Additionally, the version delivers the first portion of the groundwork for building the library on Linux and several fixes and improvements.

### [Closed 47 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20status%20in%20(close%2C%20done)%20AND%20fixVersion%20in%20(11.4)%20order%20by%20%22Epic%20Link%22)

### Added

- Kernels
  - Created several new kernels among which CopySourceAlpha, TensorFlow and SVGToImageBuffer and GetShapes kernel
- Introduced resize patch
- First unit test with Google test after adding support for Bazel build
- Zoom and before/after feature for Picsart Image test app
- Graph effects library
  - Added intelligent error and exception handling

### Changed

- Graph effects library
  - Optimized the case when blend and fade patches are used together, replaced with a single patch
  - Optimize Fade GL kernel
  - Fixed a bug with effects on transparent images related to ignoring the alpha channel values
  - Implemented optimization for resize kernel
  - Improved checkerboard rendering in Picsart Image test app to be able to test transparency with effects effectively
- Adjust tools
  - Fixed highlights tool result in new adjust with graph implementation
  - Fixed an issue in graph caching area related to the hash value which resulted in a performance improvement 
- Code quality
  - Cleaned up TensorFlow API dependencies
  - Improved floating-point comparison utilities
  - Fix errors & warnings from clang-tidy checks on the entire codebase
  - Fixed Equal and NotEqual kernel bugs for the floating-point values and decreased the number of floating-point comparisons warnings
- Developer productivity
  - Added Bazel build to the project which will enable backend support for the library and is very fast
  - GitHub actions integration
  - Android studio CMake cleanup
- Provide an API to mark image/buffer out of date for the whole image or just a part of it

### Removed

## [11.3] - 2020-03-11

Version mainly focused on polishing new graph effect library and optimization of new Adjust tools.  
Additionally version delivers several fixes and improvements.

### [Closed 61 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20status%20in%20(close%2C%20done)%20AND%20fixVersion%20in%20(11.3)%20order%20by%20%22Epic%20Link%22)

### Added

- Graph effects library
  - Migrated several effects to the new library among which are Brightness, Contrast, Focal Zoom, Tiny planet and many more
  - Number of fixes for already migrated effects
  - Created several new kernels among which RemoveBorder, IgnoreAlpha and NearlyEqual and more
- New remove graph and remove sub-graph routines callable from the node
- Code quality
  - Basic arithmetic operations for base types like point and size for code readability improvement

### Changed

- Graph effects library
  - Fixed several effects with different behavior from the live implementation
  - Continued stability and usability improvements on the PicsArt Image test app
- Optimization for IF kernel not to execute both branches which can provide noticeable performance gains in graphs with branching
- Adjust tools
  - Overall optimizations and polishing like using cache nodes and utilizing IF kernel for graph branched execution
- Image engine backend support
  - Include dependency cleanup
  - Transitioned to single project code organization for both iOS and Android
 - Number of bug fixes and stability improvements

### Removed

## [11.2] - 2020-02-19

Version mainly includes improvements for new Graph 2.1 APIs and preparation groundwork for new effects library migration.  
Additionally version delivers several fixes and improvements.

### [Closed 77 tickets](https://picsart.atlassian.net/issues/?jql=project%20%3D%20PI%20AND%20status%20in%20(close%2C%20done)%20AND%20fixVersion%20in%20(11.2)%20order%20by%20%22Epic%20Link%22)

### Added

- Graph Effects Library
- Preparation work for the new effects library to be released very soon

### Changed

- Graph 2.1 API
  - Fixed memory corruption case for the video editor
  - Fixed pause mode issues in image view for iOS and Android
  - Fixed faulty RX kernels on GL which caused the failure of several effects and tools
  - Fixed GLITCH effect JSON to prevent a crash in video editor
  - Fixed the case related to discarding graph modification after removing the image view
  - Improved Image view support of caching
  - Fixed an image quality issue for RXImageView by providing manual resolution selection API
  - Integrated graph new API for Picsart Android
- Stability
  - Fixed a crash after using the app for some time - was a memory leak in the library
  - Improved native crash stack trace reporting for Android
  - Made memory management/ownership improvement on Android to make sure to return the same object (reference) for the same C++ object
- Code quality
  - Reorganized C++ files to enable support fo the Image Engine in the backend

### Removed

- Removed ObjectiveCPP third party library as part of the code cleanup exercise
- Removed UNITY build from project settings

## [11.1] - 2019-02-05

### Added
- Native crash handling
- Support of pilibs stacktrace format to decoder.js
- Graph importing insertion option and wrappers

### Changed
- Native memory allocation calls replacement with managed memory allocation calls
- Bug fixes

### Removed
- Subject from effects

## [11.0] -2019-11-12

### Added 
- New Graph API (2.1)
    - Typed `*Value` API, data getters and setters
    - Documented and typed Factory in 4 languages
    - Thread / Resource safe API (Kernel public API is deprecated)
    - `Image View` - Grap's image presentation view for the realtime applications. (It will manage the rendering loop)
    - `Session.Run` with the `*Value` argument
    - Samples
- CPU and GL kernels aliases generation (now in JSON you can use `CPU:Fade` or `GL:Fade` to specify the technology) 
- Helper methods to work with sub-graphs
- Pre draw callback on GL kernel
   - `Lut` kernel inputs validation 
- Tests for all math kernels

### Changed
- API improvements
- Renamed `*_8888` and `*_888` and `*_8` to `8` (partiality) 
- Enabled warnings
- Bug fixes
- Optimizations 

### Removed
- Objective-C++ code from public API (for swift support)
- Logical buggy methods form API (`output`, `inputIndex`, `finalizeCompilation`, ...)
- Kernels default logging (use `KenelFactory.log` method)

## [10.29] - 2019-10-30
### Added
- OpenCV-3.4.7 /iOS
- Check on lowResInput and lowResOutput size equity for Blemish Fix
- Localization for "Line" and "Black and White" effects properties (integrated into pi-effects)

### Changed
- Adjust fixes for stickers with transparent background / Android (integrated into pi-effects)
- Radial Blur crash fix (integrated into pi-effects)
- duplicate symbol warning fix

### Removed
-

## [10.28] - 2019-10-17
### Added
- JNI for blending

### Changed
- convert() functions
- Background crash fix (integrated into pi-effects)
- Skin tone bug fix

### Removed
- Unused #ifdef

## [10.27] - 2019-09-19
### Added
-

### Changed
- Migrating to RXEffect/Android (integrated into pi-effects)
- Documentation fixes
- Bug/Warning fixes

### Removed
-

## [10.26.0] - 2019-09-06
### Added
- Sketch Mirror effects (integrated into pi-effects)
- Background Sketch (integrated into pi-effects)
- Wrapper class for accelerate method
- JNI calls validation checker/Android
- Init method on PI imagebuffer with compressed data and constructor
- TensorFlow dependency in pieffectsTestUI
- Swift support for ToolsLoader class (integrated into pi-tools)
- clang-format documentation
- LogOutOfMemory logger

### Changed
- Line value of Sketch effects(integrated into pi-effects)
- Mirror effect to graph (integrated into pi-effects)
- Enhance min amount from 0 to 1 (integrated into pi-effects)
- Migrating to RXEffect/iOS (integrated into pi-effects)
- Fix Color preservation in magic effects
- Fix kernels double registration (integrated into pi-effects)
- Fix ByteBuffer crash
- PI libs build type
- Bug fixes

### Removed
- pi-nn-effects (integrated into pi-effects)
- pitfnneffects (integrated into pi-effects)

## [10.25.0] - 2019-08-20
### Added
- Migration to AndroidX
- Debug graph view / Android
- New Math kernels 
- copyAlphaToDest method

### Changed
- OilPainting effect (integrated into pi-effects) / Android
- Adjust for sticker (integrated into pi-effects)
- Mash output color channel
- JNIEnv saving
- GlContext handling on GLKernel
- Bug fixes

### Removed
-

## [10.24.0] - 2019-08-07
### Added
- New Math kernels
- New Swift commands support
- Comparation operations
- Doxygen documentation
- Documentation for core types

### Changed
- Loaders fix
- Blemish fix (integrated to pi-effects)

### Removed
-

## [10.23.0] - 2019-07-24
### Added
- Functionality to write logs to file
- Downloadable boost /Android (integrated to pi-effects, pi-tools)
- R guided upsampling

### Changed
- Memory manager
- Blemish tool (integrated to pi-effects)
- Warning fix

### Removed
-

## [10.22.0] - 2019-07-10
### Added
- Swift support
- Guided filter upscaling kernel
- TransformationaTarget  kernel (temporary)

### Changed
- Symbols to not strip (integrated to pi-effects, pi-tools)

### Removed
- storeAccessor from API

## [10.21.0] - 2019-06-28
### Added
- Blend mode for SKETCH Effects (integrated to pi-effects)
- Interpolation mode on GLKernel

### Changed
- Morphing shader

### Removed
-

## [10.20.0] - 2019-06-13
### Added
- SKETCH Effects (integrated to pi-effects)
- Blend mode to PIRXImageView /iOS
- Image view content transformation /iOS

### Changed
- Import graph
- Binary mask ARGB 8888
- Cache nodes/Android
- Nose, brow distance parameters(integrated to pi-tools)/iOS
- Fix warnings

### Removed
-

## [10.19.0-F] - 2019-05-27
### Added
- New Face morphing tool
- Functionality to disable gl face culling for the mesh

### Changed
- Fix Android image quality
- Fix warnings

### Removed
-

## [10.18.4] - 2019-05-20
### Added
- PIImageBuffer, PIBuffer initialiser from Objective-C native containers / iOS
- Value kernels missing APIs /iOS
- Pixel types wrappers / iOS
- ImageBuffer for RGBA color scheme / Android

### Changed
- Image Buffer API / Android
- Null correctness / Android
- RXEffect /Android

### Removed
- Old ManagedBuffer/ManagedBitmap API/ Android
- Bolts framework / Android

## [10.18.0-F] - 2019-04-26
### Added
 - RXProfiler wrapper/ Android 



### Changed
 - ImageBuffer refactoring
 - Make some methods null safe/java API
 - Fixes in GLimageKernel(bitPerPixel method)
 - Fixes in Gif To Video Converter
 - Iprove compile time 
 - Concat automatic handling of double/float without collisions (RxSession caching fix)
 - Fix race condition on RXGraph


### Removed
 - PIParrallelPool unused class



## [10.17.0] - 2019-03-28
### Added
 - "BufferFromImage" kernel
 - "KeyValuesInterpolation" kernel
 - LockImageWithRect method on GLImageKernel
 - UpdateSubregion methods on GLImageKernel



### Changed
 - Fix nullability warnings
 - Fixes releated manual stretch tools(integrated to pi-tools)
 - Fix related interaption on RXSession


### Removed
 - 




## [10.16.0] - 2019-03-15
### Added
 -


### Changed
 - Refactored LUT1D Kernel (
   Replaced input "lut" to    
     {"alpha", RType::Image_8},
        {"red", RType::Image_8},
        {"green", RType::Image_8},
        {"blue", RType::Image_8},
        {"rgb", RType::Image_8})


### Removed
- LUT1D CPU kernel(as already exist "ImageTableLookUp" kernel with same functional)





## [10.15.0-F] - 2019-03-01
### Added
 - math operation on Points
 - min/max kernels for Scalars
 - discrete key frame Animation /iOS
 - blackColorRemoval method /iOS


### Changed
 - Integrated Unity build system


### Removed
- 

## [10.14.0-S] - 2019-02-21
### Added
- PIRXGLSession dealloc /iOS

### Changed
  - fix in decryptFile method/Android


### Removed
- 


## [10.14.0-F] - 2019-02-13
### Added
- BinaryMask, MinMax, MapToRange kernels
- Native exeption converting of Java exeption, all exeptions handling in JNI
- Gif To Video Converter /iOS
- CPP Containers to Objective-C containers switchers
- NSString extentions to work with c++ string


### Changed
  - Alpha support and fix of getCropRect method /Android


### Removed
- ImageRowColumnShift CPU kernel

## [10.13.2-S] - 2019-01-25
### Added
- 

### Changed
 - 

### Removed
- RLUTKernel class
- RGLLutKernel class, RGLFilterkernel have been used instead
- RCPULutKernel class, uses RCPUkernel have been used instead


## [10.13.1-F] - 2019-01-18
### Added
- Enabled Arm64-v8a architecture for all library projects(Android)


### Changed
- Fix some  modes of CPU blend kernels.
- More exact version of mask kernel
- Fixes in RKernelImage Java API


### Removed
- Armv7, Armv7s architecture on iOS build.



## [10.13.0-F] - 2018-12-24
### Added
- Helper kernels for New Wave tool
- Java Loader API wrappers.
- Enqueue loader API
- Boost C++ header only libraries are required to build project.

### Changed
- Fixes in Blur Kernel
- Fixes on blending functions
- Fixes in RKernelARGB8888 Java wrappers
- Now `RGLImageKernel<T>::invalidateTextureImage()` should be called less often by the user. `lockImage` automatically invalidates texture.
- Graph compilation is now more optimal and smarter. It is able to solve more difficult problems.
- Graph execution was optimized, ~50% overhead was substituted to ~15%. 
- [Small vector optimization](https://www.boost.org/doc/libs/1_69_0/doc/html/boost/container/small_vector.html) for `RShape`.
- Fixes in `RXProfiler` time calculation. Profiler became faster and more correct.

### Removed
- No changes.

## [10.12.0-S] - 2018-12-13
### Added
- 

### Changed
- Fixes in RXCanvas Kernel(Android)
- Hash calculation algorithm improvemnt for RXGraph caching
- Color scheme correction in CopyTo method

### Removed
-  No changes.

## [10.11.0-S] - 2018-11-29
### Added
- Add missing Cpu Kernels(Mesh, BoxBlur, Idle)
- Add String suport for Switch Kernel
- Add missing implementation of mutableData method(Image_8, Image_RGB)

### Changed
- Fix Lut effect issue on camera
- Fix AffinianTransform Kernel

### Removed
-  No changes.

## [10.11.0-F] - 2018-11-22
### Added
- OpenCV libraries are linked to the project/ Android
- ImageBuffer constructor from path
- `glBlend` implementation, which uses native OpenGL blend functions for hardware accelerated blending.
- BlendMode Java wrappers
- `mutableData()`, `unsafeData`, `dataHash` methods on the `Buffer` and `ImageBuffer`
- More conversion methods were implemented. `BGRA`->`RGB`, `ARGB`->`BGR` and so on
- `Mesh` kernel now supports blend modes. `Mesh` execution now can be disabled using `enable` input.
- `makeVertexesMatrixKernel`, `makeTransformMatrixKernel`, `AngleToRadian`, `AspectFill`, `At`, `CoordGenerator`, `ImageFromFile`, `Invert`, `MakeOrthoProjectionMatrix`, `OrthoScaleFil`, `Overflow`, `RandomNumberGenerator`, `RotateImage`, `TimeRangeContainsTime`, `KeyFrameAnimation` kernels were added.

### Changed
- Fixed RXContext caching when input kernels modification count was changing.
- Buffer hash is now calculated using shift hash algorithm variation, which should help avoid unnecessary cache misses. 
- Now copying warnings are only printed for image kernels
- Fixed wrong `RGLImageKernel<T>::lockImage()` implementation in Android specific code.
- Some major bugs were fixed in less, greater and equal kernels.

### Removed
- `ImageBuffer<T>::data()` and `Buffer<T>::data()` non-const method
-  Some `Point` kernel overloads were removed for gods sake, because they created hard to debug and resolve situations when graph was imported from JSON (will be added later , when automate type casting  will handled).

## [10.10.0-S] - 2018-11-15
### Added
- Added draw method for kernel "GLTargetKernel"

### Changed
-  No changes.

### Removed
-  No changes.

# [10.10.1-F] - 2018-11-12
### Added
- `LAB_fff` in `RType` and `RKernelType`
- `RSession` java wrapper `getKernelBuffer[Int,Float]` methods implementations
- `>`, `<`, `=`, `Convert`, `GrayCPU`, `Invert` kernels

### Changed
- New outputs for `ShapeOf` kernel (`x`, `y`, `shape` ).

### Fixed
- Deprecated `RSession` interruption handling.
- Saturation calculation in [RHSL.fsh](https://github.com/PicsArt/pi-core/blob/04a97ed41572f592d705dd07073e604c4fefae5e/scripts/shader/RHSL.fsh)

### Removed
- No Changes


## [10.10.0-F] - 2018-11-08
### Added
- RX Graph API
- Convenient and advanced `RXProfiler` which makes easier to identify slow and memory eating kernels. Supports triggers (on memory grow, every last run and so on), ~20 different columns and produces beautiful, customizable logs.
- `RXNode` and `RXValue` are core classes of new RX API. They make possible to create cross-platform incremental-compiled computational graphs. Fast, incremental connection changes.
- `RXGraph` wrapper class and `pi::import...`/`pi::export...` C++ functions make new API mostly backward compatible with old JSON based graphs. It is possible to export/import graphs to run them on new or old APIs without many changes.
- `RXFactory` provides a way to create nodes just in time. Most used nodes with value and CPU/GPU have factory functions for easy and convenient creation. For usability purposes, value nodes factory methods return `RXValue`, instead of `RXNode`.
- High-performance `RXMemoryManager`, which provides kernel garbage collection, verbose logging, a detailed configuration, and advanced kernel caching mechanisms.
- `RXSession` is divided into 2 main subclasses.
`RXCPUSession` and `RXGLSession`, abstract `RXSession` provides a general user interface. The new session is the owner all kernels finalized or run in it.
- `RXContext` (which extends `RContext` abstract class) is the next word in the world of high-performance graphs. `RXContext` provides execution context for nodes and implements hash-based caching mechanisms. Old kernels should be fully compatible with new `RXContext`.
- `RXSwitch` and `RXIf` kernels which provide support for first-class graph branching in RX API. Unnecessary execution paths are skipped.
- Crossplatform high-performance lock-free thread pool pattern implementation in C++ `pi::ThreadPool`. 
- `std::async` like `pi::async` and `pi::deferred` functions for convenient working with `pi::ThreadPool` .
- `UnorderedRefKeyMap`, `RefKeyMap` and so on. Reference-based C++ fast-lookup containers which don't own data. 
- RX API and Kernel wrappers in `Java`/`Objective-C`.
- Many new utility kernels created for different purposes (`RAspectFit`, `RBufferToImage`, `RProportionalScaleSize`)
- `LOG_...` wrappers for Objective-C.

### Changed
- Old graph API is deprecated in favor of RX API.
- *DRAMATICAL* increase in Android `dispatch_parallel` performance achieved using `pi::ThreadPool`.
- *DRAMATICAL* increase in overall `OpenGL `rendering achieved with removing unnecessary CPU/GPU synchronization. 
- `RKernel` got first-class supports of RX GC (finalizers, gc references, needToDeallocate), hashing and branching mechanisms.
- `RGLImageKernel<T>` got `reshape` and `copyTo` implementations in Android.
- `RContext` became abstract. RXContex, R1Context (deprecated) are main implementations.
- Now library compiles with many enabled new warnings which make code safer, nicer to read and faster. 
- GNU++17 C++ standard is enabled by default in all projects.
- `LOG_FATAL` now throws exception which makes easier to recover from fatal errors and get benefits of RAII C++ paradigm.

### Removed
- No Changes



