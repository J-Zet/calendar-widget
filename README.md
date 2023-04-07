# Calendar Widget
Calendar Widget is a JavaScript widget that can be easily integrated into any web page or application. Its purpose is to provide a simple, customizable calendar interface that allows users to view and interact with dates and events.

## Getting Started
To use Calendar Widget, you can either download and include the compiled JavaScript file in your project, or link to it directly from the jsDelivr CDN. You can find the latest version of the compiled file in the Releases section of this repository.

## Including the JavaScript file in your project
To include the compiled JavaScript file in your project, download the latest release from the Releases section of this repository, and add it to your project's HTML file with a `<script>` tag:

```html
<script src="calendar-widget.js"></script>
```

## Linking to the jsDelivr CDN
To link to the compiled JavaScript file from the jsDelivr CDN, use the following URL:

```html
<script
    type="module"
    src="https://cdn.jsdelivr.net/gh/j-zet/calendar-widget/dist/calendar-widget.js"
></script>
```

## Usage
To use Calendar Widget, add a container element to your HTML file with the a `data-affiliation`-attribute of `calendar-widget.online-booking.de` a `data-id` attribute that reflects the id of the widget config to show and an optional minimum height to allow better rendering experience:

```html
<div
    data-affiliation="calendar-widget.online-booking.de"
    data-id="clcy0rduo000694n1hvlnp8pa"
    style="min-height: 32rem"
></div>
```

For a full list of options and methods, see the documentation.

## License
Calendar Widget is licensed under the MIT License.