# Changelog

### [1.1.3](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/compare/v1.1.2...v1.1.3) (2021-05-09)

#### Miscellaneous Chores

* **deps:** bump io.extendreality.zinnia.unity from 1.35.0 to 1.36.0 ([50dd7a3](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/50dd7a31f19f2ff46061f9fb8b003f15767ace7f))
  > Bumps [io.extendreality.zinnia.unity](https://github.com/ExtendRealityLtd/Zinnia.Unity) from 1.35.0 to 1.36.0. - [Release notes](https://github.com/ExtendRealityLtd/Zinnia.Unity/releases) - [Changelog](https://github.com/ExtendRealityLtd/Zinnia.Unity/blob/master/CHANGELOG.md) - [Commits](https://github.com/ExtendRealityLtd/Zinnia.Unity/compare/v1.35.0...v1.36.0)
  > 
  > Signed-off-by: dependabot[bot] <support@github.com>

### [1.1.2](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/compare/v1.1.1...v1.1.2) (2021-05-03)

#### Miscellaneous Chores

* **deps:** bump io.extendreality.zinnia.unity from 1.34.1 to 1.35.0 ([d6218a1](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/d6218a19786a962e9c06319a86f4ff9b15e20407))
  > Bumps [io.extendreality.zinnia.unity](https://github.com/ExtendRealityLtd/Zinnia.Unity) from 1.34.1 to 1.35.0. - [Release notes](https://github.com/ExtendRealityLtd/Zinnia.Unity/releases) - [Changelog](https://github.com/ExtendRealityLtd/Zinnia.Unity/blob/master/CHANGELOG.md) - [Commits](https://github.com/ExtendRealityLtd/Zinnia.Unity/compare/v1.34.1...v1.35.0)
  > 
  > Signed-off-by: dependabot[bot] <support@github.com>

### [1.1.1](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/compare/v1.1.0...v1.1.1) (2021-04-12)

#### Bug Fixes

* **README.md:** provide correct badge links ([2e98c34](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/2e98c346d024d68e59f3016e49fd8a73280b3c67))
  > The badge links were incorrect causing the badges to not display.

## [1.1.0](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/compare/v1.0.1...v1.1.0) (2021-04-07)

#### Features

* **Utility:** add prefab creator ([7aa6aff](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/7aa6aff37a4b3157e0166128584a0f615e13c676))
  > The latest version of Zinnia has the basis of a prefab creator that can be used to enable easy adding of prefabs to a scene without needing to drag and drop from directories. Instead a new menu item is added for quickly adding prefabs. The guide has been updated to accommodate this and the FodyWeavers.xml is now located in the root to serve both the Runtime and Editor scripts.

#### Bug Fixes

* **FodyWeavers:** add missing weaver file ([baa84f8](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/baa84f8555b42e7d9eedd1ea329aa95acc7bb2d3))
  > Whilst there is no definite need for a Fody Weaver file in this repo, it is worth adding it for consistency with other repos that have code.
* **package.json:** add missing reference to Editor directory ([1981c9b](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/1981c9b410a29bc5a05f06065c0da8cfd66eca3f))
  > The build will fail without referencing this new Editor directory so it has now been added to the package.

### [1.0.1](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/compare/v1.0.0...v1.0.1) (2021-03-31)

#### Miscellaneous Chores

* **deps:** bump io.extendreality.zinnia.unity from 1.31.1 to 1.33.0 ([863502d](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/863502de0ec9e2a71f5a6ed1a046db8380230c4d))
  > Bumps [io.extendreality.zinnia.unity](https://github.com/ExtendRealityLtd/Zinnia.Unity) from 1.31.1 to 1.33.0. - [Release notes](https://github.com/ExtendRealityLtd/Zinnia.Unity/releases) - [Changelog](https://github.com/ExtendRealityLtd/Zinnia.Unity/blob/master/CHANGELOG.md) - [Commits](https://github.com/ExtendRealityLtd/Zinnia.Unity/compare/v1.31.1...v1.33.0)
  > 
  > Signed-off-by: dependabot[bot] <support@github.com>

## 1.0.0 (2021-03-31)

#### Features

* **structure:** add prefab and base documentation ([b179d8e](https://github.com/ExtendRealityLtd/Tilia.CameraRigs.XRPluginFramework.Unity/commit/b179d8e9b2d0cb81cc77c59319f8d62e4b507211))
  > The base XR Plugin Framework camera rig prefab has been added along with the required base documentation.
