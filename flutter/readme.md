# ✨Your Project Name Here ✨

-  briefly describe what is the project about here

## Tech Stack 

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://docs.flutter.dev/get-started/install) 

<p align="center">
  <img src="https://github.com/rrousselGit/riverpod/blob/master/resources/icon/Facebook%20Cover%20A.png?raw=true"  alt="Riverpod" />
</p>

## Target Platforms & OS

- mobile:Android & iOS
- Android:21 - 30
- iOS:12.1


## Dependencies

- Assets, widgets and services of base for this project

## Packages

- **package_info:**requires the Xcode build folder to be rebuilt after changes to the version string
  in pubspec.yaml.

## Features

- **Login:**Currently the app is available in Malaysia my , Indonesia id & Thailand th.

## Useful Tools `Android Studio`

- Flutter Riverpod Snippets
- Flutter Freezed Snippets

## Useful Tools `vscode`

- Live Share
- GitLenze
- ESLint
- Dart Data Class Generator

## Distribution

- how the app is distributed?

## API Endpoints

The following section describes all the API endpoints which been used in the app, to get access of
services/functionality provided by this project or web services.

## 📡 Reach Out 📡

Solo Project:
- **Project Owner** : 📩 Puteri Alyaa <[puteri.alyaa.afzan@gmail.com](mailto:puteri.alyaa.afzan@gmail.com)><br>

If it's a team project:

- **Team leader**: B <[youremail@g.com](youremail@g.com)>
- **Team members**:
    - C <[cemail@g.com](cemail@g.com)>
- **Product Owner**: D <[demail@g.com](demail@g.com)>

## Changelog

| **Version**                                                 | **Changes**                                                |
|-------------------------------------------------------------|------------------------------------------------------------|
| [v1.8.4](/pathrepomain/subfolder/reponame/-/tags/v1.8.4)    | explain your issue at here                                 |
| [v1.8.3](/pathrepomain/subfolder/reponame/-/tags/v1.8.3)   | filename upload report issue fixed, and 504 error handling |

# This section is specific instruction of the packages/library (if it's used in the project)

## Generate Objectbox Database

### A

1. flutter clean
2. flutter pub get

### B

1. flutter pub run build_runner build --delete-conflicting-outputs
2. flutter packages pub run build_runner build --delete-conflicting-outputs

To generate Objectbox database do:
**A** then **B1** or **B2**

- It will generate `objectbox.g.dart` that `objectbox.g.dart` has some errors in the file.
- To resolve the issue,
  add `// ignore_for_file: camel_case_types, depend_on_referenced_packages, avoid_classes_with_only_static_members`
  to top of the file.

https://docs.objectbox.io/

https://sync.objectbox.io/sync-client

[Resolving Meta Model Conflicts](https://docs.objectbox.io/advanced/meta-model-ids-and-uids#resolving-meta-model-conflicts)

[DbSchemaException: incoming ID does not match existing UID](https://docs.objectbox.io/troubleshooting#dbschemaexception-incoming-id-does-not-match-existing-uid)
