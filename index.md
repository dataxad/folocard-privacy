# Folocard Privacy Policy

**Effective date:** September 10, 2026

**App versions:** The Android behavior described below is for Folocard 0.11.
If you use an earlier version, also read **Earlier Versions: Optional Network
Features** below. Features on other platforms may differ.

**Developer:** DataXad

**Privacy contact:** [feedback@folocard.com](mailto:feedback@folocard.com)

Folocard is a privacy-first, first-touch mini CRM. Its core business-card
capture, text recognition, contact storage, review, and drafting workflows are
designed to run on hardware you control. This policy explains what stays local,
which optional actions can send data elsewhere, and the choices available to
you.

## Data Folocard Stores Locally

Depending on the features you use, Folocard can store the following inside the
app's private storage on your device:

- business-card images and recognized text;
- names, email addresses, phone numbers, addresses, organizations, job titles,
  websites, social links, and other card fields;
- notes, meeting context, review state, follow-up state, conversations, and
  drafts;
- contact phone details and calendar-event context you select and save;
- text, vCards, images, documents, audio files, and other supported files you
  deliberately import or share into Folocard, including locally prepared text
  or voice transcripts;
- locally generated enrichment, public-web source content, source/provenance
  records, and previously stored profile or company images;
- app settings, local model files, and model configuration; and
- local quality, timing, trace, and diagnostic records used to operate and
  troubleshoot the app.

Folocard does not include a DataXad analytics, advertising, cloud-sync, or
automatic crash-reporting service in the 0.11 Android update. DataXad does
not automatically receive the content listed above.

The Android operating-system sandbox and any app-lock feature you enable help
protect local data. Folocard does not claim that every local database or file is
separately encrypted.

## When Data Can Leave Your Device

The 0.11 Android update keeps card capture, recognition, AI inference, dossier
storage, and drafting on the device. Public-web research can run in the
background under your research, source, and assistant settings; it does not
require a paid network entitlement. Data can leave your device in these
situations:

### Model Downloads

When you browse or download an AI model, your device connects directly to
Hugging Face. Hugging Face receives ordinary network information such as your
IP address and the requested model or file. Card and draft content is not
needed for model downloads. See the [Hugging Face Privacy
Policy](https://huggingface.co/privacy).

### Optional Public-Web Research

When public-web research is enabled and an internet connection is available,
Folocard can send search terms derived from the contact and saved context,
requested URLs, and ordinary connection information to search providers and
public websites. Terms may include a person's name, organization, or other
context used in a research question. Those destinations receive the requests;
AI inference and the saved dossier remain on your device. Research settings
control this activity, and enabled research can remain pending while offline.
Folocard can use Brave Search; see the [Brave Search Privacy
Notice](https://safe.search.brave.com/help/privacy-policy). Websites you visit
or query apply their own policies.

### Local AI Processing

Remote model-server connections, remote AI inference, third-party enrichment
and data-broker services, and automatic third-party profile/logo lookups are
disabled in Folocard 0.11, including developer builds and all editions. Public
search and page retrieval are separate from inference. Folocard does not upload
whole private dossiers for remote inference or training. Separately, you can
choose the report and sharing actions described below.

### Earlier Versions: Optional Network Features

If you use an earlier Folocard version that offers these optional network
features, the following disclosures apply when you enable and use them.
Remote model connections and third-party profile/logo lookups are disabled in
0.11; its public search and page retrieval are described separately above.

#### Optional Web Research and Asset Lookups

When enabled and initiated, web search, page retrieval, company-site lookups,
logo retrieval, or profile-image lookup sends the search terms, requested URL,
email-derived hash, or company domain needed to perform that action to the
selected website or search provider. Folocard can use Brave Search; see the
[Brave Search Privacy Notice](https://safe.search.brave.com/help/privacy-policy).
Websites you visit or query apply their own policies.

#### User-Configured Local or Remote Model Servers

When that capability is enabled, you can choose to connect Folocard to a model
server you control or select, including an OpenAI-compatible server, LM Studio,
or Ollama. Prompts, card content, conversation content, and attached images
needed for the request can be sent to that endpoint. DataXad does not operate
or control a server you configure and does not receive those requests.

Some private-network servers use unencrypted HTTP. Use HTTPS or another secure
transport when the network or content is sensitive. The server operator's
retention and privacy terms apply.

### Email, Contacts, Calendar, Messaging, Files, and Sharing

Folocard prepares drafts; it does not silently send email. When you choose to
open a draft in an email or messaging app, open a prefilled contact or calendar
entry, share a vCard, export CSV data, or share another file, the selected app
receives that content for your review. The receiving contacts, calendar, email,
messaging, storage, or sharing app may save, send, or sync it under its own
account settings and policies. Opening a handoff does not prove it was saved
or delivered.

### Diagnostic Feedback

Diagnostic bundles are created locally. Folocard sends a bundle only when you
explicitly use the operating system's share flow and select a destination. The
bundle can contain local logs and troubleshooting information, so review the
destination before sharing it. If you send a bundle to DataXad, it is used to
investigate the issue and retained only as long as reasonably necessary for
support, security, and legal obligations.

### AI Response Reports

When you choose **Report AI response**, Folocard prepares a bounded plain-text
report containing the selected response, a message identifier, safety context,
and available app version, build, and package details. Nothing is sent until you
confirm **Send report**. After confirmation, Folocard sends the report directly
to DataXad through FormSubmit, DataXad's report-delivery service provider. The
HTTPS transfer is encrypted in transit. FormSubmit and the mail provider can
also process ordinary network and delivery information, such as an IP address,
as needed to deliver the report.

DataXad uses these optional reports to investigate harmful or inappropriate
output and improve safeguards. DataXad retains a received report for up to 30
days and then deletes it, unless a longer period is required for security,
abuse prevention, or legal obligations. To ask whether DataXad holds a report
or request its earlier deletion, email
[feedback@folocard.com](mailto:feedback@folocard.com).

## Permissions

Folocard can request access to the camera for card capture, the microphone for
optional voice features, notifications for user-requested reminders or ongoing
operations, and files or photos when you choose to import, save, or share
content. Permission availability depends on your Android version.

For contact context, you choose a phone entry in the system contact picker.
Folocard reads the selected entry's name and phone number under the picker's
access grant; it does not request broad address-book permission or scan the
whole address book. Saving a prepared contact opens the contacts app for your
review and does not silently write to it.

For calendar context, you first enable Calendar context and grant Android's
calendar-read permission. Folocard lists visible calendars, then reads event
titles, times, and locations within a bounded date window from the calendar
you choose. You choose which event context to save locally. These controls do
not enable automatic background reading or account sync. You can remove saved
context or change source settings; permission can also be revoked in Android
settings. Preparing a new calendar entry uses a separate user-directed handoff.

Imported files and shared text are retained locally for review. Local audio
transcription uses a downloaded Whisper model when available and you request
preparation; unsupported formats or unavailable models can remain pending.
Folocard does not send these recordings to a remote transcription service.

## Retention and Deletion

Local data remains on your device until you delete it with available app
controls, clear Folocard's app data in Android settings, or uninstall the app.
Files you export or share are controlled by the destination you selected and
must be deleted there separately. Websites, search providers,
email apps, and other services you choose may retain data under their own
policies.

Folocard currently does not require a DataXad account for the local Android
experience and does not provide DataXad cloud storage in this release. If you
used a legacy Folocard account, cloud backup, or paid service and want to ask
about historical data or entitlements, contact
[feedback@folocard.com](mailto:feedback@folocard.com).

## Purchases

The existing Google Play listing may retain legacy subscription and one-time
product records. The current Folocard app does not initiate or process new
purchases and does not collect purchase history or entitlement data. Drafts no
longer require a paid "Remove Signature" entitlement; the branded footer is
absent for every user. For help with a historical purchase or subscription,
contact [feedback@folocard.com](mailto:feedback@folocard.com).

## Children

Folocard is a business productivity tool and is not directed to children under 13. Do not use Folocard to collect children's personal information without the
authority and consent required by applicable law.

## International Use and Your Rights

Privacy rights vary by location. To ask about access, correction, deletion, or
another privacy right involving data held by DataXad, email
[feedback@folocard.com](mailto:feedback@folocard.com). Most Folocard data is
held only on your device or by a service you selected, so DataXad may not
possess a copy.

## Changes to This Policy

We may update this policy when Folocard's features, providers, or legal
requirements change. The effective date above identifies the current version.
Material changes will be reflected in the published policy and, when
appropriate, in the app or store listing.

## Contact

Questions or requests:
[feedback@folocard.com](mailto:feedback@folocard.com)
