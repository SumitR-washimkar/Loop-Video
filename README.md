# Loop Video Player

A simple, lightweight local video player that loops through videos in a folder automatically. Built with pure HTML, CSS, and JavaScript - no dependencies required!

## Features

- 🔄 **Auto-loop**: Automatically plays the next video when one ends
- 📁 **Folder Selection**: Load entire video folders at once
- 🎬 **Playlist View**: See all videos in a sidebar playlist
- ▶️ **Click to Play**: Click any video in the playlist to jump to it
- 🎨 **Modern UI**: Clean, dark-themed interface
- 🚀 **No Installation**: Run directly in your browser

## Screenshot

The app features:
- A dark-themed interface
- Sidebar with video playlist
- Main video player area
- Highlighting for currently playing video

## How to Use

1. **Open the App**
   - Double-click `index.html` to open it in your default browser
   - Or right-click and select "Open with" → your preferred browser

2. **Load Videos**
   - Click the "Choose Files" button in the sidebar
   - Select a folder containing your video files
   - The app will automatically load all videos from that folder

3. **Play Videos**
   - Videos will start playing automatically
   - Click any video in the playlist to jump to it
   - Videos loop continuously (when one ends, the next begins)

## Supported Video Formats

The app supports common video formats that your browser can play:
- MP4 (`.mp4`)
- WebM (`.webm`)
- OGG (`.ogg`)
- And other formats supported by HTML5 video

## Project Structure

```
Loop Video/
├── index.html          # Main application file
└── README.md           # This file
```

## Technical Details

- **Pure Vanilla JavaScript**: No frameworks or libraries needed
- **HTML5 Video API**: Uses native browser video capabilities
- **File API**: Reads files directly from your local system
- **Responsive Design**: Adapts to different screen sizes

## Browser Compatibility

Works on modern browsers that support:
- HTML5 Video
- File API
- `webkitdirectory` attribute

Tested on:
- Chrome/Edge (Recommended)
- Firefox
- Safari

## Notes

- All videos are played locally - nothing is uploaded to the internet
- The app runs entirely in your browser
- Videos must be in formats supported by your browser
- For best performance, keep video files at reasonable sizes

## Tips

- **Auto-play**: Videos start automatically when loaded
- **Loop Behavior**: When the last video ends, it loops back to the first one
- **Controls**: Use the built-in video controls to pause, seek, or adjust volume
- **Multiple Folders**: You can load a different folder at any time by clicking the folder input again

## License

Free to use and modify as needed.

## Author

Created as a simple local video looping solution.

---

**Enjoy your looping videos!** 🎥
