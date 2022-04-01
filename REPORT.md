git clone https://github.com/tp-labs/lab03.git projects/lab03
cd projects/lab03
git remote remove origin
git remote add origin https://github.com/konsumerof/lab03.git
git push --set-upstream origin master

cd formatter_lib
touch CMakeLists.txt
nano CMakeLists.txt

git push

cmake -H. -B_build
cmake --build _build
cmake --build _build --target hello_world
