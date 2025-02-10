
## CSPro Users

We are [CSPro Users](https://www.csprousers.org), a community that uses and promotes the [Census and Survey Processing System](https://www.census.gov/data/software/cspro.html) (CSPro) and [CSEntry Android](https://play.google.com/store/apps/details?id=gov.census.cspro.csentry). First released on May 5, 2000, CSPro was initially only a Windows software package that replaced two DOS-based software packages, IMPS and ISSA. In the decades since the first release, CSPro has grown into a larger application suite with an Android application as well as CSWeb, a web application that stores collected data.

Historically, CSPro was developed by three organizations, the U.S. Census Bureau's [International Programs Center](https://www.census.gov/programs-surveys/international-programs.html), [ICF](https://www.icf.com/clients/health/demographic-health-surveys-technical-assistance), and [Serpro S.A](https://www.serpro.com). Thanks to generous funding from the [U.S. Agency for International Development](https://www.usaid.gov) (USAID), the product always been in the public domain and can be used and distributed at no cost. With CSPro code released to the public, users from around the world are invited to contribute to this open source project.

----

Released versions of the software are available at the following sites:

- [Census Bureau](https://www.census.gov/data/software/cspro.html) (CSPro and CSWeb)
- [CSPro Users](https://www.csprousers.org/downloads) (CSPro and CSWeb)
- [Google Play](https://play.google.com/store/apps/details?id=gov.census.cspro.csentry) (CSEntry)

The [CSPro Users Forum](https://www.csprousers.org/forum) is a place where users can discuss all things CSPro.


## Repositories

There are five primary repositories:

- [cspro](https://github.com/csprousers/cspro): The code for CSPro and CSEntry.
    - The CSPro suite of programs that runs on Windows is coded in C++ using the [Microsoft Foundation Class](https://learn.microsoft.com/en-us/cpp/mfc/framework-mfc) (MFC) framework. This code is built using [Microsoft Visual Studio](https://visualstudio.microsoft.com).
    - CSEntry, the Android application, is coded in Java and Kotlin and built using [Android Studio](https://developer.android.com/studio).
    - The shared runtime is coded in C++, with the [NDK](https://developer.android.com/ndk) toolset building this for Android.
- [csweb](https://github.com/csprousers/csweb): The web application that allows users to securely transfer cases or files between client devices and a web server.
    - CSWeb is coded in PHP.
- [helps](https://github.com/csprousers/helps): The help documentation distributed with CSPro, which can be [viewed online](https://www.csprousers.org/help/CSPro).
    - The helps are authored using [CSDocument](https://www.csprousers.org/help/CSDocument/introduction.html), a tool distributed with CSPro 8.0+.
- [examples](https://github.com/csprousers/examples): The examples distributed with CSPro.
    - The examples are CSPro applications.
- [workshop-mobile](https://github.com/csprousers/workshop-mobile): Teaching materials for a workshop on data collection using mobile devices.
    - As with the help documentation, the workshop materials are authored using CSDocument.

Ways to collaborate on these products is described in more detail on each repository's page.
