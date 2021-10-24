
<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/138614033-5a32eb70-31f4-4bd0-8c46-3ede505ccca8.png">
  <br />
  Apple Silicon Guide
</h1>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614041-1877dd8c-8ff6-4e63-9a94-2390ac72a8f3.png">
<br />
Apple M1/M1 Pro/M1 Max Architectures.
</p>

#### A guide covering Apple Silicon including the applications, libraries and tools that will make you a better and more efficient with your Apple Silicon powered device.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**


# Table of Contents

1. [Getting Started](https://github.com/mikeroyal/Apple-Silicon-Guide#getting-started)

2. [Core ML Development](https://github.com/mikeroyal/Apple-Silicon-Guide#core-ml-development)

3. [Metal Development](https://github.com/mikeroyal/Apple-Silicon-Guide#Metal-development)

4. [Running Linux on the M1](https://github.com/mikeroyal/Apple-Silicon-Guide#running-linux-on-the-m1)

5. [Running Windows 10/11 on the M1](https://github.com/mikeroyal/Apple-Silicon-Guide#running-windows1011-on-the-m1)

6. [Gaming](https://github.com/mikeroyal/Apple-Silicon-Guide#gaming)

7. [Game Development](https://github.com/mikeroyal/Apple-Silicon-Guide#game-development)

8. [Professional Audio/Video Development](https://github.com/mikeroyal/Apple-Silicon-Guide#professional-audio-video-development)

9. [3D Graphics & Design](https://github.com/mikeroyal/Apple-Silicon-Guide#3d-graphics--design)

10. [Swift Development](https://github.com/mikeroyal/Apple-Silicon-Guide#swift-development)

11. [Objective-C Development](https://github.com/mikeroyal/Apple-Silicon-Guide#objective-c-development)

12. [C/C++ Development](https://github.com/mikeroyal/Apple-Silicon-Guide#cc-development)

# Getting Started
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Does it ARM? Apps that are reported to support Apple Silicon](https://doesitarm.com)

[M1 compatible games master list | AppleGamingWiki](https://www.applegamingwiki.com/wiki/M1_compatible_games_master_list)

[M1 Parallels Windows compatible games list | AppleGamingWiki](https://www.applegamingwiki.com/wiki/M1_Parallels_Windows_compatible_games_list)

[Apple Hypervisor](https://developer.apple.com/documentation/hypervisor) is a frameowrk that builds virtualization solutions on top of a lightweight hypervisor, without third-party kernel extensions. Hypervisor provides C APIs so you can interact with virtualization technologies in user space, without writing kernel extensions (KEXTs). As a result, the apps you create using this framework are suitable for distribution on the [Mac App Store](https://www.appstore.com/).

[Apple A-series](https://www.apple.com/) is Apple's 64-bit ARM-based system on a chip (SoC) used in their iPhones and iPads. Though, at WWDC 2020 it was announced that [Apple Silicon](https://developer.apple.com/documentation/apple_silicon) would [transition into Mac laptops](https://www.apple.com/newsroom/2020/06/apple-announces-mac-transition-to-apple-silicon/).

[Apple M1 Chip](https://www.apple.com/mac/m1/) is Apple's first SoC chip designed specifically for their ARM Mac products, it delivers incredible performance(8-core CPU and 8-core GPU), custom technologies, and great power efficiency. The M1 Chip is now availble for [Macbook Pro 13 with M1](https://www.apple.com/macbook-pro-13/), [Macbook Air 13 with M1](https://www.apple.com/macbook-air/), and [Mac Mini with M1](https://www.apple.com/mac-mini/).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614045-f20a4858-0460-49c1-8d80-0ae815e8bc93.png">
<br />
</p>

**M1 Chip. Source: [Apple](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/)**

[Apple M1 Pro Chip](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/) is a 8 or 10-core system-on-a-chip (SoC) architecture designed for pro systems in the [MacBook Pro 14”](https://www.apple.com/shop/buy-mac/macbook-pro/14-inch). The chip features fast unified memory, industry-leading performance per watt, and incredible power efficiency, along with increased memory bandwidth and capacity. The M1 Pro offers up to 200GB/s of memory bandwidth with support for up to 32GB of unified memory and a GPU (14-core or 16-core option).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614048-949a4fa8-71f8-4a2e-97fe-f8db874b3d13.png">
<br />
</p>

**M1 Pro Chip. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

[Apple M1 Max Chip](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/) is a 10-core system-on-a-chip (SoC) architecture designed for pro systems in the [MacBook Pro 16”](https://www.apple.com/shop/buy-mac/macbook-pro/16-inch). The chip features fast unified memory, industry-leading performance per watt, and incredible power efficiency, along with increased memory bandwidth and capacity. The M1 Pro offers up to 400GB/s of memory bandwidth with support for up to 64GB of unified memory and a GPU (16-core or 32-core option).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614049-eff86f41-cb0c-41c8-8a93-c9590b711227.png">
<br />
</p>

**M1 Max Chip. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614054-fc5dfb69-fa4e-4a1d-a39d-4145466a6a70.png">
<br />
</p>

**M1/ M1 Pro/ M1 Max CPU Performance. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614056-784f775d-2b4d-4273-99ab-6a1025157704.png">
<br />
</p>

**M1/ M1 Pro/ M1 Max GPU Performance. Source: [Apple](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/)**

[Xcode 12](https://developer.apple.com/xcode/) is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[Tensorflow_macOS](https://github.com/apple/tensorflow_macos) is a Mac-optimized version of TensorFlow and TensorFlow Addons for macOS 11.0+ accelerated using Apple's ML Compute framework.

[Universal App Quick Start Program](https://developer.apple.com/programs/universal/)

[Writing ARM64 Code for Apple Platforms](https://developer.apple.com/documentation/xcode/writing_arm64_code_for_apple_platforms)

[Porting Your macOS Apps to Apple Silicon](https://developer.apple.com/documentation/xcode/porting_your_macos_apps_to_apple_silicon)

[Building a Universal macOS Binary](https://developer.apple.com/documentation/xcode/building_a_universal_macos_binary)

[Addressing Architectural Differences in Your macOS Code](https://developer.apple.com/documentation/apple_silicon/addressing_architectural_differences_in_your_macos_code)

[Porting Just-In-Time(JIT) Compilers to Apple Silicon](https://developer.apple.com/documentation/apple_silicon/porting_just-in-time_compilers_to_apple_silicon)

[Porting Your Audio Code to Apple Silicon](https://developer.apple.com/documentation/audiounit/porting_your_audio_code_to_apple_silicon)

[Porting Your Metal Code to Apple Silicon](https://developer.apple.com/documentation/metal/porting_your_metal_code_to_apple_silicon)

[Tuning Your Code’s Performance for Apple Silicon](https://developer.apple.com/documentation/os/workgroups/tuning_your_code_s_performance_for_apple_silicon)

[Learn how Rosetta translates executables and what Rosetta can’t translate](https://developer.apple.com/documentation/apple_silicon/about_the_rosetta_translation_environment)

[Running Your iOS Apps on macOS](https://developer.apple.com/documentation/apple_silicon/running_your_ios_apps_on_macos)

[Adapting iOS Code to Run in the macOS Environment](https://developer.apple.com/documentation/apple_silicon/adapting_ios_code_to_run_in_the_macos_environment)

[Implementing Drivers, System Extensions, and Kexts](https://developer.apple.com/documentation/apple_silicon/implementing_drivers_system_extensions_and_kexts)

[Installing a Custom Kernel Extension](https://developer.apple.com/documentation/apple_silicon/installing_a_custom_kernel_extension)

[Debugging a Custom Kernel Extension](https://developer.apple.com/documentation/apple_silicon/debugging_a_custom_kernel_extension)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614058-cf6558fe-2805-4909-8aea-ef081b92f92f.png">
<br />
Devices powered by Apple Silicon.
</p>

[macOS](https://www.apple.com/macos/monterey-preview/) is an advanced desktop operating system (OS) for Apple's series of desktops and laptops.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821090-8d4a4380-cc4b-11eb-896a-74e1be0fb3c6.png">
<br />
</p>

**macOS Monterey. Source: [Apple](https://www.apple.com/macos/monterey/)**

[iOS](https://www.apple.com/ios/ios-15-preview/) is an advanced mobile operating system (OS) for Apple's series of iPhone products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821096-976c4200-cc4b-11eb-9006-641b1c99a9e7.png">
<br />
</p>

**iOS 15. Source: [Apple](https://www.apple.com/ios/ios-15/)**

[iPadOS](https://www.apple.com/ipados/ipados-preview/) is an advanced mobile operating system (OS) for Apple's series of iPad products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821093-93402480-cc4b-11eb-9a02-42e75c811c39.png">
<br />
</p>

**iPadOS 15. Source: [Apple](https://www.apple.com/ipados/ipados-15/)**

[WatchOS](https://www.apple.com/watchos/watchos-preview/) is an advanced mobile operating system (OS) for Apple's series of Watch products.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/121821100-9b985f80-cc4b-11eb-9c10-1e3aac33feda.png">
<br />
</p>

**WatchOS 8. Source: [Apple](https://www.apple.com/watchos/watchos-8/)**

# Core ML Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/132140794-0d4bf654-0884-4068-b5bb-eaee36c36797.png">
  <br />
</p>

## Core ML Learning Resources

[Core ML](https://developer.apple.com/documentation/coreml) is an Apple framework for integrating machine learning models into apps running on Apple devices (including iOS, watchOS, macOS, and tvOS). Core ML introduces a public file format (.mlmodel) for a broad set of ML methods including deep neural networks (both convolutional and recurrent), tree ensembles with boosting, and generalized linear models. Models in this format can be directly integrated into apps through Xcode.

[Introduction to Core ML](https://coremltools.readme.io/docs)

[Integrating a Core ML Model into your App](https://developer.apple.com/documentation/coreml/integrating_a_core_ml_model_into_your_app)

[Core ML Models](https://developer.apple.com/machine-learning/models/)

[Core ML API Reference](https://apple.github.io/coremltools/index.html)

[Core ML Specification](https://apple.github.io/coremltools/mlmodel/index.html)

[Apple Developer Forums for Core ML](https://developer.apple.com/forums/tags/core-ml)

[Top Core ML Courses Online | Udemy](https://www.udemy.com/topic/Core-ML/)

[Top Core ML Courses Online | Coursera](https://www.coursera.org/courses?query=core%20ml)

[IBM Watson Services for Core ML | IBM](https://www.ibm.com/watson/stories/coreml)

[Generate Core ML assets using IBM Maximo Visual Inspection | IBM](https://developer.ibm.com/technologies/iot/tutorials/ibm-maximo-visual-inspection-apple-devices/)

## Core ML Tools, Libraries, and Frameworks

[Core ML tools](https://coremltools.readme.io/) is a project that contains supporting tools for Core ML model conversion, editing, and validation.

[Create ML](https://developer.apple.com/machine-learning/create-ml/) is a tool that provides new ways of training machine learning models on your Mac. It takes the complexity out of model training while producing powerful Core ML models.

[Tensorflow_macOS](https://github.com/apple/tensorflow_macos) is a Mac-optimized version of TensorFlow and TensorFlow Addons for macOS 11.0+ accelerated using Apple's ML Compute framework.

[TensorFlow](https://www.tensorflow.org) is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

[Keras](https://keras.io) is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.It was developed with a focus on enabling fast experimentation. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[XGBoost](https://xgboost.readthedocs.io/) is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework. XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems in a fast and accurate way. It supports distributed training on multiple machines, including AWS, GCE, Azure, and Yarn clusters. Also, it can be integrated with Flink, Spark and other cloud dataflow systems.

[LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) is an integrated software for support vector classification, (C-SVC, nu-SVC), regression (epsilon-SVR, nu-SVR) and distribution estimation (one-class SVM). It supports multi-class classification.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.

[Apple Vision](https://developer.apple.com/documentation/vision) is a framework that performs face and face landmark detection, text detection, barcode recognition, image registration, and general feature tracking. Vision also allows the use of custom Core ML models for tasks like classification or object detection.

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[Cocoapods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

# Metal Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129622324-243aca6c-1feb-4b16-abef-70ad8b97f488.png">
  <br />
</p>

## Metal Learning Resources

[Metal](https://developer.apple.com/metal/) is a low-level API that provides a platform-optimized, low-overhead API for developing the latest 3D pro applications and amazing games using a rich shading language with tighter integration between graphics and compute programs. To help you do more while managing ever more complex shader code, Metal adds an unparalleled suite of advanced GPU debugging tools to help you realize the full potential of your graphics code.

[Apple Developer Documentation](https://developer.apple.com/documentation)

[MetalKit](https://developer.apple.com/documentation/metalkit/)

[Metal Shading Language Specification](https://developer.apple.com/metal/Metal-Shading-Language-Specification.pdf)

[Using Metal Feature Set Tables](https://developer.apple.com/documentation/metal/gpu_features/using_metal_feature_set_tables/)

[Metal Performance Shaders](https://developer.apple.com/documentation/metalperformanceshaders/)

[Optimizing Performance with the GPU Counters Instrument](https://developer.apple.com/documentation/metal/optimizing_performance_with_the_gpu_counters_instrument?language=objc)

[Enabling Frame Capture](https://developer.apple.com/documentation/metal/frame_capture_debugging_tools/enabling_frame_capture?language=objc)

[Reducing the Memory Footprint of Metal Apps](https://developer.apple.com/documentation/metal/reducing_the_memory_footprint_of_metal_apps)

[Metal Developer Tools for Windows](https://developer.apple.com/download/release/)

[Metal Sample code](https://developer.apple.com/metal/sample-code/)

[Metal plugin for TensorFlow](https://developer.apple.com/metal/tensorflow-plugin/)

[Metal Developer discussions](https://developer.apple.com/forums/tags/metal/)


## Metal Tools, Libraries, and Frameworks

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation) is a framework provides a base layer of functionality for apps and frameworks, including data storage and persistence, text processing, date and time calculations, sorting and filtering, and networking. The classes, protocols, and data types defined by Foundation are used throughout the macOS, iOS, watchOS, and tvOS SDKs.

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore) is a graphics rendering and animation infrastructure that provides high frame rates and smooth animations without burdening the CPU and slowing down your app.

[Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)is a framework based on the Quartz advanced drawing engine. It provides low-level, lightweight 2D rendering with unmatched output fidelity.

[Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics) is a framework that implements hardware-accelerated graphics for macOS running in a virtual machine, hereafter known as the guest. The macOS operating system provides a graphics driver that runs inside the guest, communicating with the framework in the host operating system to take advantage of Metal-accelerated graphics.

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[Cocoapods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

# Running Linux on the M1
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Hector Martin](https://github.com/marcan) has merged the initial support for Apple M1 hardware into the Linux SOC (System On a Chip) tree for [Linux Kernel 5.13](https://git.kernel.org/pub/scm/linux/kernel/git/soc/soc.git/commit/?h=for-next&id=0d5fe4b31785b732b71e764b55cda5c8d6e3bbbf). Also credit to developers [Sven Peter](https://github.com/svenpeter42) and [Alyssa Rosenzweig](https://github.com/alyssarosenzweig).

[Asahi Linux](https://asahilinux.org/) is a project and community with the goal of porting Linux to Apple Silicon Macs, starting with the 2020 M1 Mac Mini, MacBook Air, and MacBook Pro. Their goal is not just to make Linux run on these machines but to polish it to the point where it can be used as a daily OS.

[M1N1](https://github.com/AsahiLinux/m1n1) is a bootloader and experimentation playground for Apple Silicon.

[Apple Silicon to Apple Silicon VDM utility](https://github.com/AsahiLinux/macvdmtool) is a tool that lets you get a serial console on an Apple Silicon device and reboot it remotely, using only another Apple Silicon device running macOS and a standard Type C cable.

[Asahi GPU](https://github.com/AsahiLinux/gpu) is a repo that provides research for an open source graphics stack (3D acceleration) for Apple M1 chips.

[Asahi Linux Wiki](https://github.com/AsahiLinux/docs/wiki)

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110054441-f4349400-7d0f-11eb-8889-743009b33994.png">
  <br />
</h1>

# Running Windows 10/11 on the M1
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

[Parallels Desktop for Mac](https://www.parallels.com/products/desktop/) is a program that let's you runs Windows side-by-side with macOS (no restarting required) on your MacBook, MacBook Pro, iMac, iMac Pro, Mac mini or Mac Pro. Share files and folders, copy and paste images and text & drag and drop files between Mac and Windows applications.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880057-df697a80-8292-11eb-8484-9bbc02592377.jpg">
<br />
Parallels Desktop for Mac
</p>

[VMware Fusion](https://www.vmware.com/products/fusion.html) is a tool that allows you to run Windows, Linux, containers, Kubernetes and more in virtual machines (VMs) on M1 Mac device without rebooting.

[ARM64EC (“Emulation Compatible”)](https://docs.microsoft.com/en-us/windows/uwp/porting/arm64ec) is a new application binary interface (ABI) for Windows 11 on ARM that runs with native speed and is interoperable with x64 architecture. An app, process, or even a module can freely mix and match with ARM64EC and x64 as needed. The ARM64EC code in the app will run natively while any x64 code will run using Windows 11 on ARM’s built-in emulation. The ARM64EC ABI differs slightly from the current [ARM64 ABI](https://docs.microsoft.com/en-us/cpp/build/arm64-windows-abi-conventions?view=msvc-160) in ways that make it binary compatible with x64 code. Specifically, the ARM64EC ABI follows x64 software conventions including calling convention, stack usage, and data alignment, making ARM64EC and x64 interoperable. Apps built as ARM64EC may contain x64 code but do not have to, since ARM64EC is its own complete, first-class ABI for Windows.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124997795-20cf2400-e000-11eb-8954-4944286b8ea8.png">
  Windows 11 Desktop
</h3>

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/120387363-a9aabf80-c2de-11eb-84a5-8e4b422e7546.png">
  Windows 10 Desktop
</h3>

# Gaming
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

## Apple Arcade

[Apple Arcade](https://www.apple.com/apple-arcade/) is a game subscription service that gives up to six family members unlimited access to 100+ incredibly fun games, all with no ads and no in-app purchases.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112693074-377cb100-8e3d-11eb-910c-1095c91da6d5.png">
</p>

## Steam

[Get Steam](https://store.steampowered.com/about/)

 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">

 [Steam Link app](https://store.steampowered.com/steamlink/about) is available free of charge, streaming your Steam PC games to phones, tablets, and TV.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692999-14ea9800-8e3d-11eb-964a-6bee4e665900.png">
</p>

## Game Streaming

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/) is NVIDIA's Cloud Gaming Service.

 <img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Moonlight Game Streaming](https://moonlight-stream.org/) is a program that let you stream from your PC games over the Internet with no configuration required. Stream from almost any device, whether you're in another room or miles away from your gaming rig.
<img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">

[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) is a Free and Open Source Software Client for PlayStation 4 and PlayStation 5 Remote Play for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms.

[Xbox Project xCloud](https://www.xbox.com/en-US/xbox-game-streaming/project-xcloud) is Microsoft's cloud-based Xbox game-streaming technology **(currently in Beta)**. **Play games like Forza Horizon 4, Halo 5: Guardians, Gears of War 4, Sea of Thieves, Cuphead, Red Dead Redemption 2, and 100+ other games on your mobile device or Chrome web browser**. Microsoft's Xbox Project xCloud does require an [Xbox Game Pass Ultimate](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming) subscription.

<img src="https://user-images.githubusercontent.com/45159366/108111388-74d56e00-7049-11eb-8aeb-3e5d65f9e832.png">

[Amazon Luna](https://www.amazon.com/luna/landing-page) is Amazon's Cloud Gaming Service. Amazon Luna is Compatible/Supported on a vartiey of [Devices and Browsers](https://www.amazon.com/gp/help/customer/display.html?nodeId=GUFHUSX8X324T4XE).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112693072-364b8400-8e3d-11eb-9df0-d58af7ac9c9c.png">
</p>

## Game Emulators

[RetroArch](https://www.retroarch.com/) is a frontend for emulators, game engines and media players. It enables you to run classic games on a wide range of computers and consoles through its slick graphical interface. Settings are also unified so configuration is done once and for all.

[Dolphin](https://dolphin-emu.org) is an emulator for two recent Nintendo video game consoles: the GameCube and the Wii. It allows PC gamers to enjoy games for these two consoles in full HD (1080p) with several enhancements: compatibility with all PC controllers, turbo speed, networked multiplayer, and even more.

[Citra](https://citra-emu.org/) is an open-source emulator for the Nintendo 3DS capable of playing many of your favorite games.

[yuzu](https://yuzu-emu.org) is an experimental open-source emulator for the Nintendo Switch from the creators of Citra.

[DOSBox](https://www.dosbox.com/) is an open-source DOS emulator which primarily focuses on running DOS Games.

[MAME](https://www.mamedev.org/) is a Arcade Machine Emulator.

[xemu](https://xemu.app/) is an original Xbox emulator.


## Performance Benchmarks

[Geekbench 5](https://www.geekbench.com/download/) is a cross-platform benchmark that measures your system's performance with the press of a button.

[Phoronix Test Suite](https://www.phoronix-test-suite.com/)

[UNIGINE Superposition](https://benchmark.unigine.com/superposition) is an extreme performance and stability test for PC hardware: video card, power supply, cooling system.

<img src="https://user-images.githubusercontent.com/45159366/107092007-8f8d2480-67b7-11eb-9c3f-a0cb02e6dfcd.png">

# Game Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97361059-45151700-185c-11eb-9d12-dae51c79eb8a.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279021-ea6b5000-bbdd-11eb-9f59-5251fc3ac751.png">
  <br />
</p>

## Game Engines

**[Checkout the Unity Engine](https://unity.com/)**

<img src="https://user-images.githubusercontent.com/45159366/104788113-3432be00-5746-11eb-99b1-49360669f327.png">


**[Checkout the Unreal Engine 4](https://www.unrealengine.com/)**

<img src="https://user-images.githubusercontent.com/45159366/104788122-37c64500-5746-11eb-8f61-48a69b94582d.png">


**[Checkout the CryEngine](https://www.cryengine.com/)**

<img src="https://user-images.githubusercontent.com/45159366/104788177-680de380-5746-11eb-9fc2-6d6f0bdc0a82.png">


**[Checkout the Godot Engine](https://godotengine.org/)**

[If you would like to Donate to the Godot Project](https://www.patreon.com/godotengine)

<img src="https://user-images.githubusercontent.com/45159366/104788134-3f85e980-5746-11eb-94c4-d97165ee888b.jpeg">


**[Checkout Blender](https://www.blender.org/)**

[If you would like to Donate to the Blender Project](https://fund.blender.org/)

<img src="https://user-images.githubusercontent.com/45159366/104788139-401e8000-5746-11eb-9647-058dee01a00e.png">


**[Checkout AWS Lumberyard(based on CryEngine)](https://aws.amazon.com/lumberyard/)**

<img src="https://user-images.githubusercontent.com/45159366/104788145-43b20700-5746-11eb-82f1-1351c3b7e380.png">


**[Checkout Game Maker Studio 2](https://www.yoyogames.com/gamemaker)**

<img src="https://user-images.githubusercontent.com/45159366/104788147-44e33400-5746-11eb-879a-bc6239c98ce4.jpg">


## Game Development Learning Resources

[Unreal Online Learning](https://www.unrealengine.com/en-US/onlinelearning-courses) is a free learning platform that offers hands-on video courses and guided learning paths.

[Unreal Engine Authorized Training Program](https://www.unrealengine.com/en-US/training-partners)

[Unreal Engine for education](https://www.unrealengine.com/en-US/education/)

[Unreal Engine Training & Simulation](https://www.unrealengine.com/en-US/industry/training-simulation)

[Unity Certifications](https://unity.com/products/unity-certifications)

[Autodesk for Games](https://www.autodesk.com/campaigns/autodesk-for-games)

[Getting Started with DirectX 12 Ultimate](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

[Getting Started with Vulkan](https://www.khronos.org/vulkan/)

[Getting Started with Apple Metal](https://developer.apple.com/metal/)

[Game Design Online Courses from Udemy](https://www.udemy.com/courses/Design/Game-Design/)

[Game Design Online Courses from Skillshare](https://www.skillshare.com/browse/game-design)

[Learn Game Design with Online Courses and Classes from edX](https://www.edx.org/learn/game-design)

[Game Design Courses from Coursera](https://www.coursera.org/courses?query=game%20design)

[Game Design and Development Specialization Course from Coursera](https://www.coursera.org/specializations/game-development)

## Game Development Tools

[Unreal Engine](https://www.unrealengine.com) is a game engine developed by Epic Games with the world's most open and advanced real-time 3D creation tool. Continuously evolving to serve not only its original purpose as a state-of-the-art game engine, today it gives creators across industries the freedom and control to deliver cutting-edge content, interactive experiences, and immersive virtual worlds.

[Unity](https://unity.com) is a cross-platform game development platform. Use Unity to build high-quality 3D and 2D games, deploy them across mobile, desktop, VR/AR, consoles or the Web, and connect with loyal and enthusiastic players and customers.

[Unigine](https://unigine.com) is a cross-platform game engine designed for development teams (C++/C# programmers, 3D artists) working on interactive 3D apps.

[Panda3D](https://www.panda3d.org/) is a game engine, a framework for 3D rendering and game development for Python and C++ programs, developed by Disney and CMU. Panda3D is open-source and free for any purpose, including commercial ventures.

[Source 2](https://developer.valvesoftware.com/wiki/Source_2) is a 3D video game engine in development by Valve as a successor to Source. It is used in Dota 2, Artifact, Dota Underlords, parts of The Lab, SteamVR Home, and Half-Life: Alyx.

[Havok](https://www.havok.com/) is a middleware software suite that provides a realistic physics engine component and related functions to video games. It is supported  and optimized across all major platforms, including Nintendo Switch, PlayStation®, Stadia, and Xbox. Along with integrations for Unity and Unreal Engine and are used in countless proprietary game engines.

[AutoDesk 3ds Max](https://www.autodesk.com/products/3ds-max/overview) is a professional software program for 3D modeling, animation, rendering, and visualization. 3ds Max allows you to create stunning game environments, design visualizations, and virtual reality experiences.

[Houdini](https://www.sidefx.com/) is a 3D procedural software for modeling, rigging, animation, VFX, look development, lighting and rendering in film, TV, advertising and video game pipelines.

[A-Frame](https://aframe.io) is a web framework for building virtual reality experiences in WebVR with HTML and Entity-Component. A-Frame works on Vive, Rift, desktop, mobile platforms.

[AppGameKit](https://www.appgamekit.com) is a powerful game development engine, ideal for Hobbyist and Indie developers. Where you can start coding in the easy to learn AppGameKit BASIC or use the libraries in C++ & XCode.

[Amazon Lumberyard](https://aws.amazon.com/lumberyard/) is an open source, AAA game engine(based on CryEngine) that gives you the tools you need to create high quality games. Deeply integrated with AWS and Twitch, Amazon Lumberyard includes full source code, allowing you to customize your project at any level.

[Blender](https://www.blender.org) is the free and open source 3D creation suite. It supports the entirety of the 3D pipeline—modeling, rigging, animation, simulation, rendering, compositing and motion tracking, video editing and 2D animation pipeline.

[CryEngine](https://www.cryengine.com) is a powerful real-time game development platform created by Crytek.

[GameMaker Studio 2](https://www.yoyogames.com/gamemaker) is the latest and greatest incarnation of GameMaker. It has everything you need to take your idea from concept to finished game. With no barriers to entry and powerful functionality, GameMaker Studio 2 is the ultimate 2D development environment.

[Godot](https://godotengine.org) is a feature-packed, cross-platform game engine to create 2D and 3D games from a unified interface. It provides a comprehensive set of common tools, so that users can focus on making games without having to reinvent the wheel. Games can be exported in one click to a number of platforms, including the major desktop platforms (Linux, Mac OSX, Windows) as well as mobile (Android, iOS) and web-based (HTML5) platforms.

[Open Graphics Library(OpenGL)](https://www.opengl.org/) is an API used acrossed mulitple  programming languages and platforms for hardware-accelerated rendering of 2D/3D vector graphics currently developed by the [Khronos Group](https://www.khronos.org/).

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[OpenGL Shading Language(GLSL)](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL)) is a High Level Shading Language based on the C-style language, so it covers most of the features a user would expect with such a language.  Such as control structures (for-loops, if-else statements, etc) exist in GLSL, including the switch statement.

[High Level Shading Language(HLSL)](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl) is the High Level Shading Language for DirectX. Using HLSL, the user can create C-like programmable shaders for the Direct3D pipeline. HLSL was first created with DirectX 9 to set up the programmable 3D pipeline.

[DirectX 12 Ultimate](https://github.com/Microsoft/DirectX-Graphics-Samples) is an API(for high performance 2D & 3D graphics) from Microsoft. DirectX 12 Ultimate brings support for ray tracing, mesh shaders, variable rate shading, and sampler feedback. Available in Windows 2004 version(May 2020 Update).

[Vulkan](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Metal](https://developer.apple.com/metal/) is a low-level GPU programming framework used for rendering 2D and 3D graphics on Apple platforms such as iOS, iPadOS, macOS, watchOS and tvOS.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

[OpenGL ES](https://www.khronos.org/opengles/) is the mobile subset of OpenGL. It's supported on all major mobile platforms, and is also the base for WebGL.

[OpenCL](https://www.khronos.org/opencl/) is a framework for writing programs that execute across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs and other processors or hardware accelerators.

[EGL](https://www.khronos.org/egl/) is an interface between Khronos rendering APIs such as OpenGL or OpenVG and the underlying native platform window system.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/) is the Video Decode and Presentation API for UNIX. It provides an interface to video decode acceleration and presentation hardware present in modern GPUs.

[VA API](https://freedesktop.org/wiki/Software/vaapi/) is an open-source library and API specification, which provides access to graphics hardware acceleration capabilities for video processing.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation) is an extension of the X video extension (Xv) for the X Window System. The XvMC API allows video programs to offload portions of the video decoding process to the GPU hardware.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[LibGDX](https://github.com/libgdx/libgdx) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

[cocos2d-x](https://github.com/cocos2d/cocos2d-x) is a multi-platform framework for building 2d games, interactive books, demos and other graphical applications. It is based on cocos2d-iphone, but instead of using Objective-C, it uses C++. It works on iOS, Android, macOS, Windows and Linux.

[MonoGame](https://github.com/MonoGame/MonoGame) is a framework for creating powerful cross-platform games. The spiritual successor to XNA with thousands of titles shipped across desktop, mobile, and console platforms. MonoGame is a fully managed .NET open source game framework without any black boxes.

[Three.js](https://threejs.org) is a cross-browser JavaScript library and application programming interface used to create and display animated 3D computer graphics in a web browser using WebGL.

[Superpowers](http://superpowers-html5.com/) is a downloadable HTML5 app for real-time collaborative projects . You can use it solo like a regular offline game maker, or setup a password and let friends join in on your project through their Web browser.

[URHO3D](https://urho3d.github.io/) is a free lightweight, cross-platform 2D and 3D game engine implemented in C++ and released under the MIT license. Greatly inspired by OGRE and Horde3D.

[Vivox](https://www.vivox.com/) is a voice & text chat platform that's trusted by the world's biggest gaming brands and titles such as Fortnite, PUBG, League of Legends, and Rainbow Six Siege.

[HGIG](https://www.hgig.org/) is a volunteer group of companies from the game and TV display industries that meet to specify and make available for the public guidelines to improve consumer gaming experiences in HDR.

[GameBlocks](https://www.gameblocks.com/) is a Server Side Anti-Cheat & Middleware software.

## Augmented Reality (AR) & Virtual Reality (VR)

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[ARCore](https://developers.google.com/ar/) is a software development kit developed by Google that allows for augmented reality applications in the real world. These tools include environmental understanding, which allows devices to detect horizontal and vertical surfaces and planes. It also includes motion tracking, which lets phones understand and track their positions relative to the world. Also ARCore’s Light Estimation API lets your digital objects appear realistically as if they’re actually part of the physical world.

[OpenVR](https://github.com/ValveSoftware/openvr) is an API and runtime that allows access to VR hardware(Steam Index, HTC Vive, and Oculus Rift) from multiple vendors without requiring that applications have specific knowledge of the hardware they are targeting.

[OpenVR Benchmark on Steam](https://store.steampowered.com/app/955610/OpenVR_Benchmark/) is the first benchmark tool for reproducibly testing your real VR performance, rendering inside of your VR headset.

[OpenHMD](http://www.openhmd.net/) is open source API and drivers that supports a wide range of HMD(head-mounted display) devices such as Oculus Rift, HTC Vive, Sony PSVR, and others.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR—platforms and devices.

[Monado](https://monado.dev/) is the first OpenXR™ runtime for GNU/Linux. Monado aims to jump-start development of an open source XR ecosystem and provide the fundamental building blocks for device vendors to target the GNU/Linux platform.

[Libsurvive](https://github.com/cntools/libsurvive) is a set of tools and libraries that enable 6 dof tracking on lighthouse and vive based systems that is completely open source and can run on any device. It currently supports both SteamVR 1.0 and SteamVR 2.0 generation of devices and should support any tracked object commercially available.

[Simula](https://github.com/SimulaVR/Simula) is a VR window manager for Linux that runs on top of Godot. It takes less than 1 minute to install. Simula is officially compatible with SteamVR headsets equipped with Linux drivers (e.g. HTC Vive, HTC Vive Pro, & Valve Index). We have also added experimental support to OpenXR headsets that have Monado drivers (e.g. North Star, OSVR HDK, and PSVR). Some people have gotten the Oculus Rift S to run Simula via OpenHMD ([see here](https://github.com/OpenHMD/OpenHMD/issues/225#issuecomment-638454156)).

# Professional Audio/Video Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/100922475-caf73400-3492-11eb-88ac-d0976f3057d3.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119560582-f62f5180-bd58-11eb-842b-fcf4330f3e2f.png">
  <br />
</p>

## Audio/Video Learning Resources

[10 Video Production Tools That Make the Difference Between a Good Video and a Bad One by Dann Albright ](https://www.uscreen.tv/blog/video-production-equipment/)

[Online Audio Editing Classes from Skillshare](https://www.skillshare.com/browse/audio-editing)

[Online Video Editing Classes Skillshare](https://www.skillshare.com/search?query=Video-Editing)

[Video Editing Courses from Udemy](https://www.udemy.com/topic/video-editing/)

[Audio Editing Courses from udemy](https://www.udemy.com/topic/audio-editing/)

[Video Editing Courses from Coursera](https://www.coursera.org/courses?query=video%20editing)

[The Basics of Audio Editing from Coursera](https://www.coursera.org/lecture/vocal-production/basic-audio-editing-6JLBJ)

[Audacity Podcast Production Course: Audio Editing for Podcasters](https://www.thepodcasthost.com/academy/course-library/audacity-course/)

[Video Editing Online Training Courses from LinkedIn Learning](https://www.linkedin.com/learning/topics/video-editing)

[Audio Editing Online Training Courses from LinkedIn Learning](https://www.linkedin.com/learning/topics/audio-editing)

## Audio/Video Tools and Equipment

[H.264(AVC)](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC) is a video compression standard based on block-oriented and motion-compensated integer-DCT coding that defines multiple profiles (tools) and levels (max bitrates and resolutions) with support up to 8K.

[H.265(HEVC)](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding) is a video compression standard that is the successor to H.264(AVC). It offers a 25% to 50% better data compression at the same level of video quality, or improved video quality at the same bit-rate.

[FFmpeg](https://ffmpeg.org) is a leading multimedia framework that can decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge ones on multiple platforms such as Windows, macOS, and Linux.

[HandBrake](https://handbrake.fr/) is a tool for transcoding video from almost any format with a selection of widely supported codecs. It is supported on Window, macOS, and Linux.

[HTTP Live Streaming (HLS)](https://developer.apple.com/streaming/) is a communications protocol developed by Apple that sends live and on‐demand audio and video to iPhone, iPad, Mac, Apple Watch, Apple TV, and PC.

[Dynamic Adaptive Streaming over HTTP (DASH)](https://developer.mozilla.org/en-US/docs/Web/HTML/DASH_Adaptive_Streaming_for_HTML_5_Video) is an adaptive streaming protocol that allows for a video stream to switch between bit rates on the basis of network performance, in order to keep a video playing.

[OpenMAX™](https://www.khronos.org/openmax/) is a cross-platform API that provides comprehensive streaming media codec and application portability by enabling accelerated multimedia components to be developed, integrated and programmed across multiple operating systems and silicon platforms.

[GStreamer](https://gstreamer.freedesktop.org/) is a library for constructing graphs of media-handling components. The applications it supports range from simple Ogg/Vorbis playback, audio/video streaming to complex audio (mixing) and video (non-linear editing) processing. Applications can take advantage of advances in codec and filter technology transparently.

[Media Source Extensions (MSE)](https://www.w3.org/TR/media-source/) is a [W3C specification](https://github.com/w3c/media-source) that allows JavaScript to send byte streams to media codecs within Web browsers that support HTML5 video and audio. Also, this allows the implementation of client-side prefetching and buffering code for streaming media entirely in JavaScript.

[WebRTC](https://webrtc.org/) is an open-source project that adds real-time communication capabilities to your application that works on top of an open standard. It supports video, voice, and generic data to be sent between peers, allowing developers to build powerful voice- and video-communication solutions.

[Apple ProRes](https://support.apple.com/en-us/HT200321) is a codec technology developed by Apple for high-quality & high-performance editing in Final Cut Pro that supports up to 8K.

[Premiere Pro](https://www.adobe.com/products/premiere.html) is the industry-leading video editing software for film, TV, and the web. Creative tools, integration with other apps and services, and the power of Adobe Sensei help you craft footage into polished films and videos. With [Premiere Rush](https://www.adobe.com/products/premiere-rush.html) you can create and edit new projects from any device.

[Final Cut Pro](https://www.apple.com/final-cut-pro/) is Apple's professional grade video editing software.

[Kdenlive](https://kdenlive.org/en/) is an open source video editing tool that supports unlimited multimedia files. It's based on the MLT Framework, KDE and Qt. People who are looking for a very versatile video editing tool that comes packed with features. The latest 20.08 release is out with nifty features like Interface Layouts, Multiple Audio Stream support, Cached data management and Zoombars in the Clip Monitor and Effects Panel but one may argue that the highlights of this release are stability and interface improvements.

[OpenShot](https://www.openshot.org/) is an open-source video editing tool that's designed for users new in the editing environment. It has simple features such as a simple drag-and-drop function, it provides an easy-to-use and quick-to-learn user interface. The powerful video editor offers tons of efficient ways to cut and trim down your videos. You can freely utilize the unlimited tracks, video effects engine, title editor, 3D animations, slow motion, and time effects. It supports commonly used video codecs that are supported by FFmpeg like WebM (VP9), AVCHD (libx264), HEVC (libx265) and audio codecs like mp3 (libmp3lame) and aac (libfaac). The program can render MPEG4, ogv, Blu-ray and DVD video, and Full HD videos for uploading to the internet video websites like YouTube.

[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/) is the world’s only solution that combines professional 8K editing, color correction, visual effects and audio post production all in one software tool! You can instantly move between editing, color, effects, and audio with a single click. DaVinci Resolve Studio is also the only solution designed for multi user collaboration so editors, assistants, colorists, VFX artists and sound designers can all work live on the same project at the same time.

[Blender](https://www.blender.org/features/video-editing/) comes with a built-in video sequence editor allows you to perform basic actions like video cuts and splicing, as well as more complex tasks like video masking or color grading. The Video Editor includes: Live preview, luma waveform, chroma vectorscope and histogram displays. Audio mixing, syncing, scrubbing and waveform visualization.

[Lightworks](https://www.lwks.com/) is a non-linear video editing appluication for editing and mastering digital video used by the film industry. Its professional edition has been used for box office hits, such as Shutter Island, Pulp Fiction, and Mission Impossible. Intimidating user interface. Like professional video editors, such as Adobe Premiere Pro, Lightworks is rather complicated to use for new users.

[Shotcut](https://www.shotcut.org/) is an open source multi-platform video editor. You can perform various actions such as video editing (including 4K video quality), add effects, create new movies, import most image files formats, export to almost any file format and much more.

[Olive](https://www.olivevideoeditor.org) is a free non-linear video editor aiming to provide a fully-featured alternative to high-end professional video editing software.

[OBS (Open Broadcaster Software)](https://obsproject.com/) is free and open source software for video recording and live streaming. Stream to Twitch, YouTube and many other providers or record your own videos with high quality H264 / AAC encoding.

[REAPER](https://www.reaper.fm/) is a complete digital audio production application for computers, offering a full multitrack audio and MIDI recording, editing, processing, mixing and mastering toolset.REAPER supports a vast range of hardware, digital formats and plugins, and can be comprehensively extended, scripted and modified.

[Logic Pro](https://www.apple.com/logic-pro/) is a digital audio workstation (DAW) and MIDI sequencer software application for macOS.

[Ableton Live](https://www.ableton.com/live) is a digital audio workstation application. It's designed to be an instrument for live performances as well as a tool for composing, recording, arranging, mixing, and mastering.

[Bitwig Studio](https://www.bitwig.com) is a digital audio workstation that has linear and non-linear workflows for sound design, recording, live performance, and more. Along with 90+ instruments, effects, and other creative tools. It is supported Windows, macOS, and Linux.

[SonoBus](https://sonobus.net) is an easy to use application for streaming high-quality, low-latency peer-to-peer audio between devices over the internet or a local network.

[Avid Pro Tools](https://www.avid.com/pro-tools) is a digital audio workstation for mixing Dolby Atmos or other 3D audio for film or TV, working in a large mixing stage or a small editing suite.

[Adobe Audition](https://www.adobe.com/products/audition.html) is a digital audio workstation with tools for color, audio, and graphics, Premiere Pro works seamlessly with other apps and services, including After Effects, Adobe Audition, and Adobe Stock.

[JACK Audio Connection Kit AKA JACK](https://jackaudio.org/) is a professional sound server daemon that provides real-time, low-latency connections for both audio and MIDI data between applications that implement its API. JACK can be configured to send audio data over a network to a main machine, which then outputs the audio to a physical device. This can be useful to mix audio from a number of linked computers without requiring additional cables or hardware mixers, and keeping the audio path digital for as long as possible.

[JACK2](https://github.com/jackaudio/jack2) is a C++ version of the JACK low-latency audio server for multi-processor machines. It is a new implementation of the JACK server core features that aims at removing some limitations of the JACK1 design. The activation system has been changed for a data flow model and lock-free programming techniques for graph access have been used to have a more dynamic and robust system.

[Image-Line FL Studio](https://www.image-line.com/fl-studio/) is a digital audio workstation for mixing audio and music sequencing developed by Image-Line.

[Propellerhead Reason](https://www.reasonstudios.com/) is a digital audio workstation with tools you need for creative music production, recording, sequencing and mixing.

[Cockos Reaper](https://www.cockos.com/reaper/) is a full, flexible feature set digital audio workstation with tools used for commercial/home studios, broadcast, location recording, education, science/research, sound design, game development, and more.

[PreSonus Studio One](https://www.presonus.com/products/studio-one) is a digital audio workstation application, used to create, record, mix and master music and other audio.

[Steinberg Cubase](https://new.steinberg.net/cubase/) is a digital audio workstation developed by Steinberg for music/MIDI recording and arranging/editing of audio.

[Digital Performer](https://motu.com/products/software/dp/) is a digital audio workstation and music sequencer software package. It's can recording, editing, arranging, mixing, mastering, MIDI, and more. Digital Performer will take your music to its highest level, thanks to sophisticated features like Stretch Audio (powered by Zynaptiq’s ZTX PRO technology), live triggering and looping.

[Sonic Visualiser](https://www.sonicvisualiser.org) is a free, open-source application for Windows, Linux, and Mac, designed to be the first program you reach for when want to study a music recording closely.

[PipeWire](https://pipewire.org) is a server and user space API to deal with multimedia pipelines.It provides a low-latency, graph based processing engine on top of audio and video devices that can be used to support the use cases currently handled by both pulseaudio and JACK. PipeWire was designed with a powerful security model that makes interacting with audio and video devices from containerized applications easy. Nodes in the graph can be implemented as separate processes, communicating with sockets and exchanging multimedia content using fd passing.

[LMMS](https://lmms.io/) is an open source digital audio workstation application program. When LMMS is pairedr with appropriate computer hardware, it allows music to be produced by arranging samples, synthesizing sounds, playing on a MIDI keyboard, and combining the features of trackers and sequencers. Developed by Paul Giblock and Tobias Junghans, this program stands for "Linux MultiMedia Studio" and supports handy plugins that enables it to work on different operating systems.

[Ardour](http://ardour.org/) is an open source, collaborative effort of a worldwide team including musicians, programmers, and professional recording engineers. Development is transparent — anyone can watch our work as it happens. Like a good piece of vintage hardware, you can open the box and look inside.

[Audacity](https://www.audacityteam.org/) is an easy-to-use, multi-track audio editor and recorder for Windows, Mac OS X, GNU/Linux and other operating systems. Developed by a group of volunteers as open source and offered free of charge. Amazing support community.

# 3D Graphics and Design
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/97116104-27a74800-16b8-11eb-9556-bdb90ba45ce7.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126396094-16e1b14c-e1a2-4086-803d-5a8d99edeade.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338215-6ec91f00-b4ca-11eb-9c9e-f5cf377ca3c4.png">
  <br />
</p>

 **Blender's Cycles Render Engine. Source: [Blender](https://www.blender.org)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338217-6ffa4c00-b4ca-11eb-92d0-9aa30230495d.png">
  <br />
</p>

 **Blender VFX(Visual Effects). Source: [Blender](https://www.blender.org)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338223-72f53c80-b4ca-11eb-8100-2e2abd98c910.png">
  <br />
</p>

**Designing a simple UI/UX for an application in Adobe XD. Source: [Adobe](https://www.adobe.com/products/xd.html)**

## 3D Graphics and Design Learning Resources

[Introduction to Pixar's Universal Scene Description (USD)](https://graphics.pixar.com/usd/docs/index.html)

[Intro to using Universal Scene Description with NVIDIA](https://developer.nvidia.com/usd)

[First steps with Universal Scene Description in Blender](https://code.blender.org/2019/07/first-steps-with-universal-scene-description/)

[AMD Radeon ProRender Developer Suite](https://gpuopen.com/radeon-prorender-suite/)

[Blender Foundation](https://www.blender.org/foundation/)

[Blender Foundation Certification Training](https://www.blender.org/certification/)

[Blender Cloud Courses](https://cloud.blender.org/courses)

[Blender Institute](https://www.blender.org/institute/)

[Blender Education](https://www.blender.org/get-involved/)

[Blender Network](https://www.blendernetwork.org/)

[Blender Courses from Udemy](https://www.udemy.com/topic/blender/)

[AutoDesk Learning, Training & Certification](https://www.autodesk.com/training)

[AutoDesk Design Academy](https://academy.autodesk.com)

[AutoDesk Courses and Specializations from Coursera](https://www.coursera.org/autodesk)

[Cinema 4D Quick Tips](https://www.cineversity.com/vidplaylist/cinema_4d_quick_tips)

[Getting Started with Cinema 4D](https://www.cineversity.com/vidplaylist/getting_started_with_cinema_4d_r20)

[Graphic Design Masterclass(Photoshop, Illustrator, InDesign) from Udemy](https://www.udemy.com/course/graphic-design-masterclass-everything-you-need-to-know/)

[Vectr: Beginner's Guide To Graphic Design from udemy](https://www.udemy.com/course/vectr-beginners-guide-to-graphic-design/)

[Canva MasterClass: Design For EveryDay Use from Udemy](https://www.udemy.com/course/canva-masterclass-design-for-everyday-use/)


## 3D Graphics and Design Tools

[Adobe Creative Cloud](https://www.adobe.com/creativecloud.html) is a collection of 20+ desktop and mobile apps(Lightroom, Photoshop, Illustrator, InDesign, Rush, Etc.) and services for photography, design, video, web, UX, and more.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/126396097-921982e9-5b6b-4f1e-90f3-9b7033eeb9ca.png">
  <br />
</p>

[Autodesk®](https://www.autodesk.com/) is a collection of professional software products and services used in 3D design, architecture, engineering, manufacturing, and high production entertainment companies.

[Maya®](https://www.autodesk.com/products/maya/overview) is a 3D computer animation, modeling, simulation, and rendering software that can create realistic effects from explosions to cloth simulation.

[Maya LT™](https://www.autodesk.com/products/maya-lt/overview) is a game design software for indie game makers that can create and animate realistic-looking characters, props, and environments using the sophisticated 3D modeling and animation tools.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687226-2a682780-d1ca-11eb-9408-4b32ddc7d493.png">
  <br />
</p>

**Autodesk® Maya. Source:[Autodesk](https://www.autodesk.com/products/maya/overview)**

[3DS Max®](https://www.autodesk.com/products/3ds-max/overview) is a 3D modeling and rendering software for design visualization, games, and animation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687233-3358f900-d1ca-11eb-8e9c-0cb68b16db0e.png">
  <br />
</p>

**Autodesk® 3DS Max. Source:[Autodesk](https://www.autodesk.com/products/3ds-max/overview)**

[Arnold](https://www.autodesk.com/products/arnold/overview) is an advanced Monte Carlo ray tracing(Global illumination) renderer that helps you work more efficiently.

[ReCap™](https://www.autodesk.com/products/recap/overview) is a Pro 3D scanning software to transform the physical world into a digital asset. With reality capture data you can better understand and verify existing and as-built conditions to gain insights and make better decisions.

[Flame®](https://www.autodesk.com/products/flame/overview) is a 3D VFX and finishing software provides powerful tools for 3D compositing, visual effects, and editorial finishing. An integrated, creative environment means faster compositing, advanced graphics, color correction, and more.

[Mudbox®](https://www.autodesk.com/products/mudbox/overview) is a 3D digital painting and sculpting software that let's you sculpt and paint highly detailed 3D geometry and textures.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687228-2e944500-d1ca-11eb-894e-b55e15c35620.png">
  <br />
</p>

**Autodesk® Mudbox. Source:[Autodesk](https://www.autodesk.com/products/mudbox/overview)**

[Blender](https://www.blender.org) is a professional, free and open-source 3D computer graphics software toolset used for creating animated films, visual effects, art, 3D printed models, interactive 3D applications and video games.

[Cinema 4D](https://www.maxon.net/en-us/products/cinema-4d/overview/) is a professional 3D and VFX software suite that is capable of doing procedural and polygonal modeling, animation, lighting, texturing, motion graphic and rendering.

[Houdini](https://www.sidefx.com/) is a 3D procedural software for modeling, rigging, animation, VFX, look development, lighting and rendering in film, TV, advertising and video game pipelines.

[Open Graphics Library(OpenGL)](https://www.opengl.org/) is an API used acrossed mulitple  programming languages and platforms for hardware-accelerated rendering of 2D/3D vector graphics currently developed by the [Khronos Group](https://www.khronos.org/).

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[Vulkan](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Metal](https://developer.apple.com/metal/) is a low-level GPU programming framework used for rendering 2D and 3D graphics on Apple platforms such as iOS, iPadOS, macOS, watchOS and tvOS.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

[OpenGL ES](https://www.khronos.org/opengles/) is the mobile subset of OpenGL. It's supported on all major mobile platforms, and is also the base for WebGL.

[OpenCL](https://www.khronos.org/opencl/) is a framework for writing programs that execute across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs and other processors or hardware accelerators.

[Vuforia](https://developer.vuforia.com/) is a comprehensive, scalable enterprise AR platform. Our wide-ranging solution suite ensures that we can provide the right AR technology to every customer based on their business needs.

[Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio) is a tool that allows anyone to create beautiful 3D augmented reality (AR) experiences in a matter of minutes with no coding required.

[OpenVX™](https://www.khronos.org/openvx/) is an open-source, royalty-free standard for cross platform acceleration of computer vision applications. OpenVX enables performance and power-optimized computer vision processing, especially important in embedded and real-time use cases such as face, body and gesture tracking, smart video surveillance, advanced driver assistance systems (ADAS), object and scene reconstruction, augmented reality, visual inspection, robotics and more.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR—platforms and devices.

[GPUImage framework](https://github.com/BradLarson/GPUImage) is a BSD-licensed iOS library that lets you apply GPU-accelerated filters and other effects to images, live camera video, and movies. In comparison to Core Image (part of iOS 5.0), GPUImage allows you to write your own custom filters, supports deployment to iOS 4.0, and has a simpler interface. However, it currently lacks some of the more advanced features of Core Image, such as facial detection.

[GPUImage3](https://github.com/BradLarson/GPUImage3) is the third generation of the [GPUImage framework](https://github.com/BradLarson/GPUImage), an open source project for performing GPU-accelerated image and video processing on Mac and iOS. The original GPUImage framework was written in Objective-C and targeted Mac and iOS, the second iteration rewritten in Swift using OpenGL to target Mac, iOS, and Linux, and now this third generation is redesigned to use Metal in place of OpenGL.

[EGL](https://www.khronos.org/egl/) is an interface between Khronos rendering APIs such as OpenGL or OpenVG and the underlying native platform window system.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/) is the Video Decode and Presentation API for UNIX. It provides an interface to video decode acceleration and presentation hardware present in modern GPUs.

[VA API](https://freedesktop.org/wiki/Software/vaapi/) is an open-source library and API specification, which provides access to graphics hardware acceleration capabilities for video processing.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation) is an extension of the X video extension (Xv) for the X Window System. The XvMC API allows video programs to offload portions of the video decoding process to the GPU hardware.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[Universal Scene Description](https://github.com/PixarAnimationStudios/USD) is an efficient, scalable system for authoring, reading, and streaming time-sampled scene description for interchange between graphics applications.

[OpenTimelineIO](https://github.com/PixarAnimationStudios/OpenTimelineIO) is an interchange format and API for editorial cut information. OTIO is not a container format for media, rather it contains information about the order and length of cuts and references to external media. OTIO includes both a file format and an API for manipulating that format. It also includes a plugin architecture for writing adapters to convert from/to existing editorial timeline formats. It also implements a dependency- less library for dealing strictly with time, opentime.

[OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) is a set of open source libraries that implement high performance subdivision surface (subdiv) evaluation on massively parallel CPU and GPU architectures. This codepath is optimized for drawing deforming subdivs with static topology at interactive framerates. The resulting limit surface matches Pixar's Renderman to numerical precision.

[Affinity Designer](https://affinity.serif.com/en-gb/designer/) is a professional vector graphics editor used by many industry leading illustrators, designers, and other creatives looking to create high-quality concept art.

[Sketch](https://www.sketch.com) is a professional vector graphics app with a beautiful UI and powerful toolset.

[Krita](https://krita.org/) is an open source professional painting program for digital painting and 2D animation.

[Vectr](https://vectr.com/) is a free graphics software used to create vector graphics easily and intuitively.

[Glimpse](https://glimpse-editor.github.io/) is a cross-platform raster graphics editor based on the GNU Image Manipulation Program available for Linux, macOS, and Windows. A great tool for making YouTube video thumbnails.

[GNU Image Manipulation Program(GIMP)](https://www.gimp.org/) is a cross-platform raster graphics editor based on the GNU Image Manipulation Program(GIMP) available for Linux, macOS, and Windows. A great free alternative for Photoshop.

[PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) is a simple Patch for [GIMP 2.10+](https://www.gimp.org/) to help all Adobe Photoshop Users feel at home.

[Photopea](https://www.photopea.com/) is an advanced online photo editor supporting Adobe Photoshop(PSD), GIMP(XCF), Sketch App(Sketch), Adobe XD(XD) and CorelDRAW(CDR) formats.

[Inkscape](https://inkscape.org/) is an open-source vector graphics editor; it can be used to create or edit vector graphics such as illustrations, diagrams, line arts, charts, logos and complex paintings.

[Gthree](https://github.com/alexlarsson/gthree) is a GObject/Gtk+ port of three.js.

[FreeCAD](https://www.freecadweb.org/) is a free and open-source general-purpose parametric 3D CAD modeler and a building information modeling software with finite-element-method support.

[Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura) is the world’s most popular 3D printing software. Prepare prints with a few clicks, integrate with CAD software for an easier workflow, or dive into custom settings for in-depth control.

[Dust3D](https://dust3d.org/) is a cross-platform open-source modeling software. It helps you create a 3D watertight model in seconds. Use it to speed up your character modeling in game making, 3D printing, and so on.

[Goxel](https://github.com/guillaumechereau/goxel) is a free and Open Source 3D Voxel Editor.

[Sketchfab](https://sketchfab.com/tags/open-source) gives you open-source 3D models ready to view, buy, and download for free.

# Swift Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719675-03949c00-fb39-11ea-8f81-bf4cd544c17f.png">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110880054-dd9fb700-8292-11eb-9478-a5d62dc76f9d.png">
<br />
Developing with SwiftUI in Xcode 12
</p>

## Swift Learning Resources

[Swift](https://developer.apple.com/swift/) is Apple's main programming language for iOS, macOS, watchOS, and tvOS app development. Though, many parts of Swift will be familiar to developers from their experience of developing in C and Objective-C.

[Swift Evolution](https://github.com/apple/swift-evolution) maintains proposals for changes and user-visible enhancements to the Swift Programming Language.

[Xcode + Swift](https://developer.apple.com/swift/resources/) makes developing applications for MacOS and iOS fast and fun.

[Swift 5.3 Basics](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)

[Start Developing iOS Apps with Swift](https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/)

[Apple Developer Documentation](https://developer.apple.com/documentation)

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation)

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore)

[Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)

[Virtualization Framework](https://developer.apple.com/documentation/virtualization)

[Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics)

[Getting Started with LLDB](https://developer.apple.com/library/archive/documentation/IDEs/Conceptual/gdb_to_lldb_transition_guide/document/lldb-basics.html)

[Mac Catalyst - iOS - Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/ios/overview/mac-catalyst/)

[Amazon EC2 Mac Instances](https://aws.amazon.com/ec2/instance-types/mac/)

[Swift GitHub](https://github.com/apple/swift)

[Apple Developer Forums](https://developer.apple.com/forums/)

[Swift Forums](https://forums.swift.org/)

[Google's Swift Style Guide](https://google.github.io/swift/)

[Swift Courses Online from Coursera](https://www.coursera.org/courses?query=swift)

[Swift Courses Online from Udemy](https://www.udemy.com/topic/swift/)

[Learning Swift course from Codecademy](https://www.codecademy.com/learn/learn-swift)

## Swift Tools, Libraries, and Frameworks

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Mac Catalyst](https://developer.apple.com/mac-catalyst/) is a set of Apple APIs that developers can use to rapidly port their iOS apps to [Apple Silicon M1 Chip](https://www.apple.com/mac/m1/) and take full advantage of the new capabilities on the new Apple hardware.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[Cocoapods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[Vapor](https://github.com/vapor/vapor) is a web framework for Swift. It provides a beautifully expressive and easy to use foundation for your next website, API, or cloud project.

[Hero](https://github.com/HeroTransitions/Hero) is a library for building iOS view controller transitions. It provides a declarative layer on top of the UIKit's cumbersome transition APIs—making custom transitions an easy task for developers.

[Kingfisher](https://github.com/onevcat/Kingfisher) is a powerful, pure-Swift library for downloading and caching images from the web. It provides you a chance to use a pure-Swift way to work with remote images in your next app.

[Realm](https://github.com/realm/realm-cocoa) is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the iOS, macOS, tvOS & watchOS versions of Realm Swift & Realm Objective-C.

[Perfect](https://github.com/PerfectlySoft/Perfect) is a complete and powerful toolbox, framework, and application server for Linux, iOS, and macOS (OS X). It provides everything a Swift engineer needs for developing lightweight, maintainable, and scalable apps and other REST services entirely in the Swift programming language for both client-facing and server-side applications.

[Alamofire](https://github.com/Alamofire/Alamofire) is an HTTP networking library written in Swift.

[Eureka](https://github.com/xmartlabs/Eureka) is an elegant iOS form builder in Swift

[Carthage](https://github.com/Carthage/Carthage) is intended to be the simplest way to add frameworks to your Cocoa application. Carthage builds your dependencies and provides you with binary frameworks, but you retain full control over your project structure and setup. Carthage does not automatically modify your project files or your build settings.

[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) is reactive extensions to Cocoa frameworks, built on top of ReactiveSwift.

# Objective-C Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121821278-e6ff3d80-cc4c-11eb-9a57-c7aa13b88b30.png">
</p>


## Objective-C Learning Resources

[Objective-C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html) was the primary programming language used for writing software for macOS and iOS until [Swift](https://developer.apple.com/swift/) was introduced in 2014. It is a superset of the C programming language and provides object-oriented capabilities and a dynamic runtime.

[Apple Developer Forums](https://developer.apple.com/forums/)

[Google's Objective-C Style Guide](https://google.github.io/styleguide/objcguide.html)

[Objective C Courses on Coursera](https://www.coursera.org/courses?query=objective%20c)

[Objective-C online course on Udemy](https://www.udemy.com/topic/objective-c/)

[Objective-C for Swift Developers course by David Nutter](https://www.pluralsight.com/courses/objective-c-swift-developers)

[Objective-C Essential Training on LinkedIn Learning](https://www.linkedin.com/learning/objective-c-essential-training/)

[Objective-C for Swift Developers on Udacity](https://www.udacity.com/course/objective-c-for-swift-developers--ud1009)

## Objective-C Tools, Libraries, and Frameworks

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that’s part of the Xcode tool set. It’s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[Cocoapods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C in your Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[Realm](https://github.com/realm/realm-cocoa) is a mobile database(replaces Core Data & SQLite) that runs directly inside phones, tablets or wearables.

[Infer](https://github.com/facebook/infer) is a static analysis tool for Java, C++, Objective-C, and C.

[Mantle](https://github.com/Mantle/Mantle) is a model framework that makes it easy to write a simple model layer for your Cocoa or Cocoa Touch application.

[Quick](https://github.com/Quick/Quick) is a behavior-driven development framework for Swift and Objective-C.

[Aspects](https://github.com/steipete/Aspects) is a simple library for aspect oriented programming in Objective-C and Swift.

[Hammerspoon](https://github.com/Hammerspoon/hammerspoon) is a tool for powerful automation for macOS that acts as a bridge between the operating system and a Lua scripting engine.

[Nimbus](https://github.com/jverkoey/nimbus) is an iOS framework whose feature set grows only as fast as its documentation.

# C/C++ Development
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297894-961e0d80-a111-11eb-81c3-e2bd2ac9a7cd.png">
  <br />
</p>

## C/C++ Learning Resources

[C++](https://www.cplusplus.com/doc/tutorial/) is a cross-platform language that can be used to build high-performance applications developed by Bjarne Stroustrup, as an extension to the C language.

[C](https://www.iso.org/standard/74528.html) is a general-purpose, high-level language that was originally developed by Dennis M. Ritchie to develop the UNIX operating system at Bell Labs. It supports structured programming, lexical variable scope, and recursion, with a static type system. C also provides constructs that map efficiently to typical machine instructions, which makes it one was of the most widely used programming languages today.

[Embedded C](https://en.wikipedia.org/wiki/Embedded_C) is a set of language extensions for the C programming language by the [C Standards Committee](https://isocpp.org/std/the-committee) to address issues that exist between C extensions for different [embedded systems](https://en.wikipedia.org/wiki/Embedded_system). The extensions hep enhance microprocessor features such as fixed-point arithmetic, multiple distinct memory banks, and basic I/O operations. This makes Embedded C the most popular embedded software language in the world.

[C & C++ Developer Tools from JetBrains](https://www.jetbrains.com/cpp/)

[Open source C++ libraries on cppreference.com](https://en.cppreference.com/w/cpp/links/libs)

[C++ Graphics libraries](https://cpp.libhunt.com/libs/graphics)

[C++ Libraries in MATLAB](https://www.mathworks.com/help/matlab/call-cpp-library-functions.html)

[C++ Tools and Libraries Articles](https://www.cplusplus.com/articles/tools/)

[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

[Introduction C++ Education course on Google Developers](https://developers.google.com/edu/c++/)

[C++ style guide for Fuchsia](https://fuchsia.dev/fuchsia-src/development/languages/c-cpp/cpp-style)

[C and C++ Coding Style Guide by OpenTitan](https://docs.opentitan.org/doc/rm/c_cpp_coding_style/)

[Chromium C++ Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/c++/c++.md)

[C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md)

[C++ Style Guide for ROS](http://wiki.ros.org/CppStyleGuide)

[Learn C++](https://www.learncpp.com/)

[Learn C : An Interactive C Tutorial](https://www.learn-c.org/)

[C++ Institute](https://cppinstitute.org/free-c-and-c-courses)

[C++ Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/c-plus-plus)

[C++ Tutorials on W3Schools](https://www.w3schools.com/cpp/default.asp)

[Learn C Programming Online Courses on edX](https://www.edx.org/learn/c-programming)

[Learn C++ with Online Courses on edX](https://www.edx.org/learn/c-plus-plus)

[Learn C++ on Codecademy](https://www.codecademy.com/learn/learn-c-plus-plus)

[Coding for Everyone: C and C++ course on Coursera](https://www.coursera.org/specializations/coding-for-everyone)

[C++ For C Programmers on Coursera](https://www.coursera.org/learn/c-plus-plus-a)

[Top C Courses on Coursera](https://www.coursera.org/courses?query=c%20programming)

[C++ Online Courses on Udemy](https://www.udemy.com/topic/c-plus-plus/)

[Top C Courses on Udemy](https://www.udemy.com/topic/c-programming/)

[Basics of Embedded C Programming for Beginners on Udemy](https://www.udemy.com/course/embedded-c-programming-for-embedded-systems/)

[C++ For Programmers Course on Udacity](https://www.udacity.com/course/c-for-programmers--ud210)

[C++ Fundamentals Course on Pluralsight](https://www.pluralsight.com/courses/learn-program-cplusplus)

[Introduction to C++ on MIT Free Online Course Materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-096-introduction-to-c-january-iap-2011/)

[Introduction to C++ for Programmers | Harvard ](https://online-learning.harvard.edu/course/introduction-c-programmers)

[Online C Courses | Harvard University](https://online-learning.harvard.edu/subject/c)


## C/C++ Tools and Frameworks

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Vcpkg](https://github.com/microsoft/vcpkg) is a C++ Library Manager for Windows, Linux, and MacOS.

[ReSharper C++](https://www.jetbrains.com/resharper-cpp/features/) is a Visual Studio Extension for C++ developers developed by JetBrains.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages. All code inspections are run on the fly.

[CLion](https://www.jetbrains.com/clion/features/) is a cross-platform IDE for C and C++ developers developed by JetBrains.

[Code::Blocks](https://www.codeblocks.org/) is a free C/C++ and Fortran IDE built to meet the most demanding needs of its users. It is designed to be very extensible and fully configurable. Built around a plugin framework, Code::Blocks can be extended with plugins.

[CppSharp](https://github.com/mono/CppSharp) is a tool and set of libraries which facilitates the usage of native C/C++ code with the .NET ecosystem. It consumes C/C++ header and library files and generates the necessary glue code to surface the native API as a managed API. Such an API can be used to consume an existing native library in your managed code or add managed scripting support to a native codebase.

[Conan](https://conan.io/) is an Open Source Package Manager for C++ development and dependency management into the 21st century and on par with the other development ecosystems.

[High Performance Computing (HPC) SDK](https://developer.nvidia.com/hpc) is a comprehensive toolbox for GPU accelerating HPC modeling and simulation applications. It includes the C, C++, and Fortran compilers, libraries, and analysis tools necessary for developing HPC applications on the NVIDIA platform.

[Thrust](https://github.com/NVIDIA/thrust) is a C++ parallel programming library which resembles the C++ Standard Library. Thrust's high-level interface greatly enhances programmer productivity while enabling performance portability between GPUs and multicore CPUs. Interoperability with established technologies such as CUDA, TBB, and OpenMP integrates with existing software.

[Boost](https://www.boost.org/) is an educational opportunity focused on cutting-edge C++. Boost has been a participant in the annual Google Summer of Code since 2007, in which students develop their skills by working on Boost Library development.

[Automake](https://www.gnu.org/software/automake/) is a tool for automatically generating Makefile.in files compliant with the GNU Coding Standards. Automake requires the use of GNU Autoconf.

[Cmake](https://cmake.org/) is an open-source, cross-platform family of tools designed to build, test and package software. CMake is used to control the software compilation process using simple platform and compiler independent configuration files, and generate native makefiles and workspaces that can be used in the compiler environment of your choice.

[GDB](http://www.gnu.org/software/gdb/) is a debugger, that allows you to see what is going on `inside' another program while it executes or what another program was doing at the moment it crashed.

[GCC](https://gcc.gnu.org/) is a compiler Collection that includes front ends for C, C++, Objective-C, Fortran, Ada, Go, and D, as well as libraries for these languages.

[GSL](https://www.gnu.org/software/gsl/) is a numerical library for C and C++ programmers. It is free software under the GNU General Public License. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. There are over 1000 functions in total with an extensive test suite.

[OpenGL Extension Wrangler Library (GLEW)](https://www.opengl.org/sdk/libs/GLEW/) is a cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform.

[Libtool](https://www.gnu.org/software/libtool/) is a generic library support script that hides the complexity of using shared libraries behind a consistent, portable interface. To use Libtool, add the new generic library building commands to your Makefile, Makefile.in, or Makefile.am.

[Maven](https://maven.apache.org/) is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

[TAU (Tuning And Analysis Utilities)](http://www.cs.uoregon.edu/research/tau/home.php) is capable of gathering performance information through instrumentation of functions, methods, basic blocks, and statements as well as event-based sampling. All C++ language features are supported including templates and namespaces.

[Clang](https://clang.llvm.org/) is a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting X86-32, X86-64, and ARM (other targets may have caveats, but are usually easy to fix). Clang is used in production to build performance-critical software like Google Chrome or Firefox.

[OpenCV](https://opencv.org/) is a highly optimized library with focus on real-time applications. Cross-Platform C++, Python and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Libcu++](https://nvidia.github.io/libcudacxx) is the NVIDIA C++ Standard Library for your entire system. It provides a heterogeneous implementation of the C++ Standard Library that can be used in and between CPU and GPU code.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[Oat++](https://oatpp.io/) is a light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.

[JavaCPP](https://github.com/bytedeco/javacpp) is a program that provides efficient access to native C++ inside Java, not unlike the way some C/C++ compilers interact with assembly language.

[Cython](https://cython.org/) is a language that makes writing C extensions for Python as easy as Python itself. Cython is based on Pyrex, but supports more cutting edge functionality and optimizations such as calling C functions and declaring C types on variables and class attributes.

[Spdlog](https://github.com/gabime/spdlog) is a very fast, header-only/compiled, C++ logging library.

[Infer](https://fbinfer.com/) is a static analysis tool for Java, C++, Objective-C, and C. Infer is written in [OCaml](https://ocaml.org/).

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Apple-Silicon-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Apple-Silicon-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
