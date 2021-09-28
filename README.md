# baby-doge
A carbon copy of the Baby Doge contract

----------------------------------------------------

Investigating Baby Doge rug potential.

    function claimTokens() public onlyOwner {
            payable(_owner).transfer(address(this).balance);
    }
    
This function appears to be a method to pull all the balance (liquidity) out of the coin.
I have to investigate further but this is how it appears. 
