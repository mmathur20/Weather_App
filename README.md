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

## Tasks
<!---
Add linked issue # of task to table cell

  Examples:
    Issue (completed):    					☑️ #1
    Issue (not complete):					⬜️ #1
    Issue (scrapped or moved to another iteration):		❌ #1

  See below:
--->
#### Example:
| Member  |  Task 0 |
| ------------ | ------------ |
| CoffeeBean99  |  ☑️ [#1](/../../issues/1)  |
| AZHenley  |  ⬜️ [#0](/../../issues/0)  |

#### Iteration 1

|  Member  |  Task 1 | Task 2   | Task 3  | Task 4  | Task 5 |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Thomas | ☑️ [#4](/../../issues/4)  | ☑️ [#8](/../../issues/8)  | ☑️ [#10](/../../issues/10)  |   |   |
|  Mahim | ☑️ [#3](/../../issues/3)  | ☑️ [#6](/../../issues/6)  | ☑️ [#7](/../../issues/7)  | ⬜️ [#9](/../../issues/9)  |   |
| William  | ☑️ [#2](/../../issues/2)  | ☑️ [#5](/../../issues/5)   |  ☑️ [#11](/../../issues/11)  | ☑️ [#12](/../../issues/12)   |  ☑️ [#13](/../../issues/13)  |
| Robert | ☑️ [#15](/../../issues/15)  | ☑️ [#17](/../../issues/17)  | ☑️ [#19](/../../issues/19)  |   |   |
|  Kellen  | ☑️ [#14](/../../issues/14)  | ☑️ [#16](/../../issues/16)  | ☑️ [#18](/../../issues/18)  |   |   |

#### Iteration 2

|  Member  |  Task 1 | Task 2   | Task 3  | Task 4  | Task 5 |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Thomas |  ☑️ [#77](/../../issues/77)  |   |   |   |   |
|  Mahim | ⬜️ [#9](/../../issues/9)  | ☑️  [#45](/../../issues/45)  |   |   |   |
| William  | ☑️ [#39](/../../issues/39)  | ❌ [#40](/../../issues/40)  | ☑️ [#41](/../../issues/41)  | ☑️ [#42](/../../issues/42)  | ☑️ [#65](/../../issues/65)  |
| Robert | ☑️ [#53](/../../issues/53)  | ☑️ [#54](/../../issues/54)  |   |   |   |
|  Kellen  | ⬜️ [#21](/../../issues/21)  | ☑️ [#50](/../../issues/50)  | ☑️ [#51](/../../issues/51)  | ☑️ [#52](/../../issues/52)  | ☑️ [#64](/../../issues/64)  | ☑️ [#84](/../../issues/84)  |

#### Iteration 3

|  Member  |  Task 1 | Task 2   | Task 3  | Task 4  | Task 5 |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Thomas |  ☑️ [#128](/../../issues/128)  | ⬜️ [#129](/../../issues/129)  |   |   |   |
|  Mahim |  ☑️ [#9](/../../issues/9)  | ☑️ [#76](/../../issues/76)  |  ❌ [#96](/../../issues/96) | ☑️ [#97](/../../issues/97)  |   |
| William  | ☑️ [#66](/../../issues/66)  | ☑️ [#72](/../../issues/72)  | ☑️ [#74](/../../issues/74)  | ☑️ [#76](/../../issues/76)  | ☑️ [#86](/../../issues/86)  |
| Robert |  ⬜️ [#90](/../../issues/90)  | ☑️ [#91](/../../issues/91)  | ⬜️ [#92](/../../issues/92)  |   |   |
|  Kellen  |  ☑️ [#101](/../../issues/101)  |  ☑️ [#102](/../../issues/102) | ☑️ [#103](/../../issues/103)  | ⬜️ [#105](/../../issues/105)  |   |

#### Iteration 4

|  Member  |  Task 1 | Task 2   | Task 3  | Task 4  | Task 5 |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| Thomas |  ☑️  [#129](/../../issues/129)  | ⬜️  [#160](/../../issues/160)  |   |   |   |
|  Mahim |  ⬜️  [#96](/../../issues/96)  | ☑️  [#140](/../../issues/140)  | ⬜️  [#141](/../../issues/141)  | ⬜️  [#142](/../../issues/142)  |   |
| William  |  ☑️ [#111](/../../issues/111)  | ☑️ [#112](/../../issues/112)  | ☑️ [#116](/../../issues/116)  |  ☑️ [#143](/../../issues/143) | ☑️ [#151](/../../issues/151)  |
| Robert |  ⬜️  [#147](/../../issues/147)  | ⬜️  [#148](/../../issues/148)  | ⬜️  [#149](/../../issues/149)  |   |   |
|  Kellen  |  ⬜️  [#137](/../../issues/137)  | ⬜️  [#154](/../../issues/154)  |   |   |   |
