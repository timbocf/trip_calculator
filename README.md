# Trip Calculator

An initial scaffold for a browser-based trip calculator. The repository currently contains a Bootstrap page shell and an empty JavaScript file.

**Status: the trip-calculation functionality is not implemented yet.**

## What is included

| File | Current purpose |
| --- | --- |
| [index.html](index.html) | Responsive HTML document, an empty container/row and Bootstrap imports |
| [trip_calculator.js](trip_calculator.js) | Placeholder for future calculation logic; currently empty |

The page's title is still **Title**, and the body has no distance, speed, stop or result controls.

## Open the scaffold

Clone or download the repository, keep both files in the same directory and open **index.html** in a browser.

For an optional local server, run this from the repository:

~~~bash
python3 -m http.server 8000
~~~

Then visit http://localhost:8000. Seeing a mostly empty page is expected with the current source.

## Dependencies

Bootstrap **5.3.8** CSS and its JavaScript bundle are referenced from jsDelivr. Internet access is required for uncached CDN assets.

There is no package manager, build system, backend, routing service or API key configuration in the repository.

## Intended next implementation

A useful first version can accept manually entered mileage and average speed, calculate driving duration and display the result. Stop durations and departure/arrival times can be introduced after that basic calculation is working.

These are development directions, not existing features. Automatic routing, live traffic, maps and truck-specific route restrictions are not currently integrated.

## Where to work

Add input fields and the result area in **index.html**. Implement parsing, validation, arithmetic and display updates in **trip_calculator.js**. The existing script tag already loads that file at the end of the body.

Keep unit labels explicit as the interface develops, particularly whether durations are decimal hours or hours/minutes.

## Initial verification

At this stage, verify that **index.html** opens and that the JavaScript file is loaded without a missing-file error. Calculation test cases become meaningful once input fields and arithmetic are implemented.

No automated test suite or runnable calculator is included in this initial scaffold.
