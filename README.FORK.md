>[!Note]
>Base information please see [README](README.md) for details.
>This document mainly describes changes of this fork.

- The submodule source has been changed to [javacard_sdks](git@github.com:ibaibing/javacard_sdks.git).

- This fork can use ant-javacard also, download ant-javacard to directory **your_project/libs/ant-javacard.jar**.

  ```bash
  cd your_project
  ant convert_ant_jc
  ```

- This fork can use ant to build cap-files as many JCSDKs as possible will be supported, please see [BUIDING_WITH_ANT](https://github.com/ibaibing/building-javacard-applet/blob/main/BUIDING_WITH_ANT.md) for details.

  ```bash
  cd your_project
  ant
  ```

- more.

