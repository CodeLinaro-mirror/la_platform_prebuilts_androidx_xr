# Jetpack XR Prebuilts

This directory has the resources shared by the Jetpack XR libraries that
are not built/created from source in the frameworks/support repository.

There are two types of resources, which are in their eponymous directory:
assets (for images, models, videos, etc...) and native (for the C++ code
used to interface with C APIs).

## Jetpack XR Assets

The assets directory contains a collection of assets used across the Jetpack
XR libraries for testing/sample purposes. Additional assets may not be added
in other repositories to avoid file duplication.

All files in this directory were created for this purpose and are released
under the terms of the Apache 2.0 license.


## Jetpack XR Native Code

These shared libraries are used by the xr:runtime-openxr and xr:scenecore
Jetpack modules to expose OpenXR functionality from a C API to Java and Kotlin
code.

They are equivalent to builds produced from the open-source Jetpack XR Native
code hosted at https://github.com/google-ar/jetpack-xr-natives/.

Imported from
https://rapid.corp.google.com/#/candidate/jetpack_xr/jetpack_xr_1.0.0-alpha02/jetpack_xr_1.0.0-alpha02_RC03
