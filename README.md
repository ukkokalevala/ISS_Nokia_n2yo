Nokia LCD display 5110 configuration:
    
    CLK (Clock) - D1: This is the SPI clock line. It synchronizes data transmission between the Wemos and the Nokia display.

    DIN (Data In) - D2: This is the SPI MOSI (Master Out Slave In) line. The Wemos sends data to the display through this pin.

    DC (Data/Command) - D5: This pin tells the display whether incoming data is a command (low) or display data (high).

    CE (Chip Enable) - D6: Also known as Chip Select (CS). It activates the display for data transfer when pulled low.

    RST (Reset) - D7: Resets the display when pulled low.

This code for tracking the ISS with the Nokia display using above pin definitions. This code display "ISS Tracker" initially, then retrieve and display the ISS location data based on Wemos D1 and the N2YO API.
