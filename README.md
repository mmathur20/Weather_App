# TMWRK - Weather App

#### You are looking at the README.md file for the team. For the README.md file of the app, please check inside the `WeatherApp/` directory.

----

**Project description:** Build a weather app that fetches data from an API.

**Communications:**
- 💬 [Github Issues](/../../issues/)
- 💬 [Discord](https://discord.gg/xdqKESzMjX)

## Structure and Features
**Note:** These features are **NOT** final.

#### Main Window:
- Top search bar to lookup city
	 - Dropdown: Suggest cities as user types in search bar and update suggestions after a few seconds after the last keypress
	 - Click city in dropdown to add city to the front index of tab in the central layout
	 - If city exists in the bookmark, position city to front index of tab and shift other cities to the right
- Central layout
	 - Background graphic according to condition and time
	  - Animations like rain and snow (if there's enough time at final iteration); otherwise static background will suffice
	 - Weather of city:
	 - > Condition: sunny, cloudy, snowy, etc.
	 - > Temperature: Fahrenheit / Celsius
	 - > City time: Standard or military time (6:45 PM / 18:45) depending on settings
	 - > City time: Display both system time and city time
	 - Forecast for the week
	 - Tabs to switch among bookmarked cities
	 - Button to manage city (opens bookmark window)
	 - Alert message (e.g. "bring umbrella", "potential flooding", "stay indoors" if it's raining/thundering)
- Sidebar
	 - Design
	 - > Collapsed: Shows **only** icons
	 - > Expanded: Shows icons and text
	 - Buttons to open bookmark window, settings window, and expand/collapse
- Historical Data Lookup
	 - Use API to pull a certain category (Precipitation, Temps, etc.) for a certain date range and location.
 	 - Convert data into a graph using matplotlib.

#### Bookmark Window:
- Manage bookmark
	 - Change order of list of cities
	 - Remove city
	 - Option to add a note (e.g. "Plan to visit Knoxville this weekend")
	 - Save button and cancel button
- Bookmark data stored as Python dictionary
- Saving stores data to `bookmark.json`
- Status bar (Saving...)

#### Settings Window:
- Manage settings
	 - Theme: dark/light theme
	 - Font family
	 - Option of Fahrenheit/Celsius
	 - Option of standard or military time
	 - Save button and cancel button
- Settings data stored as Python list/tuple
- Saving stores data to `settings.json`
- Status bar (Saving...)
