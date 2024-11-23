### Download Youtube Videos 
[Youtubedl docs](https://github.com/ytdl-org/youtube-dl)

**Video to Audio**
```bash
 youtube-dl -f bestaudio --verbose -x --user-agent "Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/127.0.6533.103 Mobile Safari/537.36" "URL"
```

### Count lines of files in directory unix
```bash
find . -type f -name "*.ts" | xargs cat | wc -l
```