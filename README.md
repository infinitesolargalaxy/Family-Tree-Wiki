# Family-Tree-Wiki #
Intended to be helpful for writing a prequel, current story, and after story. Yes this is a wiki for tracking fictional character genealogies.

## Stack: ##
Laravel/Php for the backend with a MySQL database.
Vue/js for the front-end.

## MVP Features: ##

1. Left Bar allows selection of Characters sorted by their last name.

2. Bottom Bar allows selection of time from a timeline
- Initially this will only be years.
- Potentially will be expanded to have a calendar picker to allow months and dates.

3. The center of the UI should show the current family tree selected
- It is interactable and can be panned to find ancestors
- Clicking on a tree node should reveal more information about the character.
    - This information should only be up until the current date.
    - i.e. A certain character finds a macguffin at 2019, but that isn't known yet in 2018!

4. Script to load data .json file into database
