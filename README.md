# Little Timer!

### Usage

To use the Little Timer, simply visit the following link and add a timestamp parameter in the URL:

**Example:**

```
https://prodbyeagle.github.io/little-timer/?time=2024-08-15T12:00:00Z
```

This will start the timer from the specified time. The time should be provided in the format YYYY-MM-DDTHH:MM:SSZ (ISO 8601 format with Z to indicate UTC time).

### Testing Milestone Animation

If you want to test the milestone animation, you can set the timer to start just 4 seconds before the 24-hour mark by adding `&debug=true` to the URL and adjusting the time parameter accordingly.

**Example:**

```
https://prodbyeagle.github.io/little-timer/?time=2024-08-15T12:00:00Z&debug=true
```

This will set the timer to 4 seconds before 24 hours and enable the debug mode, allowing you to see the milestone animation.

### Adding to OBS

You can easily add this timer to OBS (Open Broadcaster Software) as a browser source.

**Steps:**

1. Open OBS and add a new "Browser" source.
2. Set the URL to your customized timer link, for example:
   ```
   https://prodbyeagle.github.io/little-timer/?time=2024-08-17T23:00:00Z
   ```
3. Set the dimensions:
   **Width:** 400  
   **Height:** 150
4. Adjust other settings as needed.

Your timer is now ready to be used in your OBS scenes!

---
