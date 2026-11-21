# May Villa Resort Website

A hospitality website project with visitor enquiry interactions, including a booking-enquiry form that prepares a WhatsApp message.

## Features visible in the source
- Check-in and check-out date interaction.
- Checkout minimum date updated from the selected check-in date.
- Room and guest information collection.
- Basic phone-number and guest-count validation.
- Enquiry details formatted and directed to WhatsApp.
- Separate JavaScript files for enquiry handling, navigation and chatbot behaviour.

## Technology stack
- HTML5
- CSS3
- Vanilla JavaScript
- WhatsApp click-to-chat URL integration

## Run locally
1. Clone the repository.
2. Open the main HTML page in a browser or use a static development server.
3. Test the enquiry form with sample details only.

## Security and privacy
The current enquiry flow places submitted form values into a WhatsApp URL. Encode user-provided values with URL encoding, validate all fields, and provide a privacy notice before collecting personal information. Do not treat a WhatsApp redirect as a confirmed reservation.

## Future improvements
- Add server-side enquiry validation and spam protection.
- Add accessible form labels and inline validation messages.
- Add automated tests for date order and guest-count boundaries.
- Document the chatbot's data sources and behaviour.
- Add screenshots and a verified deployment URL.

## Project status
Website enquiry prototype. An enquiry is not a confirmed booking.
