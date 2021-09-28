# baby-doge
A carbon copy of the Baby Doge contract

----------------------------------------------------

Investigating Baby Doge rug potential.

    function claimTokens() public onlyOwner {
            payable(_owner).transfer(address(this).balance);
    }
    
This function appears to be a method to pull all the balance (liquidity) out of the coin.
I have to investigate further but this is how it appears. 

----------------------------------------------------
# Contract

Contract: 0xc748673057861a797275CD8A068AbB95A902e8de 
Creator Wallet: 0xf103d2AbA493749a402B7dE11cF31f5844062B74
BSCScan: https://bscscan.com/token/0xc748673057861a797275cd8a068abb95a902e8de
Official Website: https://babydogecoin.com/
Official Twitter: @BabyDogeCoin

----------------------------------------------------

# Future

While this coin does appear to be legit despite the obvious code that has potential to yield
a rug pull, it is worth keeping an eye on for suspicious activity if investing within this coin.
