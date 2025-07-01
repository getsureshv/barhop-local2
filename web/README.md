# **React** | _**MikeHowrenBarHoppingV1**_ | _**427772**_ | _**studio_pro**_

## **Catalog ProjectId: 195837** | **Catalog BuildId: 45146**

## NOTE FOR DEVELOPERS:
Clone the code-engine branch into your working branch. The contents of the branch may get overwritten.
## Author:
Code-Engine
## Keywords:
 - mikehowrenbarhoppingv1
 - mobile
 - web

## Flags
| **Flag Name**        | **Enabled**        | **Value**  |
|:-------------|:-------------|:-------------|
| pro_boilerplate_tag<br>      | {-False-}<br>      | v1.0.0<br> |
| pro_core_block_tag<br>      | {-False-}<br>      | v1.0.0<br> |

## Repo Branches
| **Context**        | **Branch**        |
|:-------------|:-------------|
| boilerplate<br>      | master<br>      |
| core block<br>      | master<br>      |
## Assembled Features To Block Status

| **Feature-ID** | **Feature-Name**        | **Block-Name (Certification Type)**        | **Version**  | **Path**  | **Status**  |
|:-------------|:-------------|:-------------|:-------------|:-------------|:-------------|
| 1876 | navigation menu      | navigationmenu (FULL)<br>core (FULL)<br>      | 1.0.0<br>1.0.0<br> | {+packages/blocks/navigationmenu+}<br>{+packages/blocks/core+}<br> | {+Non-Empty+} | 
| 2606 | signup/login      | email-account-login (FULL)<br>utilities (FULL)<br>email-account-registration (FULL)<br>country-code-selector (FULL)<br>forgot-password (FULL)<br>otp-input-confirmation (FULL)<br>social-media-account (FULL)<br>      | 1.1.1<br>1.0.0<br>1.0.0<br>1.0.0<br>1.0.0<br>1.0.0<br>1.0.0<br> | {+packages/blocks/email-account-login+}<br>{+packages/blocks/utilities+}<br>{+packages/blocks/email-account-registration+}<br>{+packages/blocks/country-code-selector+}<br>{+packages/blocks/forgot-password+}<br>{+packages/blocks/otp-input-confirmation+}<br>{+packages/blocks/social-media-account+}<br> | {+Non-Empty+} | 
| 1658 | location      | location (FULL)<br>      | 1.0.0<br> | {+packages/blocks/location+}<br> | {+Non-Empty+} | 
| 2786 | terms and conditions      | termsconditions<br>      | <br> | {+packages/blocks/termsconditions+}<br> | {+Non-Empty+} | 
| 697 | content management      | contentmanagement (LITE)<br>      | 0.0.1<br> | {+packages/blocks/contentmanagement+}<br> | {+Non-Empty+} | 
| 194 | advanced search      | advancedsearch (FULL)<br>      | 1.0.0<br> | {+packages/blocks/advancedsearch+}<br> | {+Non-Empty+} | 
| 235 | analytics      | analytics (FULL)<br>      | 1.0.0<br> | {+packages/blocks/analytics+}<br> | {+Non-Empty+} | 
| 1241 | gallery      | photolibrary<br>      | <br> | {+packages/blocks/photolibrary+}<br> | {+Non-Empty+} | 
| 1739 | maps      | maps (FULL)<br>      | 1.0.0<br> | {+packages/blocks/maps+}<br> | {+Non-Empty+} | 
| 1583 | landing page      | landingpage (FULL)<br>      | 1.0.0<br> | {+packages/blocks/landingpage+}<br> | {+Non-Empty+} | 
| 689 | contact us      | contactus (FULL)<br>      | 1.0.0<br> | {+packages/blocks/contactus+}<br> | {+Non-Empty+} | 
| 875 | customisable user profiles      | customisableuserprofiles (LITE)<br>      | 0.0.1<br> | {+packages/blocks/customisableuserprofiles+}<br> | {+Non-Empty+} | 
| 803 | custom form      | customform (LITE)<br>      | 0.0.1<br> | {+packages/blocks/customform+}<br> | {+Non-Empty+} | 
| 581 | catalogue      | catalogue (FULL)<br>      | 1.0.0<br> | {+packages/blocks/catalogue+}<br> | {+Non-Empty+} | 
| 261 | product tutorial      | onboardingguide (FULL)<br>      | 1.0.0<br> | {+packages/blocks/onboardingguide+}<br> | {+Non-Empty+} | 
| 1178 | filter items      | filteritems (FULL)<br>      | 1.0.0<br> | {+packages/blocks/filteritems+}<br> | {+Non-Empty+} | 
| 2446 | roles and permissions      | rolesandpermissions2      |  | {-packages/blocks/rolesandpermissions2-} | {-Empty-} | 
| 172 | admin console      | adminconsole2      |  | {-packages/blocks/adminconsole2-} | {-Empty-} | 
| 2584 | settings      | settings2      |  | {-packages/blocks/settings2-} | {-Empty-} | 
| 2979 | upload media      | uploadmedia3      |  | {-packages/blocks/uploadmedia3-} | {-Empty-} | 
| 59546 | check in      | checkin1      |  | {-packages/blocks/checkin1-} | {-Empty-} | 

## AWS BACKEND DEPLOYMENT URL
 - BaseURL exported as: "https://mikehowrenbarhoppingv1-427772-ruby.b427772.prd.eastus.az.svc.builder.ai"
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

See docs folder for additional information.

### Prerequisites

What things you need to install the software and how to install them

- React Native (last tested on react-native 0.64.4)

  - https://facebook.github.io/react-native/docs/getting-started

- IFF brew is installed and user doesn't have permisions.

```
  $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)"
  $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- XCode 11 or greater

- XCode Command Line Tools

```
  $ xcode-select --install
```

- Android SDK

```
  $ brew cask install android-sdk
```

- JDK 11

```
  $ brew tap homebrew/cask-versions
  $ brew cask install java
  $ brew cask install java11
```

Or if you are using a Macbook with an Apple Silicon chip (M1 or M2) then we highly recommend using the Azul Zulu distribution of the Java Development Kit as it has better support for M1/M2 macs than the standard distribution:

```
  $ brew tap homebrew/cask-versions
  $ brew install --cask zulu11
```

### Installing

A step by step series of examples that tell you how to get a development env running

Install yarn

```
  $ brew install yarn
```

Install node

```
  $ brew install node
```

Web

```
  $ yarn
  $ yarn web
  (Note: After udpating depencies run again if no cocde erros. )
```

iOS

```
  $ yarn
  $ yarn iosbundle
  $ yarn ios
```

Android - https://docs.expo.io/versions/latest/workflow/android-studio-emulator/

```
  $ yarn
  $ export JAVA_HOME=`/usr/libexec/java_home -v 11`; java -version; export ANDROID_HOME=${HOME}/Library/Android/sdk; export PATH=${PATH}:${ANDROID_HOME}/emulator && yarn android
```

## Running the tests

Unit tests can be run at the block level. Inside the block folder where you'd like to run your unit tests, you can run

```
  $ yarn test
```

## CI/CD Details

We use GitlabCI for our deployment/Build pipelines

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Patches

There are a few small patches applied to the node modules folder that will be automatically applied after the yarn install process is complete.
