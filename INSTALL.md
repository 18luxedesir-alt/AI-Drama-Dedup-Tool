# FFmpeg Installation Guide

FFmpeg is required for AI-Drama-Dedup-Tool to process videos.

## Windows Installation

### Option 1: Download Pre-built Binary (Recommended)

1. Go to https://www.gyan.dev/ffmpeg/builds/
2. Download ffmpeg-release-essentials.zip
3. Extract to C:\ffmpeg\
4. Add to PATH:
 - Open Start → Search "Environment Variables"
 - Click "Edit the system environment variables"
 - Click "Environment Variables"
 - Under "System variables", find "Path" → Edit
 - Add C:\ffmpeg\bin
 - Click OK

### Option 2: Using Package Manager

Chocolatey:
 choco install ffmpeg

Scoop:
 scoop install ffmpeg

## Verify Installation

Open Command Prompt or PowerShell and type:
 ffmpeg -version

If you see version info, FFmpeg is installed correctly.

## Troubleshooting

"FFmpeg not found" error:
- Make sure C:\ffmpeg\bin is in your system PATH
- Restart the application after installing FFmpeg
