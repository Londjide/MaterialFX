[![HitCount](https://github.com/Londjide/MaterialFX/releases)](https://github.com/Londjide/MaterialFX/releases)
![GitHub Workflow Status](https://github.com/Londjide/MaterialFX/releases%20CI%20with%20Gradle?label=github%20build&style=flat-square)
![Sonatype Nexus (Releases)](https://github.com/Londjide/MaterialFX/releases%3A%2F%https://github.com/Londjide/MaterialFX/releases)
[![javadoc](https://github.com/Londjide/MaterialFX/releases)](https://github.com/Londjide/MaterialFX/releases)
![GitHub issues](https://github.com/Londjide/MaterialFX/releases)
![GitHub pull requests](https://github.com/Londjide/MaterialFX/releases)
![GitHub](https://github.com/Londjide/MaterialFX/releases)
---

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Londjide/MaterialFX/releases">
    <img https://github.com/Londjide/MaterialFX/releases" alt="Logo">
  </a>
</p>


<h3 align="center">MaterialFX</h3>

<p align="center">
    MaterialFX is an open source Java library which provides material design components for JavaFX
    <br />
    <a href="https://github.com/Londjide/MaterialFX/releases"><strong>Explore the wiki »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Londjide/MaterialFX/releases">Download Latest Demo</a>
    ·
    <a href="https://github.com/Londjide/MaterialFX/releases">Report Bug</a>
    ·
    <a href="https://github.com/Londjide/MaterialFX/releases">Request Feature</a>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

* [About the Project and History of JavaFX](#about-the-project-and-history-of-javafx)
* [About the Logo](#about-the-logo)
* [Some GIFs](#preview-gifs)
* [Getting Started](#getting-started)
  * [Build](#build)
  * [Usage](#usage)
    * [Gradle](#gradle)
    * [Maven](#maven)
* [Documentation](#documentation)
* [Changelog](#changelog)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Donation](#donation)
* [Supporters](#supporters)

<!-- ABOUT THE PROJECT -->

## About The Project and History of JavaFX

JavaFX is a software platform intended to replace Swing in creating and delivering rich client applications that operate
consistently across diverse platforms. With the release of JDK 11 in 2018, Oracle has made JavaFX part of the OpenJDK
under the OpenJFX project in order to increase the pace of its development.

Key features:

- FXML and SceneBuilder, A designer can code in FXML or use JavaFX Scene Builder to interactively design the graphical
  user interface (GUI). Scene Builder generates FXML markup that can be ported to an IDE where a developer can add the
  business logic.
- Built-in UI controls and CSS, JavaFX provides all the major UI controls required to develop a full-featured
  application. Components can be skinned with standard Web technologies such as CSS.
- Self-contained application deployment model. Self-contained application packages have all the application resources
  and a private copy of the Java and JavaFX runtimes. They are distributed as native installable packages and provide
  the same installation and launch experience as native applications for that operating system. JavaFX is a software
  platform for creating and delivering desktop applications, as well as rich Internet applications (RIAs) that can run
  across a wide variety of devices.

Over the years the way of creating GUIs has often changed and JavaFX default appearance is still pretty much the same.
That's where this project comes in. The aim of my project is to bring components which follow as much as possible the
Google's material design guidelines to JavaFX. The second purpose is to provide a successor to the already
available [JFoenix](https://github.com/Londjide/MaterialFX/releases) library, which is a bit old and has a lot of issues.

In recent months the project has evolved a lot, to the point that it is no longer a simple substitute.  
To date MaterialFX offers not only restyled controls, but also: new and unique controls such as the Stepper,
controls completely redone from scratch such as ComboBoxes or TableViews (and many others),
and many utilities for JavaFX and Java (NodeUtils, ColorUtils, StringUtils ...).

<!-- ABOUT THE PROJECT -->

## About The Logo
MaterialFX v11.13.0 brought a lot of fixes and new features, but it also brought a new logo, something that is more
meaningful for me and that somewhat represents the new version.  
The new logo is a Phoenix, the immortal bird from Greek mythology, associated to regeneration/rebirth.
When a Phoenix dies it obtains new life by raising from its ashes.  
MaterialFX v11.13.0 fixed many critical bugs and broken features, I like to think that it is reborn from
the previous version, so I thought a new logo would have been a good idea. 

<!-- PREVIEW GIFS -->

## Preview GIFs

#### Imgur Link: [Gallery](https://github.com/Londjide/MaterialFX/releases)

<i>
<details>
<summary>Buttons</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Buttons" border="0">
</details>
<p></p>

<details>
<summary>Check Boxes, Radio Buttons and Toggles</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Checkboxes" border="0">
</details>
<p></p>

<details>
<summary>Combo Boxes</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Comboboxes" border="0">
</details>
<p></p>

<details>
<summary>Dialogs</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Dialogs" border="0">
</details>

<p></p>
<details>
<summary>Fields</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Fields" border="0">
</details>
<p></p>

<details>
<summary>Lists</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Listviews" border="0">
</details>
<p></p>

<details>
<summary>Notifications</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Notifications" border="0">
</details>
<p></p>

<details>
<summary>Pickers</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Pickers" border="0">
</details>
<p></p>

<details>
<summary>Progress</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Progress" border="0">
</details>
<p></p>

<details>
<summary>Scroll Panes</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Scrollpanes" border="0">
</details>
<p></p>

<details>
<summary>Sliders</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Sliders" border="0">
</details>
<p></p>


<details>
<summary>Stepper</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Stepper" border="0">
</details>
<p></p>

<details>
<summary>Tables</summary>
<br>
<img src="https://github.com/Londjide/MaterialFX/releases" alt="Tableviews" border="0">
</details>
<p></p>

<!-- GETTING STARTED -->

## Getting Started

In this section you can learn what do you need to use my library in your project or see a preview/demo which I'm
planning to release as runtime images here on github.

### Build

To build MaterialFX, execute the following command:

    gradlew build

To run the main demo, execute the following command:

    gradlew run

**NOTE**: MaterialFX requires **Java 11** and above.
  
**NOTE**: Starting from version 11.14.0 (next major version), MaterialFX will transition to
Java 17 and bump version to 17.x.x. What will happen to version 11 is still to be decided

### Usage

###### Gradle

```groovy
repositories {
    mavenCentral()
}

dependencies {
  implementation 'https://github.com/Londjide/MaterialFX/releases'
}
```

###### Maven

```xml

<dependency>
  <groupId>https://github.com/Londjide/MaterialFX/releases</groupId>
  <artifactId>materialfx</artifactId>
  <version>11.13.5</version>
</dependency>
```

<!-- DOCUMENTATION -->
## Documentation
You can read MaterialFX's documentation at [https://github.com/Londjide/MaterialFX/releases](https://github.com/Londjide/MaterialFX/releases)
                                                                    
<!-- CHANGELOG -->

## Changelog

See the [CHANGELOG](https://github.com/Londjide/MaterialFX/releases) file for a list of changes per
version.

<!-- ROADMAP -->

## Roadmap

See the [Open Issues](https://github.com/Londjide/MaterialFX/releases) for a list of proposed features (and known issues)
.  
See the [ROADMAP](https://github.com/Londjide/MaterialFX/releases) for a list of implemented and upcoming
features.

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any
contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the GNU LGPLv3 License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Alex - https://github.com/Londjide/MaterialFX/releases  
[![Discord](https://github.com/Londjide/MaterialFX/releases)](https://github.com/Londjide/MaterialFX/releases)
<br /><br />
Project Link: [https://github.com/Londjide/MaterialFX/releases](https://github.com/Londjide/MaterialFX/releases)

<!-- DONATION -->

#### Donation

It's been more than a year since I started developing MaterialFX. Implementing cool looking, fully functional controls,
introducing new components and features as well as providing many utilities for JavaFX and Java is really hard,
especially considering that developing for JavaFX also means to deal with its closeness, its bugs, its annoying
design decisions. Many times I've honestly been on the verge of giving up because sometimes it's really too much
stress to handle.  
**But**, today MaterialFX is a great library, supported by many people and I'm proud of it.
If you are using MaterialFX in your projects and feel like it, I recently activated [GitHub Sponsors](https://github.com/Londjide/MaterialFX/releases) so
you can easily donate/sponsor.

<!-- SUPPORTERS -->

# Supporters:
(If you want your github page to be linked here and you didn't specify your username in the donation, feel free to contact me by email and tell me. Also contact me if for some some reason you don't want to be listed here)

- Alaa Abu Zidan
- Alex Hawk
- Aloento
- Mauro de Wit
- Mohammad Chaudhry (thank you very much for the huge donation, YOU are the legend)
- Sourabh Bhat
- Ultraviolet-Ninja
- Yahia Rehab
- Yiding He
- *Your name can be here by supporting me at this link, [GitHub Sponsors](https://github.com/Londjide/MaterialFX/releases)*

Thank you very very much to all supporters, to all people who contribute to the project, to all people that thanked me, you really made my day
