# libopus-Android.mk
A build Android NDK script for libopus with NEON and SSE optimization.

As far as I know that building libopus without NEON and SSE optimization may lead to some compatibility issues (e.g. Chrome may unable to decode).

This script was modified from https://android.googlesource.com/platform/external/libopus/+/master .
It was used to build opus codec for IP Camera app and USB Camera app.
