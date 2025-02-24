---
title: Azure Media Player Overview
description: Learn more about the Azure Media Player.
author: IngridAtMicrosoft
ms.author: inhenkel
ms.service: media-services
ms.topic: overview
ms.date: 04/05/2021
---

# Azure Media Player overview #

Azure Media Player is a web video player that plays media content from [Microsoft Azure Media Services](https://azure.microsoft.com/services/media-services/) on a wide variety of browsers and devices. Azure Media Player uses industry standards, such as HTML5, Media Source Extensions (MSE), and Encrypted Media Extensions (EME) to provide an enriched adaptive streaming experience.  When these standards are not available on a device or in a browser, Azure Media Player uses Flash and Silverlight as fallback technology. Regardless of the playback technology used, developers have a unified JavaScript interface to access APIs, allowing content served by Azure Media Services to be played across a wide range of devices and browsers without any extra effort.

Microsoft Azure Media Services allows for content to be served up with DASH, Smooth Streaming and HLS streaming formats to play back content. Azure Media Player takes into account these various formats and automatically plays the best link based on the platform/browser capabilities. Microsoft Azure Media Services also provides dynamic encryption of assets with common encryption (PlayReady or Widevine) or AES-128 bit envelope encryption. Azure Media Player allows for decryption of PlayReady and AES-128 bit encrypted content when appropriately configured.  To understand how to configure the player, see the [Protected Content](azure-media-player-protected-content.md) section.

If you have and specific issues, questions or find any bugs, please [file a support ticket](https://portal.azure.com/#blade/Microsoft_Azure_Support/HelpAndSupportBlade/overview) using the Client Playback category.

> [!NOTE]
> Please note that Azure Media Player only supports media streams from Azure Media Services.

## License ##

Azure Media Player is licensed and subject to the terms outlined in the Microsoft Software License Terms for Azure Media Player. See [license file](/legal/azure-media-player/azure-media-player-license) for full terms. For more information, see the [Privacy Statement](https://www.microsoft.com/en-us/privacystatement/default.aspx).

Copyright 2015 Microsoft Corporation.

## Next steps ##

- [Azure Media Player Quickstart](azure-media-player-quickstart.md)
