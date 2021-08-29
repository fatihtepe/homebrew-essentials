## To install smartmontools, copy and paste the code below into the Terminal

```
brew install smartmontools && sudo smartctl --all /dev/disk0
```

 Launch Terminal and at the prompt, type `diskutil list` and press Return. This will show information on the SSD in your Mac.

 `smartctl -a disk0` Smartmontools will run and post a report on the health of your drive. You can give the numbers a look and make sure your SSD is okay.