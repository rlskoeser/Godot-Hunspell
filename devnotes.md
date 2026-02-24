# compile

Checkout a copy of godot-cpp and hunspell.  Checkout the tag for the version of Godot you are compiling for.

Compile with `scons`; specify platform and template.

scons platform=android target=template_release
scons platform=android target=template_debug
scons platform=web target=template_release


To compile for android, you must install android sdk and set ANDROID_HOME in environment.

To compile for wasm/web, you must install emsdk 4.0.x. Use emsdk to install and activate, setting the necessary environment variables
