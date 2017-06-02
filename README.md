# opencv to javascript compiler

### How to Build
1. Get the source code

  ```
  git clone https://github.com/biggzlar/opencv_js_compiler.git
  cd opencvjs
  git clone https://github.com/opencv/opencv 
  ```
2. Install emscripten. You can obtain emscripten by using [Emscripten SDK](https://kripken.github.io/emscripten-site/docs/getting_started/downloads.html).

  ```
  ./emsdk update
  ./emsdk install latest
  ./emsdk activate latest
  source ./emsdk_env.sh
  ```
3. Compile OpenCV and generate bindings by executing n_make.py script.

  ```
    python n_make.py input.cpp
  ```
