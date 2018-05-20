# Context-Validation-Android-app

The application I built scans for context features (such as battery state, WiFi access points, and nearby cellular towers) on an interval, and records these features into a database.  Although this sounds trivial, it turns out that performing this task (and doing so efficiently) requires knowledge of many Android app lifecycle concepts, as well as the use of system service APIs which each has their own intricacies.
