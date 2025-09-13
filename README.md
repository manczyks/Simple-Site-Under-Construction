# Simple-Site-Under-Construction
This is a simple website template that displays a countdown clock for a site under construction. It’s perfect if you want to let visitors know when your site will launch.

## Features
- Clean and minimal design
- Countdown timer that updates automatically
- Easy to customize text, launch date, and styles
- Works in any modern web browser

## Getting Started
1. Download or Clone this Repository
```
	git clone https://github.com/manczyks/Simple-Site-Under-Construction.git
```
2. Open in a Browser
Simply open index.html in your browser to view the countdown page.
3. Customize Your Website
* Open index.html in a text editor.
* Update the site title, headline, and launch date with your information. Example:
```
<script type="text/javascript">
$(function () {
var austDay = new Date("August 15, 2028 02:15:00");
    $('#defaultCountdown').countdown({until: austDay, layout: '{dn} {dl}, {hn} {hl}, {mn} {ml}, and {sn} {sl}'});
    $('#year').text(austDay.getFullYear());
    });
</script>
```
4. (Optional) Customize Styles
Edit style.css to change colors, fonts, or layout.

## License
This project is free to use and modify.