# Privacy Policy for FormReady

**Effective date:** 11 October 2026

**Last updated:** 15 October 2026

**Application:** FormReady – Photo & Signature Formatter

**Android package:** `com.formready.imageutility`

**Privacy and support contact:** [codenotlie@gmail.com](mailto:codenotlie@gmail.com)

## 1. About this policy

FormReady helps you crop, rotate, resize, compress, convert and prepare photos and signatures for upload requirements. This policy explains local image processing, advertising, optional purchases, storage and your controls.

FormReady does not require a FormReady account and does not operate a custom image-processing server. Image work is local. Google advertising, consent and purchase services can use the internet and process information separately, as described below.

## 2. Selecting and processing images

You choose JPG or PNG images using Android's supported photo or file-selection interfaces. FormReady accesses the images you select rather than requesting broad access to all files or your entire photo library.

Selected photos and signatures are processed on your device. The app may copy an imported image into private app storage so editing or recovery does not depend on continued access to the original provider. It may retain the source's URI, filename, dimensions, file size and integrity information for processing and recovery.

FormReady processes image pixels locally and does not send imported photos or signatures to a FormReady processing server or include them in its advertising requests. It does not use those images for developer-operated advertising profiles or AI training. Original images are not intentionally overwritten. Newly generated image outputs omit source metadata such as location EXIF; an imported private source copy may still contain the original metadata.

Choosing an image stored by a cloud photo or file provider may require that provider to retrieve it. That provider's handling is separate from FormReady's local processing.

## 3. Private storage, saving and sharing

Private app storage may contain imported copies, generated results, editing recipes and crop history, unfinished-session recovery information, preferences, filename prefixes, custom presets, batch queues, output metadata, earned credits and temporary export/share files. Full image bytes are not placed in Android saved-screen-state bundles.

Saving uses Android's Storage Access Framework to create a new document at a destination you choose. Batch ZIP exports can include an output manifest with input names, result dimensions, formats, sizes, warnings and failures. Review the destination and information before exporting.

Sharing uses Android's share sheet and a restricted content URI with temporary read access to a prepared output copy. The recipient app or storage provider you select can process, transmit or retain that file under its own terms. A cloud destination or messaging app may upload it. FormReady does not control that recipient's delivery, encryption, retention or deletion, and does not automatically send your selected images to recipients.

## 4. Free advertising and optional rewarded batches

The Free version uses Google AdMob through the Google Mobile Ads SDK. It can display an eligible banner on Home only after an adult age-category choice and successful applicable consent checks. Advertising is off for the 13–17 category, an unanswered choice and “Prefer not to answer.” FormReady does not place banners on photo/signature editors, Crop or Result/Export, or automatically show interstitial or app-open advertisements.

Eligible adult Free users can optionally choose to watch an ad to earn **one batch credit for one processing operation of up to three images**. The offer is disclosed before the ad; the user chooses whether to load and show it. A rewarded creative can be a video, playable or another supported format; a video is not guaranteed.

A credit is awarded only after the SDK's earned-reward callback, not simply because an ad closes. Loading failures, lack of applicable consent or unavailable ads do not prevent ordinary Free single-image editing, processing, saving or sharing. Previously earned credits can be used without a new ad or internet connection.

Verified Pro users have an ad-free application experience: FormReady does not display new Home banners or initiate rewarded advertisements while that entitlement is active. Advertising/consent code remains in the application, and explicit privacy choices or Google Play purchase checks may still use the internet. The app does not automatically refresh advertising consent while Pro is active. An already-started Free request or full-screen ad cannot always be withdrawn immediately when entitlement changes.

## 5. Earned credit storage and limitations

Credits are stored locally in private app storage separately from Pro purchases. A credit does not grant Pro or unlock saved custom presets. Installing the app does not create a credit.

When a capped batch starts, one credit is reserved. The first durably verified output consumes it, including an output with an explicitly reported KB-limit warning. A partial-success batch uses one credit and keeps its usable outputs. If processing fails entirely or is cancelled before any output is published, the reservation is returned. After a published output, cancellation does not return the used credit; retrying is a new operation. Interrupted reservations are reconciled against retained verified output information on restart, without automatically restarting processing.

Unused credits do not automatically expire in the app. Clearing app data or uninstalling removes the local ledger; no account-based credit restoration or transfer is provided. Device migration, damaged storage, modified software or a process ending before the initial reward storage commit can affect recovery. Live storage failures are reported. The app has no server-side reward verification or developer-operated remote credit ledger, and local accounting is not tamper-proof.

## 6. Google advertising and consent data

Google and eligible advertising partners may collect and process information through advertising/consent services, subject to applicable choices and their policies. Google's Mobile Ads SDK disclosure includes:

- IP address, which may be used to estimate approximate location.
- Advertising identifiers, app-set identifiers and applicable device/account identifiers.
- App and ad interactions, such as launches, taps, ad views and rewarded-ad interactions.
- Diagnostic and performance information, such as loading time, hang rate and energy usage.

Google describes advertising, analytics and fraud prevention as purposes for SDK processing. Consent services also handle privacy-choice signals and technical information needed to present applicable messages. FormReady does not directly request GPS location or use your selected photos, signatures or custom preset names as ad-request content.

The SDK's network processing is not the same as local image processing. Google and advertising partners determine handling and retention under their own policies and applicable agreements. This policy does not promise that all SDK information is immediately deleted, stored only in memory or never used across services. Advertising partners and purposes may be described in the consent form's partner list.

Google states that Mobile Ads SDK user-data transfers use TLS encryption in transit. This does not mean data is end-to-end encrypted against Google, or that files you choose to send through other applications receive the same protections.

## 7. Consent and available privacy controls

For the eligible adult advertising path, FormReady uses Google's User Messaging Platform (UMP) to refresh consent information and display applicable regional messages. Teen, unanswered and undisclosed categories do not trigger automatic advertising consent updates/forms. Existing required privacy choices remain accessible regardless of category or Pro access. Information and choices can depend on your region and the publisher's message configuration.

When available, open **Home → Settings → Privacy choices** to reopen the applicable Google form and change or withdraw choices. This entry is shown when UMP requires it; it may not appear in every region. The Settings **Privacy policy** entry opens this page.

UMP permitting an ad request does not by itself mean you agreed to personalized advertising. Depending on choices and SDK eligibility, limited or non-personalized ads may still be served. Changing advertising choices does not remove your earned credits or prevent ordinary local image work.

You can also manage advertising identifiers and available ad-privacy settings through Android and Google controls. Android options and names vary by version. Deleting or resetting an advertising ID does not necessarily stop every form of SDK processing or delete previously retained third-party data.

## 8. Google Play purchases and Pro access

FormReady Pro is an optional one-time lifetime product offered through Google Play Billing. The checkout shows the applicable price and terms. Pro provides ad-free use, unlimited batch operations subject to processing/storage safety limits, and saved custom presets.

Google Play handles payment details under its policies. FormReady does not directly access your full card number, banking password or payment credentials. The app receives purchase information such as product/package identifiers, purchase tokens, purchase state, signed purchase data and acknowledgement state to validate ownership, acknowledge eligible purchases and restore access.

Purchase verification and ownership checks occur through the existing client/Google Play integration; FormReady does not operate its own purchase-verification server. Google Play may process transaction, service and diagnostic information. Current ownership is rechecked; refunds, revocation, connectivity or verification failures can affect Pro availability. Local single-image tools and previously generated verified results remain usable when a purchase cannot be verified. Clearing FormReady's local data does not erase your Google Play transaction records.

## 9. Retention and deletion controls

| Information | Current local handling |
| --- | --- |
| Selected age category and advertising policy version | Stored locally until changed, app data is cleared or the app is uninstalled; unsupported/missing preference defaults to advertising off. No date of birth or identity document is stored. |
| Preferences and saved presets | Retained until changed/deleted through available controls, or app data is cleared/uninstalled. Custom preset controls require eligible Pro access. |
| Active/recoverable editor source, recipe and result | Retained privately while referenced by an editor/recovery journal; finishing or replacing work releases references. |
| Batch sources, outputs and queue metadata | Retained until queue clear or replacement. Pending processing/export/credit settlement can require completion or restart recovery before clearing. |
| Unreferenced session/processing files and prepared share copies | Eligible for cleanup after 24 hours during applicable startup/share cleanup. This is opportunistic cleanup, not guaranteed deletion at exactly 24 hours. |
| Batch ZIP staging | Unreferenced staging is eligible for cleanup after 24 hours when another archive is prepared; pending export copies can remain until resolved. |
| Earned unused credits | Retained in the local ledger without automatic expiry; removed by app-data clearing/uninstall. |
| Exported/shared files | Retained outside app storage according to your destination/recipient; delete them separately. |
| Google-held ad, consent or purchase information | Controlled by Google and applicable partners; deleting FormReady's private storage does not necessarily delete those records. |

Storage and image-size limits apply. Clear the Batch queue to remove its retained private images when permitted. You can remove presets using available Pro controls, and clear FormReady's private data or uninstall through Android Settings. Clearing data also removes settings, local recovery and credits. Android/device backup or transfer behavior can vary; the app disables Android backup for its private data.

FormReady does not offer an online FormReady account or a developer-operated remote image store to delete. For privacy questions or deletion-related assistance, contact **codenotlie@gmail.com**. We cannot remotely erase your device files or promise deletion of independently controlled Google/recipient records. Use their privacy controls or request channels for those records.

If you email us, you voluntarily provide your email address, message and any attachments. They are handled to address your request through the email service; do not send sensitive images or identifiers unnecessarily. This policy does not specify a fixed deletion deadline for correspondence or third-party records.

## 10. Permissions and third parties

The release app uses internet/network access for advertising, consent and Google Play services, Advertising ID/ad-services permissions supplied by the SDKs, and Billing permission for purchases. It uses scoped image/file selection and restricted sharing. It does not request broad all-files/photo-library, camera, microphone, contact, or GPS-location access for its implemented workflows.

Third-party information:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from apps and sites](https://policies.google.com/technologies/partner-sites)
- [Google Mobile Ads SDK data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [Google Play Terms of Service](https://play.google.com/about/play-terms/)
- [Android advertising ID controls](https://support.google.com/googleplay/android-developer/answer/6048248?hl=en)

Android file providers, recipient apps and browsers you choose have their own practices. Opening a privacy/help website uses your browser; web hosting can process ordinary request information such as IP addresses under its policies.

## 11. Children's privacy

FormReady is intended for teenagers aged 13–17 and adults, as selected by the developer for its Google Play target audience. It is not intended for children under 13. It is a general-purpose image-formatting utility without a child-specific mode. The app offers three self-declared age categories: 13–17, 18 or older, and Prefer not to answer, with an option to skip. This choice is used only for advertising eligibility and is not verified identity. We do not collect date of birth or identity documents. The category and policy version are stored locally; the raw category is not sent as custom advertising data. Standard Google consent/ad-treatment parameters can convey eligibility for the allowed adult path.

Teen, unanswered and undisclosed categories receive no new app-controlled banner or rewarded requests or automatic advertising consent solicitation. Eligible adult requests use a G-rated content cap and real UMP eligibility checks. Ordinary image tools, existing earned credits and Pro access remain usable regardless of the choice. Change it through Settings → Age category; applicable existing Privacy choices remain accessible. We do not claim that self-declaration or these restrictions establish compliance with every regional rule for minors.

If you are a parent or guardian with a privacy concern involving a child's use, contact **codenotlie@gmail.com**. Please do not include unnecessary photos or sensitive personal information in the initial message. We do not claim that the absence of registration prevents third-party SDK data processing.

## 12. Security, changes and contact

FormReady uses Android private app storage, bounded processing and restricted content-URI sharing to help protect local files. It does not guarantee absolute security of a device, operating system, recipient or third-party service. Keep your device updated and protect access to it.

Changes to application functionality or third-party services may require updates to this policy. Revisions will appear at the same public URL with an updated date.

You can manage information stored by FormReady by:

- Removing images or processing results using available application controls.
- Deleting custom presets.
- Clearing FormReady's application data through Android settings.
- Uninstalling FormReady.
- Deleting exported files from their selected storage locations.

Clearing application data or uninstalling FormReady generally removes its locally stored private application data, subject to Android's system storage and backup behavior.

Files previously exported or shared with other applications may need to be deleted separately.

FormReady does not currently provide a developer-operated online user account requiring a separate account-deletion procedure.

## 9. Data Security

We consider privacy and security when designing FormReady.

The application uses Android's application storage protections and supported file-sharing mechanisms to help protect locally stored files.

Image sharing uses Android-supported content access and permissions rather than unrestricted access to private application files.

However, no software or device-storage system can guarantee absolute security.

We recommend keeping your Android device updated and protecting it with an appropriate screen lock.

## 10. Children's Privacy

FormReady is a general-purpose image-formatting utility and is not specifically designed for children.

The application does not require account registration or intentionally request children's personal information.

If you believe a privacy concern involving a child has arisen through the use of FormReady, please contact us using the email address provided below.

## 11. Your Privacy Choices

You control which photos and signatures you select for processing.

You can choose:

- Whether to import an image into FormReady.
- Whether to save or share processed results.
- Which destination receives an exported image.
- Whether to purchase optional Pro functionality.
- Whether to retain or delete locally stored application information.

Premium functionality is optional. Free image-processing features do not require a Pro purchase.

## 12. Changes to This Privacy Policy

We may update this Privacy Policy when application functionality changes, additional services are introduced, or legal and regulatory requirements change.

Updated versions will be published at the same Privacy Policy URL with a revised "Last Updated" date.

We encourage users to review this page periodically.

## 13. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or the handling of information in FormReady, please contact us.

**Application:** FormReady – Photo & Signature Formatter  
**Support and Privacy Email:** codenotlie@gmail.com

We will review privacy-related inquiries and respond as appropriate.

## 14. Advertising and Google AdMob

FormReady offers a Free version supported by advertisements and an optional Pro upgrade.

The Free version uses Google AdMob, provided by Google, to display banner advertisements on the Home screen. FormReady Pro does not display advertisements while the user's Pro entitlement is active.

Google AdMob may collect and process information such as:

- IP address, which may be used to estimate approximate location.
- Device and advertising identifiers, including the Android Advertising ID where available.
- App interactions and advertising engagement information.
- Diagnostic and performance information.

Google may use this information for advertising, analytics, fraud prevention, security, and related purposes.

FormReady uses Google's User Messaging Platform (UMP) to manage applicable advertising consent and privacy choices. Depending on the user's location and applicable laws, the app may display a consent or privacy message. Where required, users can access privacy choices through Settings.

FormReady processes selected photos and signatures locally on the device. The app does not send the content of those selected images to Google AdMob for advertising.

Learn more:

- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses information from apps and sites: https://policies.google.com/technologies/partner-sites

For privacy-related questions, contact: codenotlie@gmail.com
---

**FormReady – Photo & Signature Formatter**

*Simple, secure, and convenient photo and signature formatting.*
