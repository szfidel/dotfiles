# Kanata MacOS

1. In the plist file change
   Replace /opt/homebrew/bin/kanata with the actual path from which kanata
   Replace YOUR_USERNAME with your actual macOS username

2. Set the proper permissions for the plist file:

```
sudo chown root:wheel /Users/YOUR_USERNAME/Library/LaunchDaemons/com.kanata.daemon.plist
sudo chmod 644 /Users/YOUR_USERNAME/Library/LaunchDaemons/com.kanata.daemon.plist
```

3. Load the system daemon
   `sudo launchctl load /Users/YOUR_USERNAME/Library/LaunchDaemons/com.kanata.daemon.plist`
4. Start the system
   `sudo launchctl start com.kanata.daemon`

## kanata.kbd

5. Function keys F1 to F4 and swapped brightness keys to F5 and F6

6. Home row mods when held

- g, h = control
- f, j = command
- d, k = shift
- s, l = ctrl+alt+cmd (for window management)

7. Shift numbers and symbols when held

8. "Navigation" layer when hold spacebar 500ms

- Spanish accents plus ñ
- hjkl to directional arrows
