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

![lab03-1](https://user-images.githubusercontent.com/90759633/161233510-352a07b0-f2f4-4aa6-82ba-4b334b40291e.png)

![lab03-2](https://user-images.githubusercontent.com/90759633/161233537-90df8331-0990-43cf-a5a2-d2ee74e4f702.png)

![lab03-3](https://user-images.githubusercontent.com/90759633/161233548-961d48d7-21d4-4d4b-9280-877e98006dfc.png)

![lab03-4](https://user-images.githubusercontent.com/90759633/161233561-75055132-f24d-43ff-99f2-e0fb93e0c19a.png)
