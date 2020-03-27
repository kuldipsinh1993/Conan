1. Create new package:
  conan new hello/0.1 -t

  -"hello" is the package name and "0.1" is the version.

2. Create profile:
  conan profile new default --detect

  - default is the profile name and it will detect machines Configuration and
    create profile.

3. Creating and Testing package:
  conan create . demo/testing

  - If at last "Hello world Release!" come then your package created
    successfully.
  
