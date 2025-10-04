*this is pseudocode for math function for calculating a total of a sell*

    function ComputeTotal(Price, Quantity, TaxRate) {
        SubTotal := Price * Quantity
        Tax := SubTotal * TaxRate
        Total := SubTotal + Tax
        Round(Total * 100) / 100
    }
