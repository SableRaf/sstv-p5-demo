# SSTV Encoding for p5.js

This project demonstrates how to encode images created with p5.js into [Slow Scan Television](https://en.wikipedia.org/wiki/Slow-scan_television) (SSTV) audio signals.

SSTV is a method of transmitting static images via radio waves, used mainly by [amateur radio operators](https://en.wikipedia.org/wiki/Amateur_radio_operator).

This project is heavily based on the amazing [Web-SSTV](https://github.com/CKegel/Web-SSTV/) by Christian Kegel. Please support the official release.

## Features
- Encode the p5.js canvas into an SSTV audio signal
- Download the SSTV audio file
- Support for various SSTV modes

## Limitations
Decoding is not currently supported. If you'd like to help with this, please head over to the [Web-SSTV](https://github.com/CKegel/Web-SSTV/) repository.

## Usage
1. Clone the repository.
2. Navigate to the project directory.
3. Open `index.html` in your web browser to run the application.
4. Modify the p5.js code in the sketch.js file to create custom visuals that can be encoded into SSTV signals.

## Decoding Images
To decode the image from the audio, you will need an SSTV decoder. There are many available online, such as [MMSSTV](https://hamsoft.ca/pages/mmsstv.php) for Windows, [Robot36](https://play.google.com/store/apps/details?id=xdsopl.robot36&hl=en) for Android, or [CQ SSTV](https://apps.apple.com/us/app/sstv-slow-scan-tv/id387910013) for iOS/iPadOS.

## SSTV Modes

Multiple SSTV modes are supported, including:

-   **Martin** (e.g., Martin M1, Martin M2)
-   **Scottie** (e.g., Scottie S1, Scottie S2, Scottie DX)
-   **PD** (e.g., PD50, PD90, PD120, PD160)
-   **WRASSE SC2-180**

## Contributing

For anything related to the SSTV code, please contribute to the original project at [Web-SSTV](https://github.com/CKegel/Web-SSTV/).

For the p5.js integration, feel free open an issue or submit a pull request.

## License

This project is available freely under the MIT license. See the [LICENSE.md](LICENSE.md) file for more information.

## Dependencies

- [P5.js](https://p5js.org/)
- [SSTV](https://en.wikipedia.org/wiki/Slow-scan_television)