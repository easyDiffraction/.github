<p align='left'>
  <picture>
    <!-- light mode logo -->
    <source media='(prefers-color-scheme: light)' srcset='https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyScience/logos/es-logo_light.svg'>
    <!-- dark mode logo -->
    <source media='(prefers-color-scheme: dark)' srcset='https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyScience/logos/es-logo_dark.svg'>
    <!-- default logo == light mode logo -->
    <img src='https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyScience/logos/es-logo_light.svg' alt='EasyCrystallography'>
  </picture>
</p>

<table class="images" width="100%"  style="border:0px solid white; width:100%;">
    <tr style="border: 0px;">
        <td width="33%" style="border:0px; width:33.33%">
            <img src="..." />
        </td>
        <td width="33%" style="border:0px; width:33.33%">
            <img src="..." />
        </td>
        <td width="33%" style="border:0px; width:33.33%">
            <img src="..." />
        </td>
    </tr>
</table>

**EasyScience** is a versatile data analysis framework designed to streamline the journey from data collection to publication. It provides:
- **Powerful back-end tools**: Core functionality through Python libraries.
- **Efficient front-end modules**: QML components for developing desktop applications with ease.

Explore our dedicated repositories for specific techniques:

<style>
td, th {
   border: none!important;
}
</style>

|                             | 🏠 Project Hub      | 📦 Python Library      | 💻 Desktop Application | 🌐 Main Web Page       |
|-----------------------------|---------------------|------------------------|------------------------|------------------------|
| ![ed-dark]![ed-light]       | [diffraction]       | [diffraction-lib]      | [diffraction-app]      | [diffraction-page]     |
| ![er-dark]![er-light]       | [reflectometry]     | [reflectometry-lib]    | [reflectometry-app]    | [reflectometry-page]   |
| ![ei-dark]![ei-light]       | [imaging]           | [imaging-lib]          | [imaging-app]          |                        |
| ![eq-dark]![eq-light]       | [dynamics]          | [dynamics-lib]         | [dynamics-app]         |                        |
| ![et-dark]![et-light]       |                     |                        | [texture-app]          |                        |

## Full List of Repositories

### 1. Technique-Specific Projects

|                             | Repository              | Description                                                                                         |
|-----------------------------|-------------------------|-----------------------------------------------------------------------------------------------------|
| ![ed-dark]![ed-light]       | 🏠 [diffraction]        | Launching point for the EasyDiffraction family of repositories                                      |
|                             | 📦 [diffraction-lib]    | Python library for diffraction data analysis                                                        |
|                             | 💻 [diffraction-app]    | Desktop application for diffraction data analysis                                                   |
|                             | 🌐 [diffraction-page]   | Main web page for EasyDiffraction                                                                   |
| ![er-dark]![er-light]       | 🏠 [reflectometry]      | Launching point for the EasyReflectometry family of repositories                                    |
|                             | 📦 [reflectometry-lib]  | Python library for reflectometry data analysis                                                      |
|                             | 💻 [reflectometry-app]  | Desktop application for reflectometry data analysis                                                 |
|                             | 🌐 [reflectometry-page] | Main web page for EasyReflectometry                                                                 |
| ![ei-dark]![ei-light]       | 🏠 [imaging]            | Launching point for the EasyImaging (Bragg-edge imaging) family of repositories                     |
|                             | 📦 [imaging-lib]        | Python library for Bragg-edge imaging data analysis                                                 |
|                             | 💻 [imaging-app]        | Desktop application for Bragg-edge imaging data analysis                                            |
| ![eq-dark]![eq-light]       | 🏠 [dynamics]           | Launching point for the EasyDynamics (Quasielastic Neutron Scattering, QENS) family of repositories |
|                             | 📦 [dynamics-lib]       | Python library for quasielastic neutron scattering data analysis                                    |
|                             | 💻 [dynamics-app]       | Desktop application for quasielastic neutron scattering imaging data analysis                       |
| ![et-dark]![et-light]       | 💻 [texture-app]        | Desktop application for texture data reduction                                                      |

### 2. Generic Projects

|                           | Repository                    | Description                                                                |
|---------------------------|-------------------------------|----------------------------------------------------------------------------|
| ![es-dark]![es-light]     | [.github]                     | EasyScience organization profile                                           |
|                           | [easyscience-page]            | Main web page for the EasyScience organization                             |
|                           | [easyscience-corelib]         | Core building blocks for Python libraries in the EasyScience framework     |
| ![escr-dark]![escr-light] | [easyscience-crystallography] | Backend crystallographic tools in the EasyScience framework                |
|                           | [easyscience-guilib]          | Graphical components for desktop applications in the EasyScience framework |

### 3. Common Resources

| Repository          | Description                                                   |
|---------------------|---------------------------------------------------------------|
| [assets-branding]   | Logos, icons, and branding assets for the entire organization |
| [assets-page]       | Shared assets for project web pages                           |
| [assets-docs]       | Shared assets for project documentation                       |
| [templates-project] | Copier template for technique-specific EasyScience projects   |

### 4. Other EasyScience Repositories

| Repository | Description                                                 |
|------------|-------------------------------------------------------------|
| [pypi]     | Custom Python package index for EasyScience-based libraries |

### 5. Third-Party Projects

| Repository       | Description                                  |
|------------------|----------------------------------------------|
| [deps-cryspy]    | Custom version of the CrysPy library         |
| [deps-pycrysfml] | Python bindings for the CrysFML2008 library  |
| [deps-pdffit2]   | Custom version of the diffpy.pdffit2 library |


## Repositories to be Merged

Add the prefix `to_be_merged__` to repositories that will be integrated into others:

- [EasyDiffractionLibDocs](https://github.com/EasyScience/EasyDiffractionLibDocs): Will be merged into the `docs/` directory of [EasyDiffractionLib](https://github.com/EasyScience/EasyDiffractionLib).
- [EasyDiffractionAppDocs](https://github.com/EasyScience/EasyDiffractionAppDocs): Will be merged into the `docs/` directory of [EasyDiffractionApp](https://github.com/EasyScience/EasyDiffractionApp).

## Repositories to be Checked

Add the prefix `to_be_checked__` to repositories under review:

- [easyAppWww](https://github.com/EasyScience/easyAppWww)
- [easyCoreWww](https://github.com/EasyScience/easyCoreWww)
- [easyExampleLib](https://github.com/EasyScience/easyExampleLib)
- [easySkeletonApp](https://github.com/EasyScience/easySkeletonApp)
- [easyTemplateLib](https://github.com/EasyScience/easyTemplateLib)

## Repositories to be Removed

Add the prefix `to_be_removed__` to repositories slated for removal:

- [demo-repository](https://github.com/EasyScience/demo-repository)
- [diffpy.structure](https://github.com/EasyScience/diffpy.structure)
- [easyAppGui](https://github.com/EasyScience/easyAppGui)
- [easyAppLogic](https://github.com/EasyScience/easyAppLogic)
- [libsDarwin](https://github.com/EasyScience/libsDarwin)
- [libsLinux](https://github.com/EasyScience/libsLinux)
- [libsWin32](https://github.com/EasyScience/libsWin32)
- [matplotlib_backend_qtquick](https://github.com/EasyScience/matplotlib_backend_qtquick)
- [pycrysfml08](https://github.com/EasyScience/pycrysfml08)
- [EasyScience_old](https://github.com/EasyScience/EasyScience_old)
- [test_conditional](https://github.com/EasyScience/test_conditional)


<!---URLs--->

[ed-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDiffraction/logos/ed-logo_102x32_dark.svg#gh-dark-mode-only
[ed-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDiffraction/logos/ed-logo_102x32_light.svg#gh-light-mode-only
[er-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyReflectometry/logos/er-logo_120x32_dark.svg#gh-dark-mode-only
[er-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyReflectometry/logos/er-logo_120x32_light.svg#gh-light-mode-only
[ei-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyImaging/logos/ei-logo_84x32_dark.svg#gh-dark-mode-only
[ei-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyImaging/logos/ei-logo_84x32_light.svg#gh-light-mode-only
[eq-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDynamics/logos/eq-logo_93x32_dark.svg#gh-dark-mode-only
[eq-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDynamics/logos/eq-logo_93x32_light.svg#gh-light-mode-only
[esh-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyShapes/logos/esh-logo_79x32_dark.svg#gh-dark-mode-only
[esh-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyShapes/logos/esh-logo_79x32_light.svg#gh-light-mode-only
[esh-2-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyShapes/logos/esh-logo-2_79x32_dark.svg#gh-dark-mode-only
[esh-2-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyShapes/logos/esh-logo-2_79x32_light.svg#gh-light-mode-only
[et-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyTexture/logos/et-logo_80x32_dark.svg#gh-dark-mode-only
[et-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyTexture/logos/et-logo_80x32_light.svg#gh-light-mode-only

[es-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyScience/logos/es-logo_81x32_dark.svg#gh-dark-mode-only
[es-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyScience/logos/es-logo_81x32_light.svg#gh-light-mode-only
[esco-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDiffraction/logos/ed-logo_102x32_dark.svg#gh-dark-mode-only
[esco-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDiffraction/logos/ed-logo_102x32_light.svg#gh-light-mode-only
[escr-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyCrystallography/logos/ecr-logo_132x32_dark.svg#gh-dark-mode-only
[escr-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyCrystallography/logos/ecr-logo_132x32_light.svg#gh-light-mode-only
[esap-dark]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDiffraction/logos/ed-logo_102x32_dark.svg#gh-dark-mode-only
[esap-light]: https://raw.githubusercontent.com/EasyScience/BrandingResources/refs/heads/master/EasyDiffraction/logos/ed-logo_102x32_light.svg#gh-light-mode-only

<!---Diffraction--->
[diffraction]: https://github.com/EasyScience/EasyDiffraction
[diffraction-lib]: https://github.com/EasyScience/EasyDiffractionLib
[diffraction-app]: https://github.com/EasyScience/EasyDiffractionApp
[diffraction-page]: https://easyscience.github.io/EasyDiffractionWww
[diffraction-lib-docs]: https://easyscience.github.io/EasyDiffractionLibDocs
[diffraction-app-docs]: https://easyscience.github.io/EasyDiffractionAppDocs

<!---Reflectometry--->
[reflectometry]: https://github.com/EasyScience/EasyReflectometry
[reflectometry-lib]: https://github.com/EasyScience/EasyReflectometryLib
[reflectometry-app]: https://github.com/EasyScience/EasyReflectometryApp
[reflectometry-page]: https://easyscience.github.io/EasyReflectometryWww

<!---Imaging--->
[imaging]: https://github.com/EasyScience/EasyReflectometry
[imaging-lib]: https://github.com/EasyScience/EasyImagingLib
[imaging-app]: https://github.com/EasyScience/EasyImagingApp

<!---QENS/Spectroscopy--->
[dynamics]: https://github.com/EasyScience/EasyQens
[dynamics-lib]: https://github.com/EasyScience/EasyQensLib
[dynamics-app]: https://github.com/EasyScience/EasyQensApp

<!---Shapes/Shapespyer--->
[shapes-app]: https://github.com/easyscience/shapes-app

<!---Texture--->
[texture-app]: https://github.com/EasyScience/EasyTextureApp

<!---Shape--->
[shape-app]: https://github.com/EasyScience/shape-app

<!---Generic projects-->
[.github]: https://github.com/EasyScience/.github
[easyscience-corelib]: https://github.com/EasyScience/EasyScience
[easyscience-guilib]: https://github.com/EasyScience/EasyApp
[easyscience-crystallography]: https://github.com/EasyScience/EasyCrystallography
[easyscience-page]: https://github.com/EasyScience/easyScienceWww

<!---Common resources--->
[assets-branding]: https://github.com/EasyScience/BrandingResources
[assets-page]: https://github.com/EasyScience/EasySite
[assets-docs]: https://github.com/EasyScience/CommonDocsAssets

<!---Other EasyScience repositories--->
[templates-project]: https://github.com/EasyScience/EasyProjectTemplate
[pypi]: https://github.com/EasyScience/pypi

<!---Third-party projects--->
[deps-cryspy]: https://github.com/EasyScience/cryspy
[deps-pycrysfml]: https://github.com/EasyScience/PyCrysFML
[deps-pdffit2]: https://github.com/EasyScience/pdffit2
