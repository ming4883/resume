# Information

|  |  |
|---|---|
| Name | Ka Ming Chan |
| Gender | Male |
| DOB | 4th Aug 1983 |
| Languages | <ul><li>Chinese (Cantonese) : Native</li><li>Chinese (Putonghua) : Fluent</li><li>English : Fluent</li></ul> |

# Education

| Period | School | Qualification |
| --- | --- | --- |
| 2002-2006 | City Univeraity Of Hong Kong | BSc (Hon) in Computer Science |
| 2007-2010 | The Hong Kong Polytechnic University | MSc in Electronic and Information Engineering (Distinction) |

# Work Experience

* ### Game Cyber Technology Limited (5/2000 – 9/2003)
  * Developed a 3d effect editor with Borland C++ Builder
  * Conduct researches on vaiours 3D rendering effects using Direct3D 8

* ## CIMSOFT CORPORATION (Placement) (7/2004 - 7/2005)
  * Development on a Prisoner tracking system based on Visual Basic 6.0 and RFID technology.
  * Development on a Advertising kiosk system based on .NET Framework 1.1
  
* ## M-Inverse Holdings Limited (2006 - Present)
  * Development based on the OGRE 3D game engine which made the following games
    * [Skillz The DJ Game (initial PC version)](https://www.youtube.com/watch?v=DdtkrJLpqu0)
    * More can be found in [HERE](http://www.m-inverse.com/works.html)
  * Development of mini games in [Hello Kitty Online](https://en.wikipedia.org/wiki/Hello_Kitty_Online) using Adobe Flex & SmartFox Server
  * Development on in-house cross platform game engine which made the following games:
    * [Dungeons and Coin](https://play.google.com/store/apps/details?id=com.sigmagame.coinpusher&hl=en)
    * [Fish Galaxy](https://play.google.com/store/apps/details?id=com.sigmagame.fishgalaxy&hl=en)
    * [American Ball](https://play.google.com/store/apps/details?id=com.sigmagame.americanball&hl=en)
    * [Bingo Jungle](https://play.google.com/store/apps/details?id=com.sigmagame.bingojungle&hl=en)
    * [Bulu Monster](https://play.google.com/store/apps/details?id=com.sigmagame.imonster&hl=en)
  * Development on unannounced PSVR project using Unity 3D
  * Development on unannounced mobile multiplay strategy game using Unity 3D

# Skills

* Performance-wise C / C++ Games / Applications development
  * Familiar with data-oriented (cache line friendly) design & development
  * Familiar with memory management techniques
  * Familiar with common data structures and algorithms
  * Familiar with C++ 11 standard libraries
  * Familiar with C++ template techniques such as typelist, specialization, partial specialization ... etc
  * Experience in common C++ frameworks such as ASIO, QT
  * Familiar with test driven development and frameworks such unittest++, gtest ... etc
  * Familiar with cmake and various build systems

* Games Engine / Tool development
  * Experience in embedding scripting-languages (LUA, squirrel)
  * Experience in 3DS Max exporters and plugins development
  * Experience in FBX SDK
  * Experience in implementing a lightmapper
  * Experience in TCP/IP socket programming
  * Experience in libgit2 usages
  * Experience in implementing environment map filtering tool using spherical harmonics.
  * Experience in implementing FABRIK system.

* Graphics & Shaders Programming
  * Author of the following ShaderToy shaders
    * [Rain Drops](https://www.shadertoy.com/view/llfczH)
    * [Anpanman](https://www.shadertoy.com/view/MdV3R3)
    * [The Cross](https://www.shadertoy.com/view/XsfGR7)
  * Author of the following demos
    * [DirectX 9.0c Soft Shadows demo](https://www.youtube.com/watch?v=E-qdbqYblgY)
    * [DirectX 11 histogram based tone mapping demo](https://www.youtube.com/watch?v=w_Z4GOlokvA)
  * Familiar with Physically Based Rendering principle & work flow
  * Experience in implementing various GFX effects such as SSAO, Flimic Tone Mapping, Depth of Field... etc.

* Raspberry Pi & Microcontroller development
  * Familiar with cross compiling work flow
  * Experience in Linux development
  * Experience in Arduino & Esp8266 development
  * Experience in Docker usages

* Miscellaneous programming languages such as C#, Python, Javascript ... etc

# Recent Works

* mCloud
  * A in-house custom Git Client for game asset management
  * Based on libgit2 and CEF sharp
  * Simpified and easy to understand git operations for artist

* Unannounced VR sport game based on UE4 (4.15) and HTC Vive
  * Similar to [RipCoil](https://www.youtube.com/watch?v=gELTZzntr7Q)
  * Duties:
    * Implemented a custom FAnimNode which controls the character's upper body with IK
    * Modified UE4's SteamVR plugin to provide custom fade in / out in the HTC VIVE headset
    * Provide guidelines and supports to artists for using UE4.

* Unannounced PSVR project based on Unity 3D 5.4
  * An animal VR simulation game for PSVR
  * OVA style shadings
  * Duties
    * Implemented a set of shaders of OVA style shadings
    * Implemented contact shadows effect for Unity 3D
    * Implemented a custom screen space outline effect
    * Implemented an adaptive local filmic tonemapping operator
    * Provide supports and examples to artists for adopting Unity 3D's lighting system and HDR rendering

* Unannounced mobile multiplay strategy game using Unity 3D 5.6
  * Similar to [Mobile Strike](https://www.mobilestrikeapp.com/) with real time 3D battle reply.
  * Duties:
    * Implemented a 3 point lighting system and shaders for 3D character rendering
      * Support shader LOD
      * Use pre-computed GGX specular LUT to provide more convincing specular highlights than phong shading
    * Implemented a set shaders for 3D scene rendering
      * Support shader LOD
      * An Uber shader which support various features such as lighting on/off, decal, texture composition ... etc
      * Provide fake specular highlights with GGX distribution from lightmap data.
    * Implemented a set shaders for 3D effect rendering
      * Support shader LOD
      * Use flow map to control texture animations
    * Implemented a screen space rain drop effect for the main menu
      * Similar to [this](https://tympanus.net/codrops/2015/11/04/rain-water-effect-experiments/)
      * With much better performance

* Smart Remote Car project
  * Personal project for learning embedding system development
  * Involve 3 major modules: Motor control, FPV, and Client remote 
  * Key notes:
    * Use TCP/IP over wifi for inter module communications
    * Use Esp8266 for motor control and wifi AP
    * Use Raspiberry pi for FPV
      * Use V4L2 for video capture
      * Implemented a simple video streaming protocol over TCP/IP
    * Use Android Phone for client remote
      * Use QT for simpfiled Android development
      * Use OpenGL ES and IMGUI for user interfaces

# EOF
