# datetime
A date time screensaver with shifting pixels.

# Why
For my home assistant dashboard which is using FullyKiosk, I wanted a useful screensaver. I created this simple HTML file that grabs the system date and time.

# Features
To avoid burn-in for displays, every 10 seconds there is a maximum 50px shift of the <div>. The actual shift is randomised, to further reduce likelihood burn-in. My wall panel is IPS and has been running for over a year 24/7 without any visible burn-in. I make no guarantees about your screens: YMMV.

Localisation: Since the page uses the system settings, it will match whatever the system is set to. If you want a different format than what your system has, you'll need to fork. By default, I have the full text weekday and full text of the month.
