### Download Youtube Videos
https://github.com/yt-dlp/yt-dlp

**Video to Audio**
```bash
./yt-dlp -f m4a --audio-quality 0 --yes-playlist --verbose --embed-metadata --embed-thumbnail --embed-chapters "URL"
```

### Count lines of files in directory unix
```bash
find . -type f -name "*.ts" | xargs cat | wc -l
```
