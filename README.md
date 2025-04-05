# Web Development Project 5 - SpaceX Launch Dashboard

Submitted by: **Saakshi Podduturu**

This web app: This interactive web app visualizes SpaceX launch data fetched from a public API. It displays a searchable and filterable list of launches, along with summary statistics such as total launches and average flight number. Users can search by mission name, filter by success status, and adjust a year range slider to explore launches over time. The dashboard provides a clear and engaging snapshot of SpaceX's mission history.

Time spent: 5 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **The site has a dashboard displaying a list of data fetched using an API call**
  - The dashboard should display at least 10 unique items, one per row
  - The dashboard includes at least two features in each row
- [x] **`useEffect` React hook and `async`/`await` are used**
- [x] **The app dashboard includes at least three summary statistics about the data** 
  - The app dashboard includes at least three summary statistics about the data, such as:
    - Flight number
    - Success
    - Launch year
- [x] **A search bar allows the user to search for an item in the fetched data**
  - The search bar **correctly** filters items in the list, only displaying items matching the search query
  - The list of results dynamically updates as the user types into the search bar
- [x] **An additional filter allows the user to restrict displayed items by specified categories**
  - The filter restricts items in the list using a **different attribute** than the search bar 
  - The filter **correctly** filters items in the list, only displaying items matching the filter attribute in the dashboard
  - The dashboard list dynamically updates as the user adjusts the filter

The following **optional** features are implemented:

- [x] Multiple filters can be applied simultaneously
- [x] Filters use different input types
  - e.g., as a text input, a dropdown or radio selection, and/or a slider
- [x] The user can enter specific bounds for filter values

The following **additional** features are implemented:

* [ ] List anything else that you added to improve the site's functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src= 'https://app.screencastify.com/v3/watch/bDeEGU0741MDkl079Jj7' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ...  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

One of the main challenges was managing asynchronous API calls using useEffect and async/await. Ensuring that the data loaded correctly before attempting to render it required careful state management and conditional rendering to avoid errors during the initial render.

Another challenge was implementing dynamic filtering—especially combining multiple filters (search, success status, and year range). Making sure that all filters worked together and updated the UI in real-time took some debugging and fine-tuning.

Styling the dashboard and making it user-friendly while keeping the layout clean and readable was also a challenge, particularly when displaying different types of input controls like text, dropdowns, and sliders.

## License

    Copyright [yyyy] [Saakshi Podduturu]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
