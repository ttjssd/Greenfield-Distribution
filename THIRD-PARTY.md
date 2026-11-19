# Third-party components

GREENFIELD launcher is built with .NET 8 / WPF (MIT) and CmlLib.Core 4.0.6 (MIT).
Sources and licenses:
- https://github.com/dotnet/runtime/blob/main/LICENSE.TXT
- https://github.com/dotnet/wpf/blob/main/LICENSE.TXT
- https://github.com/CmlLib/CmlLib.Core/blob/master/LICENSE
- https://www.nuget.org/packages/System.Security.Cryptography.ProtectedData/8.0.0

Client files are downloaded directly from the original Modrinth CDN and are not embedded in this package:

| Component | Fixed version | License / source |
|---|---|---|
| Fabric API | 0.159.0+26.2 | Apache-2.0 · https://modrinth.com/mod/fabric-api |
| Sodium | 0.9.2 | Polyform Shield 1.0.0 · https://modrinth.com/mod/sodium |
| Iris | 1.11.4 | LGPL-3.0-only · https://modrinth.com/mod/iris |
| Entity Model Features | 3.3.12 | LGPL-3.0-only · https://modrinth.com/mod/entity-model-features |
| Entity Texture Features | 7.2.6 | LGPL-3.0-only · https://modrinth.com/mod/entitytexturefeatures |
| Reese's Sodium Options | 2.2.4 | MIT · https://modrinth.com/mod/reeses-sodium-options |
| Sodium Extra | 0.9.3 | LGPL-3.0-only · https://modrinth.com/mod/sodium-extra |
| Fresh Animations | 1.11.2 | Custom terms · https://modrinth.com/resourcepack/fresh-animations |
| Solas Shader | 3.7b | All Rights Reserved · https://modrinth.com/shader/solas-shader |

Fresh Animations is by FreshLX. The published terms permit modpack/server use but restrict standalone redistribution. GREENFIELD references its official download and does not embed or modify it. The paid FA+Player add-on is excluded.
Solas is by Septonious. Its original official CDN download is used; no copy is rehosted in this repository or release archive.

Fabric Loader 0.19.5 is obtained from Fabric's official Maven/meta service: https://github.com/FabricMC/fabric-loader (Apache-2.0).
Minecraft and managed Java are downloaded from original launcher metadata. Minecraft is not redistributed. A valid Java Edition account is required.

No RPGCore ClientUI, RPGStudioPack, RPG models, game UI, item textures or authentication data are included.

The premium farm background was generated/edited with OpenAI image_gen from the operator-provided visual reference. It contains no copied RPG pack assets. Native logo/UI shapes are launcher components. The background is embedded in the launcher; logos, panels and buttons are separate native WPF controls.

GREENFIELD Inventory is an original client-only Fabric mod. Its wood/cream frame was generated with OpenAI image_gen from the operator's UI reference, with transparent exterior and no landscape. The logo is a raster text image, not a redistributed font file. The resource pack only defines greenfield_inventory assets. No vanilla game art, RPG pack art or test-world screenshots are embedded in the inventory pack.
