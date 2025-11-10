# Jetpack XR Prebuilts

This directory has the resources shared by the Jetpack XR libraries that
are not built/created from source in the frameworks/support repository.

There are three types of resources, which are in their eponymous directory:
assets (for images, models, videos, etc...), extensions (for platform stubs),
and native (for the C++ code used to interface with C APIs).

## Jetpack XR Assets

The assets directory contains a collection of assets used across the Jetpack
XR libraries for testing/sample purposes. Additional assets may not be added
in other repositories to avoid file duplication.

All files in this directory were created for this purpose and are released
under the terms of the Apache 2.0 license.


## Jetpack XR Extensions

These jar files provide stubs for the com.android.xr.extensions platform APIs.

- com.android.extensions.xr.jar - to be used as a compile-only dependency for
  XR libraries and apps that rely on extensions
- com.android.extensions.xr.host.test.jar - to be used as a compile-only
  dependency for XR host tests that rely on extensions
- com.android.extensions.xr.instrumented.test.jar - to be used as a compile-only
  dependency for XR instrumented tests that rely on extensions

PMAD check in: http://mhcr/421877<br>
Android build id: http://ab/13691615<br>

## Jetpack XR Native Code

These shared libraries are used by the xr:runtime-openxr and xr:scenecore
Jetpack modules to expose OpenXR functionality from a C API to Java and Kotlin
code.

They are equivalent to builds produced from the open-source Jetpack XR Native
code hosted at https://github.com/google-ar/jetpack-xr-natives/.

Imported from
https://rapid.corp.google.com/#/candidate/jetpack_xr/nightly_20251024/nightly_20251024_RC00
