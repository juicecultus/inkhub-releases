<div align="center">

# InkHub

### More possibilities. The same paper-like screen.

An open, Linux-based experience for reading, useful tools and quiet play on your e-reader.

[Explore InkHub](https://einkhub.com) · [See the screens](https://einkhub.com/showcase) · [Release downloads](https://github.com/juicecultus/inkhub-releases/releases) · [Join r/InkHub](https://www.reddit.com/r/InkHub/)

</div>

> **Release status — 1.0.0_RC is being prepared.**
> No installable release or corresponding-source archive has been published here yet.
> The website is live; customer installation and checkout remain closed pending release checks.
> Do not use this repository's **Code → Download ZIP** as an installer.

## FROM BOOT TO YOUR NEXT BOOK

<table>
  <tr>
    <th>InkHub boot splash</th>
    <th>Home · Kobo Libra 2</th>
    <th>Home · reMarkable</th>
  </tr>
  <tr>
    <td valign="top"><img src="assets/inkhub-boot.png" width="260" alt="InkHub boot artwork: a black ink splash and InkHub wordmark on white." /></td>
    <td valign="top"><img src="assets/kobo-home.png" width="260" alt="Kobo Libra 2 Home with a book-cover carousel, reading progress, frontlight and Bluetooth controls." /></td>
    <td valign="top"><img src="assets/remarkable-home.png" width="260" alt="InkHub Home on reMarkable, showing Pride and Prejudice in the carousel and reading information below." /></td>
  </tr>
</table>

The splash is the actual boot artwork exported to PNG, not a photograph of a boot.
Home images are device captures from development builds; they are not screenshots
of the forthcoming RC. Details may change before release. Example books are not
an included book bundle. [Explore Reader, tools, games and Terminal →](https://einkhub.com/showcase)

## YOUR E-READER, WITH MORE FREEDOM

InkHub brings a custom Linux environment to hardware you already own: choose your
reader, bring books from different sources, transfer files without a store account,
and use everyday tools on a quiet e-ink screen. On Kobo Libra 2 it replaces the OS;
on reMarkable it lives alongside the original system, so the native notebook and
drawing experience remains a restart away.

**Listen on Kobo with Wi-Fi off.** InkHub controls Bluetooth independently of Wi-Fi,
so local audio in Listen can play through Bluetooth headphones or a speaker without
keeping Wi-Fi enabled. This was exercised on our Libra 2 bench with speaker playback.
By contrast, [Kobo's stock-system guidance](https://help.kobo.com/hc/en-us/articles/4406284800023-Troubleshoot-Bluetooth-pairing-on-your-Kobo-eReader)
says enabling Bluetooth also enables Wi-Fi. This is a Kobo benefit, not a claim that
the reMarkables have Bluetooth hardware, and not a battery-life guarantee.

## WHAT YOU GET

- **A home for your books.** A cover carousel, library, search and reading information.
- **Reader, made for e-ink.** EPUB reading with typography controls, contents, highlights,
  annotations and export, dictionary lookup, Wikipedia and in-book search.
- **KOReader alongside Reader.** Another reading option for PDFs and other supported formats.
- **Tools without the noise.** Notes, calculator, Pomodoro, LocalSend file transfers and Terminal.
- **A little downtime.** Chess, Sudoku, Blocks, Solitaire and other games.
- **Device-aware controls.** Frontlight, natural light and Bluetooth audio through Listen on
  Kobo Libra 2; orientation and physical-button support where the hardware provides them.

Features depend on the device and release. A general-purpose web browser is work in
progress, not a promised feature of this RC.

## BRING YOUR LIBRARY. CHOOSE HOW IT GETS HERE.

| What you want to do | InkHub's route |
| --- | --- |
| **Find your next book** | Browse/search book catalogues from **Get books** in My Library. Built-in entries include **Standard Ebooks**, **Project Gutenberg**, **textos.info** and **Gallica**. |
| **Use your own catalogue** | Add a compatible **OPDS** catalogue, including a Calibre Content Server. Search and download supported books directly on the device. |
| **Manage books from Calibre** | **Calibre wireless** connects to the desktop app over the local network for book transfers and library information, with read-status integration. This is separate from browsing Calibre's OPDS catalogue. |
| **Send a file from a phone or computer** | **LocalSend** transfers files between compatible devices on the same local network, without uploading them to a cloud service. |
| **Drag and drop from a browser** | Enable **Connect over Wi-Fi**, open the address shown on the device, and manage books from a computer's browser. |
| **Use a network drive** | Connect a compatible file manager through **WebDAV** to the enabled device share. |
| **Use a cable** | Kobo offers USB card access; reMarkable uses its USB-network file-sharing route rather than exposing its internal storage as a USB disk. |
| **Keep a cloud book folder available** | **Cloud folder**, powered by rclone, downloads from a configured provider such as Dropbox, Google Drive, OneDrive or Nextcloud/WebDAV. Account setup/import is required; automatic sync is optional. |
| **Take your notes with you** | Export Reader highlights and annotations, transfer the exported files, or explicitly upload exported notes through Cloud folder. |
| **Continue reading elsewhere** | Configure **reading-progress sync** with a compatible KOReader sync service and matching book files. This is separate from Calibre book transfer and cloud-folder sync. |

Online catalogues need internet access; local transfers need only the relevant local
connection. Catalogue availability, authentication and download rights are controlled
by each provider. Standard Ebooks uses its public search feed; some provider feeds
require membership. InkHub does not bypass DRM or include paid books.

Cloud-folder sync mirrors the selected remote folder: removing a remote book can remove
its downloaded copy on the next sync. Reading-progress compatibility depends on the
book and clients; it is not universal cross-app annotation sync.

## CHOOSE YOUR DEVICE

| Device | How InkHub runs | Returning to the original experience |
| --- | --- | --- |
| **Kobo Libra 2** | Replaces the installed OS; the guided route uses desktop Chrome. | **Return to Kobo** in Settings starts the stock-restoration process. This is restoration, not dual boot. Keep the installation backup safe. |
| **reMarkable 1** | Dual boot alongside the stock system; the guided route uses a local helper. | Restart into reMarkable for its native notebook and drawing experience. |
| **reMarkable 2** | Dual boot alongside the stock system; the guided route uses a local helper. | Restart into reMarkable for its native notebook and drawing experience. |
| **reMarkable Paper Pure** | Dual boot alongside the stock system; the guided route uses a local helper. | Restart into reMarkable for its native notebook and drawing experience. |

These are the devices in the release programme, not a claim that every RC installation
check has passed. Always check the release notes for exact model and stock-firmware
requirements. Do not install an image intended for a different model.

## INSTALLATION & UPDATES

The guided service lives at **[einkhub.com](https://einkhub.com)**. When the release opens,
start there for the model-specific preparation, trial and installation steps.

Back up important data first. For Kobo, keep a copy of the card's stock backup on your
computer too: a backup on the same card cannot protect against that card failing.
Do not disconnect power or USB while an installation is writing to the device.

The one-off hosted installation purchase includes **future seamless OTA software
installations for that device**. It pays for the guided service, not exclusive access
to open-source software. Public releases and the rights granted by their licences
remain available independently of a purchase.

## DOWNLOADS YOU CAN VERIFY

Each published release will identify its device, version, installation requirements,
known limitations and verification instructions. It will include the applicable
installation/OTA artifacts, signed manifests, checksums and matching source materials.

GitHub Releases is the public distribution home. The browser installer uses a
Cloudflare R2 mirror where browser-access headers are needed. Large download bodies
do not pass through the storefront or its customer database.

Use the **exact release assets** linked by the installer or release notes. A checksum
detects changed bytes; the signed manifest is what authenticates the release. Do not
substitute files from another version or treat an automatically generated source ZIP
as a firmware package.

## OPEN SOFTWARE, COMPLETE SOURCES

This is a **release repository**, not the private development repository or its history.
For each distributed release, the explicitly labelled **corresponding-source archive**
will contain the covered source, patches, build materials and notices needed under
the applicable licences. Follow that archive's build instructions.

**GitHub's automatic “Source code (zip)” and “Source code (tar.gz)” links are not those
archives.** They contain this release repository's files, not the complete device OS.

Component licences govern the software, including applicable rights to build, modify
and redistribute it. Independently authored hosted installation and customer-service
infrastructure remains proprietary; that does not withhold required corresponding
source or override existing open-source permissions.

## COMMUNITY

Share questions, ideas and bug reports at **[r/InkHub](https://www.reddit.com/r/InkHub/)**.
Help is through the subreddit or Reddit DMs, without a guaranteed response time or SLA.

For a useful bug report, include your device model, InkHub version, the steps to
reproduce it and a screenshot where possible. Remove passwords, serial numbers,
personal documents and other private information before posting logs or pictures.

---

**© 2026 AllMumsTalk Limited t/a InkHub**

InkHub and einkhub.com identify our project and service. InkHub name, logo and original
brand artwork belong to AllMumsTalk Limited. This notice does not claim registered
trademark status or revoke existing licence permissions. Book artwork and third-party
names remain subject to their respective rights. InkHub is an independent project,
not affiliated with or endorsed by Kobo or reMarkable.
