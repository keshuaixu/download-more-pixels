# download-more-pixels

Downloads more pixels to your shitty 1366x768 screen. It's a wrapper for xrandr.

## Installation

Add the script to your PATH.

Edit the `native_x` and `native_y` to match your screen's native resolution.

## Usage

```
# sets the resolution to 1920x1080,
download-more-pixels 1920 1080 

# makes things smaller to fits the horizontal edge to the screen
download-more-pixels -h 1920 1080

# makes things smaller to fits the vertical edge to the screen
download-more-pixels -v 1920 1080 

# resets the resolution to default
download-more-pixels 
```



