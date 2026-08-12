# Miami-Dade Clerk Self-Service Kiosk Prototype

This is a browser-based prototype for a touchscreen kiosk.

## Run
Open `index.html` in a modern browser. For kiosk testing, use the browser's full-screen/kiosk mode.

## Important
- This prototype uses demo data.
- It does not process real payments.
- It does not store card data.
- It does not connect to Miami-Dade Clerk production systems.
- Production integration requires authorization, credentials, security review, and approved payment/document hardware.

## Integration targets
The Miami-Dade Clerk publishes authorized APIs for civil, traffic, official records and other court/record data. The production app should call those APIs from a secure backend rather than exposing developer credentials in the kiosk browser.
