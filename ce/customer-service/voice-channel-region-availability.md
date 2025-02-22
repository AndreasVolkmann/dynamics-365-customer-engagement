---
title: "Supported cloud locations, languages, and locale codes | MicrosoftDocs"
description: "Use this article to learn about the supported cloud locations, languages, and locale codes for the voice channel in Omnichannel for Customer Service."
author: neeranelli
ms.author: nenellim
manager: shujoshi
ms.date: 05/16/2022
ms.topic: article

---

# Supported cloud locations, languages, and locale codes 

[!INCLUDE[cc-use-with-omnichannel](../includes/cc-use-with-omnichannel.md)]

## Introduction

This article provides information about the supported cloud locations, languages, and locale codes.

> [!NOTE]
> For information about international availability of live chat and digital messaging channels, see [International availability of Omnichannel for Customer Service](international-availability.md#international-availability-of-omnichannel-for-customer-service).

## Supported cloud locations

Use the information in the following table to know about the availability of the voice channel in Omnichannel for Customer Service.

If the voice channel in Omnichannel for Customer Service for your country or region-specific cloud deployments are not yet available, use the general region deployments. For example, country/region cloud for local deployment in the United Kingdom is **To be announced** and is not a part of Europe geographical region availability.

 If you need your data to stay within a country or region, stay tuned for country or region-specific local deployment of the voice channel. More information: [Datacenter regions](/power-platform/admin/new-datacenter-regions)

> [!IMPORTANT]
> Your Microsoft 365 tenant must be co-located in one of the following geographic locations where Omnichannel for Customer Service is available. These geographic locations refer to your Microsoft 365 tenant only and not the data center where your Dynamics 365 environment or org instance resides.

|Geographic location | Availability | Availability in Customer Service trial|
|----------|---------|-----|
|North America (crm.dynamics.com) |November 2021  | November 2021|
|Europe, Middle East, Africa (crm4.dynamics.com)|December 2021 |To be announced|
|Asia Pacific (crm5.dynamics.com) |December 2021 |To be announced|
|Australia, New Zealand, Fiji (crm6.dynamics.com) |December 2021 |To be announced|
|South America (crm2.dynamics.com) |To be announced | To be announced|
|Country/Region clouds: Canada, France, Germany, India, Japan, Switzerland, United Arab Emirates (UAE), United Kingdom |To be announced |To be announced|
|Government Community Cloud (GCC) (crm9.dynamics.com) |To be announced |To be announced|
||||

### Direct offer availability

Azure direct offer or [Microsoft as a carrier](/azure/communication-services/concepts/telephony/telephony-concept) is available for customers with billing locations in the United States, United Kingdom, Ireland, and Puerto Rico.  Azure direct offer supports the following options:

- The purchase of new US and Puerto Rico numbers. For information, see [Subscription eligibility and number capabilities](/azure/communication-services/concepts/numbers/sub-eligibility-number-capability).
- The porting of existing US or toll-free phone numbers. For information, see [Port a phone number](/azure/communication-services/quickstarts/telephony/port-phone-number).
- The purchase of new numbers in United Kingdom (preview) and Denmark (preview). For information, see [Customers with UK Azure billing addresses](/azure/communication-services/concepts/numbers/sub-eligibility-number-capability#customers-with-uk-azure-billing-addresses) and [Customers with Denmark Azure Billing Addresses](/azure/communication-services/concepts/numbers/sub-eligibility-number-capability#customers-with-denmark-azure-billing-addresses). You can purchase the United Kingdom and Denmark numbers only if you have a billing address in the respective country. You must purchase the numbers through the Azure portal, then you can sync into Omnichannel for Customer Service through the [sync option](voice-channel-acs-resource.md#sync-from-azure).

The listed billing locations only are supported even if Microsoft as a carrier is available in other regions. Customers can select a [different carrier](voice-channel-bring-your-own-number.md) using Azure direct routing.

### Direct routing availability

Bring your own carrier through [Azure direct routing](/azure/communication-services/concepts/telephony/telephony-concept#azure-direct-routing) is supported across all geographic locations using certified Session Border Controllers. More information: [Bring your own carrier](voice-channel-bring-your-own-number.md)

In the geographic location where the voice channel is generally available, Azure direct routing extends general availability support.

## Supported languages and locale codes

See the information in the following table to know about the supported languages and locale codes.

We use the Azure Cognitive Services Speech service Speech-to-Text for transcription, so we'll support all the languages that Speech-to-Text supports today. We also support a bring-your-own bot through Azure Bot Service for Interactive Voice Response (IVR) that will be constrained by the languages that Speech-to-Text supports. End-to-end voice and IVR support is available only if a language is supported in the Power Virtual Agents or Azure Bot Service, and Omnichannel for Customer Service. Sentiment and AI insights are optional for the voice functionality.  

| Language | Locale code | Voice channel | Power Virtual Agents | Speech-to-Text | Text-to-Speech | Sentiment | AI suggestions | UI language support |
|----|----|----|----|----|----|----|----|----|
| Afrikaans - South Africa | `af- ZA` |x|x|x|x|x|x|x|
| Albanian | `sq` |x|x|x|x|x|x|x|
| Amharic | `am- ET` |x|x|x|x|x|x|x|
| Arabic - Algeria| `ar-DZ` |x|x|✔|✔|x|x|x|
| Arabic - Bahrain| `ar-BH` |x|x|✔|✔|x|x|x|
| Arabic - Egypt| `ar-EG` |x|x|✔|✔|x|x|x|
| Arabic - Iraq| `ar-IQ` |x|x|✔|✔|x|x|x|
| Arabic - Israel| `ar-IL` |x|x|✔|x|x|x|x|
| Arabic - Jordan| `ar-JO` |x|x|✔|✔|x|x|x|
| Arabic - Kuwait| `ar-KW` |x|x|✔|✔|x|x|x|
| Arabic - Lebanon| `ar-LB` |x|x|✔|x|x|x|x|
| Arabic - Libya| `ar-LY` |x|x|✔|✔|x|x|x|
| Arabic - Morocco| `ar-MA` |x|x|✔|✔|x|x|x|
| Arabic - Oman | `ar-OM` |x|x|✔|x|x|x|x|
| Arabic - Palestinian Authority| `ar-PS` |x|x|✔|x|x|x|x|
| Arabic - Qatar| `ar-QA` |x|x|✔|✔|x|x|x|
| Arabic - Saudi Arabia| `ar-SA` |✔|x|✔|✔|x|✔|✔|
| Arabic - Syria| `ar- SY` |x|x|✔|✔|x|x|x|
| Arabic - Tunisia| `ar-TN` |x|x|✔|✔|x|x|x|
| Arabic - United Arab Emirates| `ar-AE` |x|x|✔|✔|x|x|x|
| Arabic - Yemen| `ar-YE` |x|x|✔|✔|x|x|x|
| Armenian | `hy` |x|x|x|x|x|x|x|
| Assamese | `as` |x|x|x|x|x|x|x|
| Azerbaijani | `az` |x|x|x|x|x|x|x|
| Bangla - Bangladesh| `bn-BD` |x|x|x|x|x|x|x|
| Bashkir | `ba` |x|x|x|x|x|x|x|
| Basque| `eu-ES` |x|x|x|x|x|x|✔|
| Bengali - India| `bn-IN` |x|x|x|x|x|x|x|
| Bosnian (Latin) | `bs` |x|x|x|x|x|x|x|
| Bulgarian | `bg-BGC UI` |✔|x|✔|✔|✔|x|✔|
| Burmese - Myanmar| `my-MM` |x|x|x|x|x|x|x|
| Catalan | `ca` |✔|x|✔|✔|✔|x|✔|
| Chinese - China - Mandarin| `zh-CN` |✔|✔|✔|✔|✔|x|✔|
| Chinese - Hong Kong SAR - Cantonese - Taiwan - Traditional| `zh-CN` |✔|✔|✔|✔|✔|x|✔|
| Chinese - Literary | `lzh` |x|x|x|x|x|x|x|
| Croatian - Croatia | `hr-HR` |✔|x|✔|✔|✔|x|✔|x|
| Czech - Czech Republic | `cs-CZ` |✔|x|✔|✔|✔|x|✔|
| Danish - Denmark | `da-DK` |✔|✔|✔|✔|✔|x|✔|
| Dari | `prs` |x|x|x|x|x|x|x|
| Divehi | `dv` |x|x|x|x|x|x|x|
| Dutch - Belgium | `nl-BE` |x|x|✔|✔|x|x|x|
| Dutch - Netherlands | `nl-NL` |✔|✔|✔|✔|✔|✔|✔|
| English - Australia | `en-AU` |x|x|✔|✔|x|x|x|
| English - Canada | `en-CA` |x|x|✔|✔|x|x|x|
| English - Ghana | `en-GH` |x|x|✔|✔|x|x|x|
| English - Hong Kong | `en-HK` |x|x|✔|✔|x|x|x|
| English - India | `en-IN` |x|x|✔|✔|x|x|x|
| English - Ireland | `en-IE` |x|x|✔|✔|x|x|x|
| English - Kenya | `en-KE` |x|x|✔|✔|x|x|x|
| English - Nigeria | `en-NG` |x|x|✔|✔|x|x|x|
| English - New Zealand | `en-NZ` |x|x|✔|✔|x|x|x|
| English - Philippines | `en-PH` |x|x|✔|✔|x|x|x|
| English - Singapore | `en-SG` |x|x|✔|✔|x|x|x|
| English - South Africa | `en-SA` |x|x|✔|✔|x|x|x|
| English - Tanzania | `en-TZ` |x|x|✔|✔|x|x|x|
| English - United Kingdom | `en-GB` |x|x|✔|✔|x|x|x|
| English - United States | `en-US` |✔|✔|✔|✔|✔|✔|✔|
| Estonian - Estonia | `et-EE` |✔|x|✔|✔|✔|x|✔|
| Fijian | `fj` |x|x|x|x|x|x|x|
| Filipino | `fil-PH` |x|x|x|✔|x|x|x|
| Finnish | `fi-FI` |✔|x|✔|✔|✔|x|✔|
| French -Canada | `fr-CA` |x|x|✔|✔|x|x|x|
| French - France | `fr-FR` |✔|✔|✔|✔|✔|✔|✔|
| French - Switzerland| `fr-CH` |x|x|✔|✔|x|x|x|
| Galician | `gl-ES` |x|x|x|x|x|x|✔|
| Georgian | `ka` |x|x|x|x|x|x|x|
| German - Austria| `de-AT` |x|x|✔|✔|x|x|x|
| German - Germany | `de-DE` |✔|✔|✔|✔|✔|✔|✔|
| German - Switzerland | `de-CH` |x|x|✔|✔|x|x|x|
| Greek - Greece| `el-GR` |✔|x|✔|✔|✔|x|✔|
| Gujarati - India | `gu-IN` |x|x|✔|✔|x|x|x|
| Haitian Creole | `ht` |x|x|x|x|x|x|x|
| Hebrew - Israel | `he-IL` |✔|x|✔|✔|✔|x|✔|
| Hindi - India | `hi-IN` |✔|✔|✔|✔|✔|x|✔|
| Hmong Daw | `mww` |x|x|x|x|x|x|x|
| Hungarian - Hungary | `hu-HU` |✔|x|✔|✔|✔|x|✔|
| Icelandic - Iceland| `is-IS` |x|x|x|x|x|x|x|
| Indonesian - Indonesia | `id-ID` |✔|✔|✔|✔|✔|x|✔|
| Inuinnaqtun | `ikt` |x|x|x|x|x|x|x|
| Inuktitut | `iu` |x|x|x|x|x|x|x|
| Inuktitut - Latin | `iu-Latn` |x|x|x|x|x|x|x|
| Irish - Ireland | `ga-IE` |x|x|✔|✔|x|x|x|
| Italian - Italy| `it -IT` |✔|✔|✔|✔|✔|✔|✔|
| Japanese - Japan | `ja-JP` |✔|✔|✔|✔|✔|✔|✔|
| Javanese - Indonesia | `jv-ID` |x|x|x|x|x|x|x| 
| Kannada - India | `kn-IN` |x|x|✔|✔|x|x|x|
| Kazakh - Kazakhstan | `kk-KZ` |x|x|x|x|x|x|✔|
| Khmer - Cambodia | `km-KH` |x|x|x|x|x|x|x|
| Klingon | `tlh-` |x|x|x|x|x|x|x|
| Klingon (plqaD) | `tlh-Piqd` |x|x|x|x|x|x|x|
| Korean - Korea | `ko-KR` |✔|✔|✔|✔|✔|x|✔|
| Kurdish (Central) | `ku` |x|x|x|x|x|x|x|
| Kurdish (Northern) | `kmr` |x|x|x|x|x|x|x|
| Kyrgyz | `ky` |x|x|x|x|x|x|x|
| Lao - Laos | `lo-LA` |x|x|x|x|x|x|x|
| Latvian - Latvia | `lv-LV` |✔|x|✔|✔|✔|x|✔|
| Lithuanian - Lithuania | `lt-LT` |✔|x|✔|✔|✔|x|✔|
| Macedonian - Republic of North Macedonia | `mk-MK` |x|x|x|x|x|x|x|
| Malagasy | `mg` |x|x|x|x|x|x|x|
| Malay - Malaysia | `ms-MY` |✔|x|✔|✔|✔|x|✔|
| Malayalam - India | `ml-IN` |x|x|x|x|x|x|x|
| Maltese - Malta | `mt-MT` |x|x|✔|✔|x|x|x|
| Maori | `mi` |x|x|x|x|x|x|x|
| Marathi - India | `mr-IN` |x|x|✔|✔|x|x|x|
| Mongolian - Cyrillic | `mn-Cyrl` |x|x|x|x|x|x|x|
| Mongolian - Traditional | `mn-Mong` |x|x|x|x|x|x|x|
| Nepali | `ne` |x|x|x|x|x|x|x|
|Norwegian Bokmal - Norway| `nb-NO` |✔|✔|✔|✔|✔|x|✔|
| Odia | `or` |x|x|x|x|x|x|x|
| Pashto - Afghanistan | `ps-AF` |x|x|x|x|x|x|x|
| Persian - Iran | `fa-IR` |x|x|x|x|x|x|x|
| Polish - Poland | `pl-PL` |✔|✔|✔|✔|✔|x|✔|
| Portuguese - Brazil | `pt-BR` |✔|✔|✔|✔|✔|x|✔|
| Portuguese - Portugal | `pt-PT` |✔|x|✔|✔|x|x|x|
| Punjabi | `pa` |x|x|x|x|x|x|x|
| Queretaro Otomi | `otq` |x|x|x|x|x|x|x|
| Romanian - Romania | `ro-RO` |✔|x|✔|✔|✔|x|✔|
| Russian - Russia | `ru-RU` |✔|✔|✔|✔|✔|x|✔|
| Samoan | `sm` |x|x|x|x|x|x|x|
| Serbian (Cyrillic) - Serbia | `sr-Cyrl-CS` or sr-RS |x|x|x|x|✔|x|✔|
| Serbian (Latin) - Serbia | `sr-Latn-CS` |x|x|x|x|✔|x|✔|
| Sinhala - Sri Lanka | `si-LK` |x|x|x|x|x|x|x|
| Slovak - Slovakia | `sk-SK` |✔|x|✔|✔|✔|x|✔|
| Slovenian - Slovenia| `sl-SL` |✔|x|✔|✔|✔|x|✔|
| Somali - Somalia | `so-SO` |x|x|x|x|x|x|x|
| Spanish - Argentina | `es-AR` |x|x|✔|✔|x|x|x|
| Spanish - Bolivia| `es-BO` |x|x|✔|✔|x|x|x|
| Spanish - Chile | `es-CL` |x|x|✔|✔|x|x|x|
| Spanish - Colombia | `es-CO` |x|x|✔|✔|x|x|x|
| Spanish - Costa Rica| `es-CR` |x|x|✔|✔|x|x|x|
| Spanish - Cuba| `es-CU` |x|x|✔|✔|x|x|x|
| Spanish - Dominican Republic| `es-DO` |x|x|✔|✔|x|x|x|
| Spanish - Ecuador| `es-EC` |x|x|✔|✔|x|x|x|
| Spanish - El Salvador| `es-SV` |x|x|✔|✔|x|x|x|
| Spanish Equatorial Guinea| `es-GQ` |x|x|✔|✔|x|x|x|
| Spanish - Guatemala| `es-GT` |x|x|✔|✔|x|x|x|
| Spanish - Honduras| `es-HN` |x|x|✔|✔|x|x|x|
| Spanish - Mexico | `es-MX` |x|x|✔|✔|x|x|x|
| Spanish - Nicaragua| `es-NI` |x|x|✔|✔|x|x|x|
| Spanish - Panama| `es-PA` |x|x|✔|✔|x|x|x|
| Spanish - Paraguay| `es-PY` |x|x|✔|✔|x|x|x|
| Spanish - Peru| `es-PE` |x|x|✔|✔|x|x|x|
| Spanish - Puerto Rico| `es-PR` |x|x|✔|✔|x|x|x|
| Spanish - Spain | `es-ES` |✔|✔|✔|✔|✔|✔|✔|
| Spanish - Venezuela| `es-VE` |x|x|✔|✔|x|x|x|
| Spanish - Uruguay| `es-UY` |x|x|✔|✔|x|x|x|
| Spanish - US| `es-US` |x|x|✔|✔|x|x|x|
| Sudanese - Indonesia | `su-ID` |x|x|x|x|x|x|x|
| Swahili - Kenya| `sw-KE` |x|x|✔|✔|x|x|x|
| Swedish - Sweden | `sv-SE` |✔|✔|✔|✔|✔|x|✔|
| Swahili - Tanzania| `sw-TZ` |x|x|x|x|x|x|x|
| Tahitian | `ty` |x|x|x|x|x|x|x|
| Tamil - India | `ta-IN` |x|x|✔|✔|x|x|x|
| Tatar | `tt` |x|x|x|x|x|x|x|
| Telugu - India | `te-IN` |x|x|✔|✔|x|x|x|
| Thai - Thailand | `th-TH` |✔|x|✔|✔|✔|x|✔|
| Tibetan | `bo` |x|x|x|x|x|x|x|
| Tigrinya | `ti` |x|x|x|x|x|x|x|
| Tongan | `to` |x|x|x|x|x|x|x|
| Turkish - Turkey | `tr-TR` |✔|✔|✔|✔|✔|x|✔|
| Ukrainian - Ukraine | `uk-UA` |x|x|x|x|✔|x|✔|
| Upper Sorbian | `hsb` |x|x|x|x|x|x|x|
| Urdu - India | `ur-IN` |x|x|x|x|x|x|x|
| Uyghur | `ug` |x|x|x|x|x|x|x|
| Uzbek - Uzbekistan | `uz-UZ` |x|x|x|x|x|x|x|
| Vietnamese - Vietnam | `vi-VN` |✔|x|✔|✔|✔|x|✔|
| Welsh - United Kingdom | `cy-GB` |x|x|x|x|x|x|x|
| Yucatec Maya | `yua` |x|x|x|x|x|x|x|
| Zulu - South Africa| `zu-ZA` |x|x|x|x|x|x|x|
||||||||||

Use the information in the following table to find out more about language support for voice-related features.
 
| Feature |	List of supported languages |
| ---- | ---- |
| Transcription | [Language and speech support](/azure/cognitive-services/speech-service/language-support)|
| Power Virtual Agents (IVR) | [Power Virtual Agents supported languages](/power-virtual-agents/authoring-language-support)|
| Bring your own bot (IVR) | [Language and voice support for the Speech service](/azure/cognitive-services/speech-service/language-support)|
| AI suggestions | [Language support for AI suggestions](csw-enable-ai-suggested-cases-knowledge-articles.md#language-support-for-ai-suggestions)|
| Sentiment Analysis | [Multilingual sentiment](enable-sentiment-analysis.md#multilingual-sentiment) |
| Other Omnichannel for Customer Service features | [Language availability in Omnichannel for Customer Service](international-availability.md#language-availability)
|||

### See also

[Overview of the voice channel](voice-channel.md)  
[FAQ about the voice channel in Omnichannel for Customer Service](voice-channel-faqs.md)  

