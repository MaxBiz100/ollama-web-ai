Use this link to test the pages

https://hpssjellis.github.io/ollama-web-ai/drafts/ollama-web##.html

Note ollama-web21.html is seriously powerful with image, video and pure audio translation.

The real page should just be downloaded to your computer so that internet is not needed.



For testing we have (BUT THAT IS A SERIOUS SECURITY ISSUE.) The PWA will be different.

```
setx OLLAMA_ORIGINS "*"
```

but that has some serious security issues (any webpage could call your Ollama), when a PWA is made we can change that command to something like, which should be much more stable.

```
setx OLLAMA_ORIGINS "chrome-extension://YOUR-ID-HERE"

```


The other option is to simply shutdown ollama in the system tray when not using it. It is an app so you can just load it when you want to keep using it.
