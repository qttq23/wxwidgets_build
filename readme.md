download & build instruction...


1. download zip file from : ..

2. unzip to ..

3. create build folder: eg: wxWidgets-3.1.6_build and run:
cd wxWidgets-3.1.6_build

4. go to build folder and run:
cmake -G "Visual Studio 17 2022" -A x64 "..\wxWidgets-3.1.6" -DwxBUILD_SHARED=ON -DwxUSE_GUI=ON -DCMAKE_INSTALL_PREFIX="%cd%/../wxWidgets-3.1.6_win32_x64_release"

5. build:
cmake --build . --config Release

6. install:
cmake --build . --config Release --target install

