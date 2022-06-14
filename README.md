[ ![License Badge](https://img.shields.io/badge/License-Apache%202.0-orange?style=for-the-badge&logo=apache) ](https://www.apache.org/licenses/LICENSE-2.0)

Intellij Ubuntu Light Theme
=============================

![](https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png)

**Intellij Ubuntu Light Theme** is an Idea theme plugin whose color scheme follows the famous
[Ubuntu Color Palette](https://design.ubuntu.com/brand/colour-palette/)

Screenshot
----------

> **Note that the color scheme should be [set to "IntelliJ Light"](#configure-editor-background-color) in order to have
> the same visual as appeared in pictures below

![](https://repository-images.githubusercontent.com/503174206/9de6b167-80d5-436a-8091-7eb05ac53b8e)

Install from Source
-------------------

Before the plugin can be used, it must be deployed: built, installed, and then enabled using Plugin Manager.

Get source code by

```bash
git@github.com:stealth-tech-startup/intellij-theme-ubuntu.git
```

Then open IntelliJ and deploy this plugin. Make the project by invoking **Build | Build Project** or **Build | Build
Module 'intellij-theme-ubuntu'**.

Prepare the plugin for deployment. In the main menu, select **Build | Prepare Plugin Module 'intellij-theme-ubuntu' For
Deployment**.

![](https://plugins.jetbrains.com/docs/intellij/images/prepare_plugin_for_deployment.png)

If the plugin module builds successfully, a JAR file will be created:

![](https://plugins.jetbrains.com/docs/intellij/images/jar_saved_notification.png)

Install the newly created JAR file from disk:

1. Open **File | Settings** on Windows or **IntelliJ IDEA | Preferences** on Mac and select **Plugins**.
2. On the **Plugins** page, click the 
   Settings (![](https://resources.jetbrains.com/help/img/idea/2022.1/app.general.gearPlain.svg)) button and then click
   **Install Plugin from Disk…**.
3. Select the 'intellij-theme-ubuntu' plugin archive file and click **OK**.
4. Click **OK** to apply the changes and restart the IDE if prompted.

> Please refer to [IntelliJ Doc](https://www.jetbrains.com/help/idea/managing-plugins.html) for more details on
> installing plugin from disk

Configure Editor Background Color
---------------------------------

1. Open **File | Settings** on Windows or **IntelliJ IDEA | Preferences** on Mac
2. Navigate to **Editor | Color Scheme | General**
3. Select **IntelliJ Light** scheme

You are done. Enjoy the spirit of
Ubuntu! ![](https://i0.hdslb.com/bfs/article/958822aa3126e450dfe5f4542c09a9b048cbd3f9.gif)

License
-------

The use and distribution terms for this software are covered by the Apache License, Version 2.0
( http://www.apache.org/licenses/LICENSE-2.0.html ).
