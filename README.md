<div align="center">
    <h1>CodeWalker by dexyfex</h1>
    This program is for viewing the contents of GTAV RPF archives.
</div>

## Requirements:
- PC version of GTA:V;
- 4GB RAM (8+ recommended);
- Windows 7 and above, x64 processor;
- .NET framework 4.5 or newer from [Microsoft](https://www.microsoft.com/net/download/thank-you/net471);
- DirectX 11 and Shader Model 4.0 capable graphics.

# App Usage:

Everyone should know already how to use Codewalker and its RPF Explorer. If not, there's many tutorials out there video or text. There's also the main branch.

Anyway, this new fork is:

**Based on:**
- [crxhvrd/CodeWalkerProjects](https://github.com/crxhvrd/CodeWalkerProjects), the fork this build comes from
- [dexyfex/CodeWalker](https://github.com/dexyfex/CodeWalker), the original CodeWalker

**Included in the build:**
- [naudio/NLayer](https://github.com/naudio/NLayer), the MP3 decoder for playback and export

**Used for reference (no code copied):**
- [Hancapo/fivefury](https://github.com/Hancapo/fivefury), for the MP3 AWC layout, which the import logic follows closely
- [vgmstream/vgmstream](https://github.com/vgmstream/vgmstream), for notes on AWC codecs and repeated frames at block starts

**External tool, included:**
- [FFmpeg](https://ffmpeg.org) with LAME, for encoding MP3 on import
