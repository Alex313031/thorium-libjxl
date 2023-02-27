# Thorium libJXL

<img src="https://raw.githubusercontent.com/Alex313031/Thorium/main/logos/NEW/thorium.svg" width="64">&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/Alex313031/thorium-libjxl/main/plus-sign.svg" width="64">&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/Alex313031/thorium-libjxl/main/JPEG_XL_logo.svg" width="54">

 - [libjxl](https://github.com/libjxl/libjxl) for Thorium Browser - restores [JPEG-XL](https://jpegxl.info/) functionality to Thorium versions [post M109](https://chromium-review.googlesource.com/c/chromium/src/+/4081749).

 - This repo is added as a submodule to [the main Thorium repo](https://github.com/Alex313031/Thorium), and `setup.sh` copies this repos __//src/__ dir over the
 Chromium tree, and then Thorium's __//src/__ dir.

 &#62; @mo271's patch which this is based on: https://chromium-review.googlesource.com/c/chromium/src/+/4255409 \
 &#62; @gz83's patch which restores jxl devtools functionality: https://chromium-review.googlesource.com/c/devtools/devtools-frontend/+/4257582 \
 &#62; Also related, and needed for building is [libhighway](https://github.com/google/highway)

 &ndash; Both libjxl and libhighway versions were bumped to ~ Jan. 2023 revisions. \
 &ndash; Note that PGO might be slightly less effective unless you generate your own *.profdata* file from a debug build of Thorium/Chromium.
