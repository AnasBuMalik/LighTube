# LighTube

A minimalist, zero-dependency YouTube player designed for low-spec devices and older machines.

Mainstream web players and standard embeds often load unnecessary scripts, side panels, and layout animations that consume excess CPU and RAM. LighTube strips away all overhead, delivering a lightweight playback interface built purely with vanilla HTML, CSS, and JavaScript.

## Features

- **Resource Efficient:** Built with plain JavaScript and CSS. Zero frameworks, zero external libraries.
- **Performance-First UI:** Dark Neo-Brutalist design with sharp borders, no CSS blurs, and zero transition animations.
- **Memory Control:** Pressing `Esc` immediately destroys the iframe instance and frees browser memory.
- **Timestamp & Link Support:** Handles standard YouTube links, Shorts, and timestamp parameters (`&t=`).
- **Privacy Focused:** Uses `youtube-nocookie.com` embed endpoints.

## Usage

1. Open `index.html` in any web browser.
2. Paste a YouTube video URL into the input field.
3. Press `Enter` or click `PLAY`.
