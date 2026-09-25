<div align="center">

# InkHub

### More possibilities. The same paper-like screen.

An open, Linux-based experience for reading, useful tools and quiet play on your e-reader.

[Explore InkHub](https://inkhub.dev) · [See the screens](https://inkhub.dev/showcase) · [Release downloads](https://github.com/juicecultus/inkhub-releases/releases) · [Join r/InkHub](https://www.reddit.com/r/InkHub/)

</div>

**[InkHub 1.0.1 is available](https://github.com/juicecultus/inkhub-releases/releases/tag/v1.0.1).**
Install through [inkhub.dev](https://inkhub.dev/install), or update an existing
installation from Settings. This release uses reMarkable runtime build
**2026092502** and Kobo Libra 2 build **1195**.

New in 1.0.1: clearer sixteen-tone covers, separately editable Notes titles,
a shared four-row keyboard, less redraw work across native apps, quieter
background book processing and a Kobo battery-gauge correction. Paper Pure
and RM2 retain normal content refreshes for clear text and changing digits.
See the [release notes](https://github.com/juicecultus/inkhub-releases/releases/tag/v1.0.1)
for details and verification limits. Physical Bluetooth keyboards and Type Folio
have not been qualified.

All four devices passed their final update and reboot checks. Each reMarkable's
17 runtime files matched its signed package; Kobo's 17 application binaries and
15 app images matched the release. Kobo Notes required its signed app update
after reboot because the old image had been in use. The release's
`release-validation-2026092502.json` records the checks and their limits.

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

InkHub boot artwork and Home screens from development builds.
[Explore Reader, tools, games and Terminal →](https://inkhub.dev/showcase)

## YOUR E-READER, WITH MORE FREEDOM

InkHub brings a custom Linux environment to hardware you already own: choose your
reader, bring books from different sources, transfer files without a store account,
and use everyday tools on a quiet e-ink screen. On Kobo Libra 2 it replaces the OS;
on reMarkable it lives alongside the original system, so the native notebook and
drawing experience remains a restart away.

On Kobo Libra 2, Listen plays local audio through Bluetooth headphones or speakers
with Wi-Fi switched off. InkHub controls the radios independently; the
[stock system enables Wi-Fi with Bluetooth](https://help.kobo.com/hc/en-us/articles/4406284800023-Troubleshoot-Bluetooth-pairing-on-your-Kobo-eReader).

## WHAT YOU GET

- A home for your books. A cover carousel, library, search and reading information.
- Reader, made for e-ink. EPUB reading with typography controls, contents, highlights,
  annotations and export, dictionary lookup, Wikipedia and in-book search.
- KOReader alongside Reader. Another reading option for PDFs and other supported formats.
- Keep your place. InkHub Reader and the installed KOReader share EPUB reading
  progress locally, including offline. Use the same EPUB and close the book before
  switching apps. Optional KOReader-compatible account sync carries progress between devices.
- Tools without the noise. Notes, calculator, Pomodoro, LocalSend file transfers and Terminal.
- A little downtime. Chess, Sudoku, Blocks, Solitaire and other games.
- Device-aware controls. Frontlight, natural light and Bluetooth audio through Listen on
  Kobo Libra 2; orientation and physical-button support where the hardware provides them.

Features follow each device's hardware. A web browser is planned for a future release.

## READ YOUR WAY

- **Third-party page turners on Kobo Libra 2.** Pair a compatible Bluetooth HID
  remote in Settings. Page Up/Down, arrow, volume, Space and Enter keys are mapped
  to page turns, and remotes can connect while Reader is open. Compatibility
  depends on the remote's pairing method and key output; individual models are
  not yet listed as tested. The reMarkable builds do not provide Bluetooth pairing.
- **Bluetooth audio with Wi-Fi off.** Listen plays local audiobooks and podcasts
  through compatible headphones or speakers on Kobo Libra 2.
- **Reading that fits your device.** Automatic reading orientation on Kobo Libra 2
  and Paper Pure, plus physical page controls on Kobo Libra 2 and reMarkable 1.
- **Light that follows your evening.** Kobo Libra 2 has separate brightness and
  warmth controls, with automatic Natural light reaching full warmth at bedtime.
- **A reader built for responsiveness.** Optimised rendering and cached layouts
  speed up page turns and returning to books. Timing depends on the device, book
  and screen-refresh settings.

## BRING YOUR LIBRARY. CHOOSE HOW IT GETS HERE.

| What you want to do | InkHub's route |
| --- | --- |
| Find your next book | Browse/search book catalogues from Get books in My Library. Built-in entries include Standard Ebooks, Project Gutenberg, textos.info and Gallica. |
| Use your own catalogue | Add a compatible OPDS catalogue, including a Calibre Content Server. Search and download supported books directly on the device. |
| Manage books from Calibre | Calibre wireless connects to the desktop app over the local network for book transfers and library information, with read-status integration. |
| Send a file from a phone or computer | LocalSend transfers files between compatible devices on the same local network, without uploading them to a cloud service. |
| Drag and drop from a browser | Enable Connect over Wi-Fi, open the address shown on the device, and manage books from a computer's browser. |
| Use a network drive | Connect a compatible file manager through WebDAV to the enabled device share. |
| Use a cable | Kobo offers USB card access; reMarkable uses its USB-network file-sharing route through its local file-sharing service. |
| Keep a cloud book folder available | Cloud folder, powered by rclone, downloads from a configured provider such as Dropbox, Google Drive, OneDrive or Nextcloud/WebDAV. Account setup/import is required; automatic sync is optional. |
| Take your notes with you | Export Reader highlights and annotations, transfer the exported files, or explicitly upload exported notes through Cloud folder. |
| Continue reading elsewhere | Configure reading-progress sync with a compatible KOReader sync service and matching book files. |

Online catalogues need internet access; local transfers need only the relevant local
connection. Catalogue availability, authentication and download rights are controlled
by each provider. Standard Ebooks uses its public search feed; some provider feeds
require membership. Bring your own DRM-free books.

Cloud-folder sync mirrors the selected remote folder: removing a remote book can remove
its downloaded copy on the next sync. Reading-progress compatibility depends on the book and clients.

## CHOOSE YOUR DEVICE

| Device | How InkHub runs | Returning to the original experience |
| --- | --- | --- |
| Kobo Libra 2 | Replaces the installed OS; the guided route uses desktop Chrome. | Return to Kobo in Settings starts the stock-restoration process. Keep the installation backup safe. |
| reMarkable 1 | Dual boot alongside the stock system; the guided route uses a local helper. | Restart into reMarkable for its native notebook and drawing experience. |
| reMarkable 2 | Dual boot alongside the stock system; the guided route uses a local helper. | Restart into reMarkable for its native notebook and drawing experience. |
| reMarkable Paper Pure | Dual boot alongside the stock system; the guided route uses a local helper. | Restart into reMarkable for its native notebook and drawing experience. |

Check the release notes for your exact model and stock-firmware requirements.

## INSTALLATION & UPDATES

### Choose your computer

| Computer | reMarkable installer | Status |
| --- | --- | --- |
| Apple silicon Mac, macOS 13 or later | Model-specific ZIP containing InkHub Installer.app | Final packages are signed, Apple-notarized and stapled; Gatekeeper assessment passed. Intel Mac is not supported. |
| Windows 11 x64 | Portable ZIP containing InkHub Installer.exe | Extract the whole ZIP and keep its bundled files together. Native build, automated tests and Paper Pure USB trial passed. Unsigned; revised full browser completion remains unverified. |
| Linux | Model-specific archive and local helper | Python 3.11+, OpenSSH and minisign required. Supported for all reMarkable models. Physical reference test: Paper Pure installation and reboot on Arch Linux with Chromium. |

Download the installer for your exact model through its page on inkhub.dev.
Follow the [Mac, Windows and Linux installation guide](https://inkhub.dev/help/installing)
for prerequisites, USB setup, pairing, installation and recovery.
The reMarkable 1.0.1 kits target stock firmware **3.28.0.172**. Follow the local
installer's pairing, trial and installation steps. InkHub is the default after
installation; **Restart into reMarkable** selects the original software for one
boot. Books and settings remain in place during supported runtime updates.

Kobo Libra 2 uses the **desktop Chrome browser installation flow**, rather than
the reMarkable desktop helper. Check the model-specific guide for USB setup and
recovery requirements on your computer.

### Update an existing installation

- **reMarkable:** copy the matching signed `.inkhub` runtime package into
  `Books/Updates`, or download it through **Settings → Software update** over
  Wi-Fi. Check the package, then use **Install and restart**. These runtime
  updates retain the installed board/startup files and stock firmware.
- **Kobo Libra 2:** use its separate signed system update. reMarkable runtime
  packages are not compatible with Kobo.

The original 1.0.0 release checks passed normal USB installation on RM1, copied-package
installation with Wi-Fi off on RM2, and production HTTPS OTA over Wi-Fi on
Paper Pure. All sixteen runtime files were verified before and after a full
reboot on each reMarkable.

On 24 September 2026, the published Paper Pure Linux package also passed fresh
USB installation from **Arch Linux x86_64**, kernel **7.2.6**, using **Chromium 153**,
Python **3.14.7**, OpenSSH **10.5** and minisign **0.12**. The owner completed the
website flow in Chromium on Arch; the installed build **2026092403**, active
services and all **16 runtime file hashes** were checked before and after reboot.
Preserved InkHub books and settings were restored and checksummed. A separate
trial timeout returned the device to stock as intended. This verifies that tested
Paper Pure setup. Linux support for the other devices is a product support
decision; separate physical tests on them or other distributions are not claimed.
On Windows 11 Pro x64, the helper connected and the Paper Pure trial ran through
Chrome. After the original paired browser tab was closed, permanent installation
was completed through the same USB decision protocol and verified after reboot;
37 user files were restored and checked. Helper revision **2026092405** fixes
native Windows startup and supports recovering an authenticated browser session.
All three model ZIPs pass native verification. The revised complete Windows
browser flow and physical RM1/RM2 Windows installations remain unverified.


The guided service is open at [inkhub.dev](https://inkhub.dev/install).
Start there for the model-specific preparation, trial and installation steps.

Back up important data first. For Kobo, keep a copy of the card's stock backup on your
computer too: a backup on the same card cannot protect against that card failing.
Do not disconnect power or USB while an installation is writing to the device.

The one-off hosted installation purchase includes future OTA software updates
for that device. The installation service is £6.99, including applicable tax,
through 31 October 2026, then £9.99. The first 100 installations are free at
launch, limited to one free claim per verified account across all models. Public software releases remain freely available
under their component licences.

## DOWNLOADS YOU CAN VERIFY

Each published release identifies its device, version, installation requirements,
known limitations and verification instructions. It includes the applicable
installation/OTA artifacts, signed manifests, checksums and matching source materials.

Downloads are hosted on GitHub Releases, with a Cloudflare R2 mirror used by
inkhub.dev. The 1.0.1 desktop installers include **2026092502** in their filenames
and pair with **https://inkhub.dev**. Use the release's **SHA256SUMS-2026092502**
to verify the downloads. The stable Wi-Fi OTA discovery URLs are unchanged.
Existing accounts and installation access are retained. Contact **hello@inkhub.dev**.

Use the files linked in your release's instructions. Signed manifests authenticate
the release; checksums verify the downloaded bytes.

## OPEN SOFTWARE, COMPLETE SOURCES

For device source, choose the explicitly labelled corresponding-source archive attached
to each release. It includes covered sources, patches, build instructions and notices.
GitHub's automatic source ZIP contains this repository's documentation and images,
not the device software source.

For 1.0.1, use **inkhub-1.0.1-source-2132019e.tar.gz** together with
**kernel-working-source.tar.gz** and the dependency archives linked in
**SOURCE-README-2026092502.md**. The unchanged dependency archives remain
available at their original 1.0.0 URLs; **unchanged-source-inputs.json** records
their sizes and checksums. The source README explains the application build,
corrected display helpers and packaging provenance. Host installer sources are
included in the project archive.

Release validation distinguishes signed-artifact and device checks from the
broader legacy test suite, which is not wholly passing. It does not claim a new
clean rebuild of every dependency. Device-owned display waveforms and stock
recovery data are not redistributed. Older release sources remain available
alongside their original releases.

Component licences provide the applicable rights to build, modify and redistribute
the software. The independent hosted installation and customer-service infrastructure
is proprietary to AllMumsTalk Limited.

## CREDITS & THIRD-PARTY NOTICES

InkHub builds on the work of the following projects and their contributors.
Their software, fonts and data retain their own copyrights and licences.

- **Linux and e-reader hardware support:** [Linux](https://www.kernel.org/),
  [Andreas Kemnade's i.MX e-reader kernel and EPDC work](https://github.com/akemnade/linux),
  Freescale/NXP's original EPDC driver, and
  [postmarketOS](https://postmarketos.org/) for its e-reader integration and packaging.
  [FBInk by NiLuJe and contributors](https://github.com/NiLuJe/FBInk) provides framebuffer drawing tools.
- **reMarkable 2 display support:** [Joel Jensen's swtcon](https://github.com/yobert/swtcon)
  and [timower's rM2-stuff software TCON](https://github.com/timower/rM2-stuff).
  InkHub modifies the vendored swtcon implementation. Its
  [provenance and modification notice](notices/swtcon-NOTICE.txt) records InkHub's
  GPL-3.0-or-later distribution treatment; the upstream
  [MIT copyright and permission notice](notices/swtcon-LICENSE-MIT.txt) is also preserved.
- **System and interface:** [Buildroot](https://buildroot.org/),
  [musl](https://musl.libc.org/), [BusyBox](https://busybox.net/),
  [Slint](https://slint.dev/), [BlueZ](https://www.bluez.org/),
  [D-Bus](https://www.freedesktop.org/wiki/Software/dbus/), GLib, Avahi,
  wpa_supplicant, and the Rust ecosystem.
- **Reading and applications:** [KOReader](https://github.com/koreader/koreader),
  [crengine-ng](https://gitlab.com/coolreader-ng/crengine-ng),
  [GNU Chess](https://www.gnu.org/software/chess/), [FFmpeg](https://ffmpeg.org/),
  and [fastfetch](https://github.com/fastfetch-cli/fastfetch).
  Dictionary data: WordNet 3.1, Copyright 2011 by Princeton University.
  All rights reserved. Its required notices and disclaimer are retained in the
  [release notice](notices/inkhub-1.0.0-NOTICE.txt) and alongside the installed database.
- **File transfer and installation:** [LocalSend](https://github.com/localsend/localsend)
  (protocol core and adapted identity module, copyright 2022–2026 Tien Do Nam,
  Apache-2.0), [rclone](https://rclone.org/), [dufs](https://github.com/sigoden/dufs),
  [curl](https://curl.se/), [minisign](https://jedisct1.github.io/minisign/),
  libsodium, OpenSSH, CPython and Astral's python-build-standalone.
  Bundled host runtimes retain their own third-party notices.
- **Typography:** the Noto project, Droid Sans Mono, and the creators of
  Gelasio (Sorkin Type), Literata, Cabin (Impallari), Zilla Slab (Mozilla),
  Source Serif (Adobe) and Crimson Pro. Their OFL or Apache notices accompany
  the fonts. FreeType, HarfBuzz, FriBidi, libunibreak and utf8proc support text rendering.
- **Weather and catalogues:** weather data from [Open-Meteo](https://open-meteo.com/)
  under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), selected and
  formatted for InkHub's display. The MIT-licensed
  [joan-dashboard](https://github.com/juicecultus/joan-dashboard) informed the weather
  design, WMO mapping and forecast selection.
  Book catalogue integrations use [Project Gutenberg](https://www.gutenberg.org/),
  [Standard Ebooks](https://standardebooks.org/), [textos.info](https://www.textos.info/)
  and [Gallica](https://gallica.bnf.fr/). Catalogue access does not grant rights to
  redistribute every book or its artwork; each provider's terms apply.

This acknowledgement is an overview, not a replacement for the full licence texts.
The [1.0.1 project notice](notices/inkhub-1.0.1-NOTICE.txt) is reproduced
from the corresponding source archive; the original 1.0.0 notice remains available.
The [release assets](https://github.com/juicecultus/inkhub-releases/releases/tag/v1.0.1)
include the corresponding project and dependency sources, Buildroot legal-info,
font notices and host-runtime notices. Consult those materials for the exact
versions, copyright notices, local changes and licence terms of each component.

InkHub is independent of these projects and of Rakuten Kobo and reMarkable.
Credit does not imply their endorsement. Device-owned proprietary waveforms,
stock fonts and firmware retain their owners' rights; acknowledging them does
not grant permission to redistribute them.

## COMMUNITY

For support, bug reports and feature requests, [open a GitHub issue](https://github.com/juicecultus/inkhub-releases/issues/new).
You can also join [r/InkHub](https://www.reddit.com/r/InkHub/) for community discussion
and help through the subreddit or Reddit DMs.

For a useful bug report, include your device model, InkHub version, the steps to
reproduce it and a screenshot where possible. Remove passwords, serial numbers,
personal documents and other private information before posting logs or pictures.

---

© 2026 AllMumsTalk Limited t/a InkHub

InkHub name, logo and original brand artwork belong to AllMumsTalk Limited.
Book artwork and third-party names remain subject to their respective rights.
InkHub is an independent project.
