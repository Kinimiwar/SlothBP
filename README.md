# SlothBP

Collaborative Breakpoint Manager for x64dbg.

## Example INI

```
[Memory]
VirtualAlloc="kernel32:VirtualAlloc"

[Code Injection]
SetWindowsHookEx="user32:SetWindowsHookEx"

[Networking]
UrlDownloadToFile="urlmon.UrlDownloadToFile"
```

See [SlothBP.ini](https://github.com/x64dbg/SlothBP/blob/master/SlothBP.ini) for a more complete example.
