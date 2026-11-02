BADAMI FOODS WEBSITE
====================

How to open
-----------
Double-click index.html. It opens in your browser. No internet or installation needed.

IMPORTANT: put your WhatsApp number
-----------------------------------
Open js/script.js in Notepad and change the lines at the top:

  whatsappNumber: "923000000000"   <- your number with country code, no + or spaces
                                      (0300 1234567 becomes 923001234567)
  phoneText:  "0300 0000000"        <- phone number shown in the footer
  emailText:  "info@badamifoods.example"

How ordering works
------------------
The customer picks packs and fills in the form. When they press the button, WhatsApp
opens with the full order message ready to send to your number.
(A simple website cannot store orders by itself, so WhatsApp is used to receive them.)

Prices
------
Prices are in js/script.js under PACKS. Current price: Rs. 450 per kg.

Put it online (optional)
------------------------
Upload this whole folder to any free host such as Netlify Drop (app.netlify.com/drop),
GitHub Pages or Vercel.
