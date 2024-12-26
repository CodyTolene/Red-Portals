<div align="center">
  <img align="center" src=".github/images/logo/red-portal.png" />
  <!-- <img align="center" src=".github/images/logo/red-portal-simplistic.png" /> -->
  <h1 align="center">Red Portals</h1>
  <p align="center">
   A repository for educational and ethical exploration of 'Evil Portals,' demonstrating how rogue captive portals mimic legitimate login systems. Designed for security researchers, penetration testers, and ethical hackers to understand and mitigate network vulnerabilities.
  </p>
</div>

## Index <a name="index"></a>

- [Previews](#previews)
- [What Are "Evil Portals"?](#what-are-evil-portals)
- [Purpose](#purpose)
- [Getting Started](#getting-started)
- [Development](#development)
- [Disclaimer, Legal Notice, & Responsible Use](#disclaimer-legal-notice-responsible-use)
- [Licensing](#licensing)
- [Wrapping Up](#wrapping-up)

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Previews <a name="previews"></a>

You may click on any preview below to view it live. All templates are designed
to:

1. Be as simple and accurate as possible.
2. Work on both mobile and desktop devices.
3. Send a query param payload on form submit as
   `/login?username=example&password=example`.
4. Be developed as HTML/SCSS but compiled to a single HTML file with inline CSS.
5. Be compressed. Take note some hardware only supports displaying up to 20 KB
   templates at a time.
6. Not use any JavaScript, vanilla HTML and CSS only. You may optionally add JS
   code yourself. See the [Development](#development) section for more
   information.

> ![Info][img-info] All previews are hosted on [raw.githack.com][url-githack], a
> great CDN for source code!

| Portal            | Preview                                                              | Size     | Inspired By                                                                          |
| ----------------- | -------------------------------------------------------------------- | -------- | ------------------------------------------------------------------------------------ |
| Alaska Airlines   | [portals/alaska-airlines/index.html][url-portal-alaska-airlines]     | 2.78 KB  | [@roshanravan][url-roshanravan] - [link][url-roshanravan-alaska-airlines]            |
| Amazon            | [portals/amazon/index.html][url-portal-amazon]                       | 3.99 KB  | [@roshanravan][url-roshanravan] - [link][url-roshanravan-amazon]                     |
| Apple             | [portals/apple/index.html][url-portal-apple]                         | 5.33 KB  | [@jules0835][url-jules0835] - [link][url-jules0835-apple]                            |
| AT&T              | [portals/att/index.html][url-portal-att]                             | 3.88 KB  | [@roshanravan][url-roshanravan] - [link][url-roshanravan-att]                        |
| Delta Airlines    | [portals/delta-airlines/index.html][url-portal-delta-airlines]       | 2.58 KB  | [@bigbrodude6119][url-bigbrodude6119] - [link][url-bigbrodude6119-delta-airlines]    |
| Discord           | [portals/discord/index.html][url-portal-discord]                     | 6.55 KB  | [@JMcrafter26][url-jmcrafter26] - [link][url-jmcrafter26-discord]                    |
| Facebook          | [portals/facebook/index.html][url-portal-facebook]                   | 2.69 KB  | [@roshanravan][url-roshanravan] - [link][url-roshanravan-facebook]                   |
| Google            | [portals/google/index.html][url-portal-google]                       | 5.35 KB  | [@breaching][url-breaching] - [link][url-breaching-google]                           |
| Instagram         | [portals/instagram/index.html][url-portal-instagram]                 | 4.05 KB  | [@JMcrafter26][url-jmcrafter26] - [link][url-jmcrafter26-instagram]                  |
| Microsoft         | [portals/microsoft/index.html][url-portal-microsoft]                 | 4.75 KB  | [@Awlexegrecki][url-awlexegrecki] - [link][url-awlexegrecki-microsoft]               |
| Southwest Airline | [portals/southwest-airline/index.html][url-portal-southwest-airline] | 3.77 KB  | [@bigbrodude6119][url-bigbrodude6119] - [link][url-bigbrodude6119-southwest-airline] |
| Spectrum          | [portals/spectrum/index.html][url-portal-spectrum]                   | 3.21 KB  | [@roshanravan][url-roshanravan] - [link][url-roshanravan-spectrum]                   |
| Spirit Airlines   | [portals/spirit-airlines/index.html][url-portal-spirit-airlines]     | 2.60 KB  | [@roshanravan][url-roshanravan] - [link][url-roshanravan-spirit-airlines]            |
| Starbucks         | [portals/starbucks/index.html][url-portal-starbucks]                 | 10.74 KB | [@kleo][url-kleo] - [link][url-kleo-starbucks]                                       |
| Starlink          | [portals/starlink/index.html][url-portal-starlink]                   | 3.45 KB  | [@roshanravan][url-roshanravan] - [link][url-roshanravan-starlink]                   |
| T-Mobile          | [portals/t-mobile/index.html][url-portal-t-mobile]                   | 2.90 KB  | [@bigbrodude6119][url-bigbrodude6119] - [link][url-bigbrodude6119-t-mobile]          |
| Verizon           | [portals/verizon/index.html][url-portal-verizon]                     | 2.97 KB  | [@bigbrodude6119][url-bigbrodude6119] - [link][url-bigbrodude6119-verizon]           |

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## What Are "Evil Portals"? <a name="what-are-evil-portals"></a>

Evil Portals are custom captive portal systems often used in penetration testing
to demonstrate security risks. When connected to a rogue AP, users are directed
to a fake login page, where attackers can attempt to capture credentials or
inject payloads.

This repository provides:

- Realistic examples of AP-powered login systems ("Evil Portals").
- Configurable templates for use in controlled and authorized environments.
- Documentation on how these systems work (this README).

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Purpose <a name="purpose"></a>

The goal of this repository is to raise awareness about the vulnerabilities that
attackers may exploit using "Evil Portals" — captive portals designed to mimic
legitimate login systems on open access points (APs) or otherwise. By providing
realistic examples of how these systems operate, this repository aims to:

1. **Educate network administrators and developers** about potential risks.
2. **Demonstrate the importance of securing wireless networks** against
   unauthorized access and data interception.
3. **Help organizations and individuals develop stronger defenses** against
   phishing and other attacks facilitated by rogue APs.

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Getting Started <a name="getting-started"></a>

1. Clone this repository to your machine.
2. Set up supported hardware:

- A Raspberry Pi Pico W or other [supported hardware][url-lambda-guru] running
  [Pico-Portal][url-pico-portal].
- A Flipper Zero Wi-Fi module or similar ESP32-based devices.
- A Wi-Fi Pineapple or similar device that supports captive portal testing.

3. Use the provided templates from within the `/portals` folder to simulate
   captive portals in a controlled environment.
4. Run, preview, and demonstrate with transparency the templates to educate
   users about the risks of rogue APs and phishing attacks.

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Development <a name="development"></a>

This repository is open to contributions that improve the educational value of
the provided examples. To get started with development:

1. Fork this repository.
2. Ensure node.js and npm are installed on your machine.
3. In a new terminal, run `npm install` to install the required development
   dependencies using Node Package Manager.
4. Run `npm run build:watch` to watch for changes to files (HTML/SCSS) in the
   `/src` directory.
5. Navigate to "http://localhost:8080" to view a list of available templates.

   > ![Info][img-info] You can navigate to specific templates by visiting
   > "http://localhost:8080/{filename}/index.html" (replace `{filename}` with
   > the file you want to view).

6. Make your changes to the files in the `src/` folder and save, templates will
   recompile automatically.
7. Once you're happy with the changes, you can compile the production files from
   `/src` to `/portals` by running `npm run build`.
8. Commit your changes and push them to your fork.
9. Open a pull request to the main repository
   [here][url-red-portals-pull-requests].

Important development guidelines:

- Templates should be designed to work on both mobile and desktop devices.
- Templates should send a query param payload on form submit:
  `/login?username=example&password=example`.
- Keep examples under 20 KB per template, some hardware has this limitation.
- Templates must include the notice "This is a simulated template for
  educational purposes only. Not affiliated with or endorsed by any brand."

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## ⚠️ Disclaimer, Legal Notice, Responsible Use <a name="disclaimer-legal-notice-responsible-use"></a>

This repository is provided for **educational purposes only** and is intended
for use by:

- Security researchers
- Ethical hackers
- Penetration testers
- Individuals seeking to understand network vulnerabilities to improve defenses
- Web developers looking for examples on how to build login pages

Important Usage Guidelines:

- Only use these tools with explicit authorization from the owner of the network
  or system being tested.
- Unauthorized use may violate local, state, or international laws.
- The repository maintainers are not liable for misuse of the provided code,
  templates, or examples.

About Logos and Designs:

- The logos and designs in this repository are artistic representations or
  placeholders provided solely for educational purposes.
- They do not imply endorsement, affiliation, or sponsorship by the respective
  brands.

Terms of Use:

- The content in this repository is provided "as is," with no guarantees or
  warranties.
- By using the tools and templates herein, you accept full responsibility for
  ensuring compliance with applicable laws and obtaining proper authorization.

This repository is designed to be a teaching tool for ethical purposes. Users
are expected to:

- Only use these tools in environments where explicit authorization has been
  granted (e.g., in penetration tests or lab environments).
- Inform and educate stakeholders about the risks and solutions.
- Never deploy these tools in a way that causes harm, theft, or deception
  without consent.

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Licensing <a name="licensing"></a>

This project is licensed under the **MIT** License. See the
[LICENSE.md](LICENSE.md) file for the pertaining license text.

`SPDX-License-Identifier: MIT`

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Wrapping Up <a name="wrapping-up"></a>

Thank you for all of your support. It's important to me that this project stays
accessible to everyone, so please keep this software free and open source. If
you have any questions, please let me know by opening an issue
[here][url-new-issue].

| Type                                                                      | Info                                                           |
| :------------------------------------------------------------------------ | :------------------------------------------------------------- |
| <img width="48" src=".github/images/ng-icons/email.svg" />                | webmaster@codytolene.com                                       |
| <img width="48" src=".github/images/simple-icons/buymeacoffee.svg" />     | https://www.buymeacoffee.com/codytolene                        |
| <img width="48" src=".github/images/simple-icons/bitcoin-btc-logo.svg" /> | bc1qfx3lvspkj0q077u3gnrnxqkqwyvcku2nml86wmudy7yf2u8edmqq0a5vnt |

Fin. Happy programming friend!

Cody Tolene

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

<!-- IMAGE REFERENCES -->

[img-info]: .github/images/ng-icons/info.svg
[img-warning]: .github/images/ng-icons/warn.svg

<!-- PORTAL LINK REFERENCES -->

[url-portal-alaska-airlines]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/alaska-airlines/index.html
[url-portal-amazon]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/amazon/index.html
[url-portal-apple]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/apple/index.html
[url-portal-att]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/att/index.html
[url-portal-delta-airlines]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/delta-airlines/index.html
[url-portal-discord]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/discord/index.html
[url-portal-facebook]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/facebook/index.html
[url-portal-google]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/google/index.html
[url-portal-instagram]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/instagram/index.html
[url-portal-microsoft]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/microsoft/index.html
[url-portal-southwest-airline]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/southwest-airline/index.html
[url-portal-spectrum]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/spectrum/index.html
[url-portal-spirit-airlines]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/spirit-airlines/index.html
[url-portal-starbucks]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/starbucks/index.html
[url-portal-starlink]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/starlink/index.html
[url-portal-t-mobile]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/t-mobile/index.html
[url-portal-verizon]:
  https://raw.githack.com/CodyTolene/Red-Portals/main/portals/verizon/index.html

<!-- USER & USER CODE REFERENCES -->

[url-awlexegrecki-microsoft]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/blob/ee597f6d1edacc4a72a7687adf4a0e9dab7ae616/portals/Microsoft.html
[url-awlexegrecki]: https://github.com/Awlexegrecki
[url-bigbrodude6119-delta-airlines]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/281f8ffe25f08fa88fe8c334c89131f65c5a2afb#diff-b4fc76e467b7b429434070c839f1b16037169fe808dff2d70e475f30bf15de3e
[url-bigbrodude6119-southwest-airline]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/281f8ffe25f08fa88fe8c334c89131f65c5a2afb#diff-7894c2218212dc767afe6401c249f74c0de3381111a2bddc6721ef9900ec4ce8
[url-bigbrodude6119-t-mobile]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/9cbec168ab50724913e9a4e83b2e6b47fa955d7f#diff-8449df4d65846b35f8c364687937fb9ba8ca09ad2397978fc9a5e19da06c711a
[url-bigbrodude6119-verizon]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/9cbec168ab50724913e9a4e83b2e6b47fa955d7f#diff-97ea6f2e581d6aaad48433a780cb6f564b57e233465f3fc1fa01b942daea07d0
[url-bigbrodude6119]: https://github.com/bigbrodude6119
[url-breaching-google]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/09c66bbb310ea1a1f90b1e00a27b1e90ab5a0d3d#diff-4ef8251f8a9bf3dd2cf37224d237cbaa64ee7607660f28ce37b92e085d217059
[url-breaching]: https://github.com/breaching
[url-jmcrafter26-discord]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/blob/663975b441bc5ace4d47457d8826a4a181701fd2/portals/Discord.html#L1
[url-jmcrafter26-instagram]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/blob/663975b441bc5ace4d47457d8826a4a181701fd2/portals/instagram_realistic.html#L1
[url-jmcrafter26]: https://github.com/JMcrafter26
[url-jules0835-apple]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/b5adc38657ac7c7429c576afc261c4642fd55e09#diff-60c8686fd67fcb8612617383e99aa380eee28a17d3c0c8bcf54621e3884b4615
[url-jules0835]: https://github.com/jules0835
[url-kleo-starbucks]:
  https://github.com/kleo/evilportals/tree/master/portals/starbucks-login
[url-kleo]: https://github.com/kleo
[url-roshanravan-alaska-airlines]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/26a1b21f79b93290309d310f6ed83ac5ef0b3c82#diff-12c0462156cd8f8052b77b564b003e1d0ab3886b4d42db47ce03381787b30065
[url-roshanravan-amazon]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/26a1b21f79b93290309d310f6ed83ac5ef0b3c82#diff-454de47dc3f9f980011f78215de6f76df785b08a2299e066b5159fc877722c6d
[url-roshanravan-att]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/cc3762fddc15936a03179fb8a189be8dd0811d27#diff-c47616c5a20cac7efef1b90e688946d627c7ce28c1b105657e0bfefdc475a8e0
[url-roshanravan-facebook]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/10d6a69097d208e09363650e7af9a12c6979e612#diff-34b755e23907f7e47b7f990a45b11221112bd41d1fda0c52bb8a324dd67e1f5e
[url-roshanravan-spectrum]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/8a13000642eb6d337aeced1c022efa5fdebdb83d#diff-3065c554bc6b2a48213a9fc993c00ba666ea31e05687c1b0cb84010a7b58b07f
[url-roshanravan-spirit-airlines]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/26a1b21f79b93290309d310f6ed83ac5ef0b3c82#diff-670b566baa2e28a60d805f0697986262bd131ee665740d07b7f38f11e21255bc
[url-roshanravan-starlink]:
  https://github.com/bigbrodude6119/flipper-zero-evil-portal/commit/291b8e4386af2d6bc34e6fd43f0ba5e6bde61ae5#diff-17afe9aa8b2859f6bc7ebc81e402a659cf8c6b0778ff6a7065e2c1243f8d524b
[url-roshanravan]: https://github.com/roshanravan

<!-- OTHER LINK REFERENCES -->

[url-githack]: https://raw.githack.com/
[url-lambda-guru]: https://www.lambda.guru/
[url-new-issue]: https://github.com/CodyTolene/Red-Portals/issues
[url-pico-portal]: https://github.com/CodyTolene/Pico-Portal
[url-red-portals-pull-requests]: https://github.com/CodyTolene/Red-Portals/pulls
