This is sample File Picker Application for Android Studio.

This app is already configured to work with filepicker-library.

## Getting Started

1. Download filepicker-library and sample-studio to the same folder.

  You can check that the needed dependencies are added in:

  settings.gradle

  ```java
  include ':filepicker-library'
  project(':filepicker-library').projectDir = new File(rootProject.projectDir, '../filepicker-library')
  ```

  and build.gradle (in dependencies section)

  ```java
  compile project(':filepicker-library')
  ```

2. Set your FILEPICKER_API_KEY and PARENT_APP in MainActivity.

3. Enjoy using FilePicker!