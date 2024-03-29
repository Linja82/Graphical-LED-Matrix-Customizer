# Graphical LED Matrix Customizer
App that allows you to customize individual pixel colours for an LED matrix in a graphical format.  
  
The generated code is designed for an ESP8266 module with the LED strip connected to pin D7.

## Authors:

# Instructions:

## 1. Setting up the companion app:
<details>
  <summary>Click me</summary>
  
  1. Go to the [Google Sheets App](https://docs.google.com/spreadsheets/d/1BcQXLhg0BJCwyGEYzw7sAEM5Z4Viso_Yu5WbtARvCH0/copy).
  2. Sign into your Google account if you aren't already signed in
  3. Click [Make a copy]
     
     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Copy%20document.png" width=600>  
  4. Click on [Draw Grid]

     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Draw%20Grid2.png" width=600>
  5. A pop-up saying "Authorization Required" will appear. Click [Continue].

     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Continue.png" width=600>
  6. A new window will open and ask you to "Choose an account". Select the same account you opened the Google Sheet with.

     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Choose%20an%20account.png" width=600>
  7. The next screen will say "Google hasn't verified this app". Click on [Advanced]

     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Google%20hasn't%20verified.png" width=600>
  8. Scroll down and click on [Go to LED Panel Command Generator (unsafe)]

     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Go%20to%20LED%20Panel%20Command%20Generator2.png" width=600>
  9. A new screen will appear. Click on [Allow]

      <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Allow.png" width=600>
  10. The new window should close.
</details>  

## 2. Creating your lighting pattern:
<details>
  <summary>Click me</summary>

  1. In the Google Sheet enter your desired panel width and height. This refers to the number of pixels you have in the width and height.
      Width refers to the strip of LEDs, while height is the stacking of strips next to each other.

      Note: The "Total Pixels" value is calculated automatically.
  2. Click the [Draw Grid] button. A grid of black cells should appear in the size you specified in the previous step.

     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Draw%20Grid2.png" width=600>  
     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Black%20Grid.png" width=600>  
  3. Add background colours to each of the cells in the grid according to your design.

     <img src="https://github.com/Linja82/DME-Layered-Light-Box/blob/main/Images/Coloured%20Grid2.png" width=600>  
  4. Click the [Generate] button. A bunch of text should appear in Cell D1.
</details>

## 3. Wiring:

## 4. Power supply selection:
