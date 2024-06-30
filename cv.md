# Victor Bomberow

**Phone**:   [+375 29 694 91 52](tel:+375296949152)

**Email**:     [victor@gds.by](mailto:victor@gds.by)

**Skype**:     [live:.cid.fe6ebb1cb4a7cdfc](skype:live:.cid.fe6ebb1cb4a7cdfc?call)

**Linkedin**:   [linkedin.com/in/victor-bomberow/](https://linkedin.com/in/victor-bomberow/)

**Github**:     [github.com/vitoOmbero/](https://github.com/vitoOmbero/)



## Objective

C++ SOFTWARE DEVELOPER

## Summary

C++ developer with expertise in enterprise software development from idea to MVP.  Skilled in server-side and client-side software development.

### Personal Information

I want to keep improving my professional skills in an amicable team. In my spare time I watch documentary films and series (spacecraft, science, nature, geology), I read non-fiction literature and study the field of game development and fullstack web development. My professional interests: c++, game engines, computer science, web solutions for B2B and B2C. Military obligation status: reserved.

**Total Experience:** 11 years

### Skills

**Programming languages:** C++, C#, Java, Python, JavaScript, HTML, SQL
Relational Database Management Systems: PostgreSQL, Microsoft SQL Server, MySQL

**OS:** Windows, Linux

**IDE:** Microsoft Visual Studio, Microsoft VS Code, QtCreator, CLion, IntelliJ Idea

**Source Control Systems:** Git

**C++ Technologies:** stl, boost, Qt, libxml2, libxslt, libpqxx, libsdl2, tinyxml, rapidjson

**Other Technologies:** WinAPI, ODBC, WCF, ADO.NET, WinForms, ClickOnce, OpenStreetMap, EPPlus, Apache httpd, RabbitMQ, ZeroMQ, SQLLite, OpenGL, XML, XLST, QML, GTest, Doctest, MsTest, NUnit

**Other skills:** TDD/BDD, Bamboo, SonarQube, GitLab, Docker, CMake, Bash, PowerShell

### Education

+ *Educational Center of HTP*
  + **2018** - C++ development
  + **2018** - C++ game development

+ *Belarusian State University of Informatics and Radioelectronics, Minsk*
  + **2008 - 2013** – Radio-electronic information protection, qualification of engineer in radio electronics (Bachelor)
SP 390104
  + **2011 - 2012** – Advanced English technical translation, annotation and abstracting of literature in telecommunications and IT
№ 716-12

### Languages

+ Russian – native
+ English – B2

## Work experience

### Ispirer Systems LTD

C++ developer

Jan, 2020 - present time

### The Ministry of Internal Affairs of the Republic of Belarus

Security Operations Center C# / C++ lead developer - Police Officer (Projects not disclosure)

Jan, 2018 - Aug, 2020

Security Operations Center Security Analyst - Police Officer (Projects not disclosure)

Aug, 2013 – Dec, 2017

### Projects

#### Ispirer Systems LTD Toolchain

**Project description:** Conversion toolset for application source code and database migration.

**Responsibilities:** Development of new features and fixing issues, related to conversion tools, GUI clients, setups, license system and conversion engine.

**Technologies and Tools:** C++, boost, Qt, libxml2, libxslt, SQL, ODBC, libpqxx, WiX Toolset, Bamboo.

**Source Control System:** TFVC, Git.

**OS:** Windows

**Position:** C++ Developer.

**Team Size:** ~4-5 developers.

---

#### MIA RB Projects Description

**Projects:**  Analysis system client, based on Openstreetmap and set theory; Analysis system server, based on RabbitMQ and custom authorization system; Analysis system GUI and command line tools; Analysis system data import tools; CI/CD for projects based on Gitlab, ClickOnce.
Technologies and Tools: C#, Wcf, Ado.net, ClickOnce, EF, Winforms, EPPLus, C++, Microsoft SQL Server, Openstreetmap, PostgreSQL, Apache httpd, CentOS, C++.

**Source Control System:** Git.

**OS:** Windows Server, CentOS.

**Position:** Lead Developer.

**Team Size:** ~2 developers.

**Responsibilities:** Analysis system development and administration, customer support, fix issues and new features development.

**Achievements:** Feature realization cycle was shortened to days after I finished global legacy code refactoring of prototypes and CI/CD integration with Gitlab; I wrote documentation with Doxygen and covered core logic for all projects with tests; I implemented administration tool for system and shortened administration operations to an hour per day; I built an automated process for updating Openstreetmap server for usage in private isolated intranet.

---

### Samples

Open source repos at [github.com/vitoOmbero/](https://github.com/vitoOmbero/) are outdated.
Updates are coming...

```c++
#ifdef PEP_DEBUG
  Terminal::ReportMsg("OpenGL Version: ");
  Terminal::ReportMsg(std::to_string(gl_major_ver));
  Terminal::ReportMsg(std::to_string(gl_minor_ver));
#endif

#ifdef PEP_DEBUG
  Terminal::ReportMsg("Engine play() called...");
#endif
  GlRendererService::SetActiveWindow(window);

  InputProcessingService::Init(gGameConfiguration.InputModes);

  GameLevelLogicProcessor::GetSingleton().ProcessLevel(
      gGameConfiguration.DescriptionInfo->entry_point);

  while (GameLevelLogicProcessor::isNotLastLevel()) {
    GameLevelLogicProcessor::GetSingleton().ProcessNextLevel();
  }

  GameLevelLogicProcessor::GetSingleton().ProcessLevel(
      gGameConfiguration.DescriptionInfo->exit_point);

  InputProcessingService::Destroy();

  SDL_GL_DeleteContext(gl_context);
  SDL_DestroyWindow(window);
  SDL_Quit();
```
