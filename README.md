# Prebuilt WASM languages

These were built using emscripten 3.1.8.

As of the current date, tree-sitter precompiled wasm/js is incompatible with the latest emscripten generated languages.

If you encounter this error, you can fix this problem by rebuilding tree-sitter WASM against emscripten 3.1.8 (there's a script to do it `tree-sitter/script/build-wasm`)
