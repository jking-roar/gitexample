*this is pseudocode for math function for calculating a total of a sell*


    function TotalWithTax(Price, Quantity, TaxRate) {
        SubTotal := Price * Quantity
        Tax := SubTotal * TaxRate
        Total := SubTotal + Tax
        Round(Total * 100) / 100 
    }

