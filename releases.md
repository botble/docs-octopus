# Release Notes

- [Octopus 1.4](#version_1_4)
- [Octopus 1.3](#version_1_3)
- [Octopus 1.2](#version_1_2)
- [Octopus 1.1](#version_1_1)
- [Octopus 1.0](#version_1_0)

## Octopus 1.4
### 15-09-2020
- Update to Laravel version 7.28
- Update homepage & blog page settings. Now, it's moved into Appearance -> Theme options.
- Move settings for Cookie Consent into Appearance -> Theme options.
- Add theme options to enable/disable Facebook chat, Facebook comment.
- Add settings for watermark. Now, you can add watermark by changing setting in Admin -> Settings -> Media.
- Allow to change permalink in Admin -> Settings -> Permalinks.
- Add language settings. Allow to set default language in Admin -> Settings -> General.
- Allow admin to login using email or username.
- Optimize queries to make site loads faster.
- Update UI.
- Refactor code.
- Fix webpack.mix.js config, issue with path on Windows.
- Fix assets path.
- Fix copy folder in Admin -> Media.

## Octopus 1.3
### 05-08-2020
- Upgrade to the latest Laravel framework version 7.22.
- Deprecated some media functions: `is_image`, `get_image_url`, `get_object_image`, `rv_media_handle_upload`. 
  Replacements: `RvMedia::isImage()`, `RvMedia::getImageUrl()`, `RvMedia::handleUpload()`.
- Add support **Digital Ocean Spaces**.
- Fix timezone, it doesn't work before.
- Fix filter posts.
- Update email settings. Add support **SES**, **Postmark**, **Array**, **Log**.
- Improve performance & refactor source code.
- Improve license system, make it works better.

- Add support DigitalOcean Spaces

<a name="version_1_2"></a>
### 03-07-2020

- Update to the latest Laravel version 7.18.
- Optimize database queries.
- Add support Recaptcha v3.
- Improve cookie consent.
- Fix bugs plugin Language.
- Add default open graph image.
- Improve admin UI.
- Refactor code.

<a name="version_1_1"></a>
### 29-05-2020

- Update to the latest Laravel version 7.13.
- Improve media module: support upload chunk size.
- Improve email system.
- Move `js-validation` package to `core`.
- Upgrade jQuery to v3.5.1 and Bootstrap 4.5.0.
- Improve admin UI.
- Refactor code.

<a name="version_1_0"></a>
### 2020-04-27
- Initial release version 1.0
