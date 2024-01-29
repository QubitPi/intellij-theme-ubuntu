Intellij Ubuntu Light Theme
=============================

[![Apache License Badge]](https://www.apache.org/licenses/LICENSE-2.0)

**Intellij Ubuntu Light Theme** is an Idea theme plugin whose color scheme follows the famous
[Ubuntu Color Palette](https://design.ubuntu.com/brand/colour-palette/)

![](https://repository-images.githubusercontent.com/503174206/9de6b167-80d5-436a-8091-7eb05ac53b8e)

Installation Guide
------------------

### Step 1: Building Plugin from Source

Before the plugin can be used, it must be deployed: built, installed, and then enabled using Plugin Manager.

Get source code by

```bash
git clone https://github.com/QubitPi/intellij-theme-ubuntu.git
```

Then open IntelliJ and deploy this plugin. Make the project by invoking **Build | Build Project** or **Build | Build
Module 'intellij-theme-ubuntu'**.

Prepare the plugin for deployment. In the main menu, select **Build | Prepare Plugin Module 'intellij-theme-ubuntu' For
Deployment**.

If the plugin module builds successfully, a JAR file will be created at the root of `intellij-theme-ubuntu` directory

### Step 2: Installing Plugin from Disk

Install the newly created JAR file from disk:

1. Open **File | Settings** on Windows or **IntelliJ IDEA | Preferences** on Mac and select **Plugins**.
2. On the **Plugins** page, click the 
   Settings (![](https://resources.jetbrains.com/help/img/idea/2022.1/app.general.gearPlain.svg)) button and then click
   **Install Plugin from Disk…**.
3. Select the 'intellij-theme-ubuntu' plugin archive file and click **OK**.
4. Click **OK** to apply the changes and restart the IDE if prompted.

> Please refer to [IntelliJ Doc](https://www.jetbrains.com/help/idea/managing-plugins.html) for more details on
> installing plugin from disk

### Step 3: Configuring IntelliJ to Use the Plugin

1. Open **File | Settings** on Windows or **IntelliJ IDEA | Settings...** on Mac
2. Navigate to **Appearance & Behavior | Appearance**
3. Select **Ubuntu Theme (Light)** for "Theme" config
4. Navigate to **Editor | Color Scheme | General**
5. Select **IntelliJ Light** scheme

You are done. Enjoy the spirit of
Ubuntu! ![](https://i0.hdslb.com/bfs/article/958822aa3126e450dfe5f4542c09a9b048cbd3f9.gif)

License
-------

The use and distribution terms for [intellij-theme-ubuntu] are covered by the [Apache License, Version 2.0].

<div align="center">
    <a href="https://opensource.org/licenses">
        <img align="center" width="50%" alt="License Illustration" src="https://github.com/QubitPi/QubitPi/blob/master/img/apache-2.png?raw=true">
    </a>
</div>

[Apache License Badge]: https://img.shields.io/badge/Apache%202.0-F25910.svg?style=for-the-badge&logo=Apache&logoColor=white
[Apache License, Version 2.0]: http://www.apache.org/licenses/LICENSE-2.0.html

[intellij-theme-ubuntu]: https://github.com/QubitPi/intellij-theme-ubuntu
