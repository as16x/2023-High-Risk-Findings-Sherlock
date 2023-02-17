# 2023-High-Risk-Findings-Sherlock
<p align="center">
                                <a href="https://www.ajna.finance/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/as16x/2023-Midium-Risk-Findings-Sherlock/main/Sherlock/Ajna.jpg" width="60" height="60" alt="Javascript" /></a></p>    
                                
---
* [[H-01] RewardsManager doesn't delete old bucket snapshot info on unstaking - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/183)
* [[H-02] Anyone who approved quote tokens to a pool can be forced to take - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/145)
* [[H-03] CryptoPunks NFTs may be stolen via deposit frontrunning - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/140)
* [[H-04] scaledQuoteTokenAmount isn't updated to be collateral sell value in the quote token constraint case of _calculateTakeFlowsAndBondChange - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/139) 
* [[H-05] removeCollateral miss bankrupcy logic and can make future LPs sharing losses with the current ones - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/133)
* [[H-06] Executing funded standard proposals can be prevented by a proposal slate with duplicate proposals - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/119)
* [[H-07] ERC721Pool's mergeOrRemoveCollateral allows to remove collateral while auction is clearable - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/105)
* [[H-08] Remaining collateral used by ERC721Pool is missed in Auctions take and bucketTake return structures - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/103)
* [[H-09] ´moveQuoteToken()´ can cause bucket to go bankrupt but it is not reflected in the accounting - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/83)
* [[H-10] ERC721Pool's take will proceed with truncated collateral amount and full debt when borrower's collateral is fractional - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/68)
* [[H-11] The deposit / withdraw / trade transaction lack of expiration timestamp check and slippage control - ajna.finance - 2023-Feb](https://github.com/sherlock-audit/2023-01-ajna-judging/issues/39)
<p align="center">
                                <a href="https://ag0.gitbook.io/cooler-loans/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/as16x/2023-Midium-Risk-Findings-Sherlock/main/Sherlock/01UO5m5.jpeg?raw=true" width="60" height="60" alt="Javascript" /></a></p>    
                                
---
* [[H-01] Use safeTransfer/safeTransferFrom consistently instead of transfer/transferFrom - Cooler loans - 2023-Feb](https://github.com/sherlock-audit/2023-01-cooler-judging/issues/335)
* [[H-02] Loans can be rolled an unlimited number of times - Cooler loans - 2023-Feb](https://github.com/sherlock-audit/2023-01-cooler-judging/issues/215)
* [[H-03] Fully repaying a loan will result in debt payment being lost - Cooler loans - 2023-Feb](https://github.com/sherlock-audit/2023-01-cooler-judging/issues/33)
* [[H-04] Lender force Loan become default - Cooler loans - 2023-Feb](https://github.com/sherlock-audit/2023-01-cooler-judging/issues/23)

<p align="center">
                                <a href="https://uxd.fi" target="_blank" rel="noreferrer"><img src="https://github.com/as16x/2023-Midium-Risk-Findings-Sherlock/blob/main/Sherlock/UXD%20Protocol.jpg?raw=true" width="60" height="60" alt="Javascript" /></a></p>    
                                
---

* [[H-01] PerpDespository#reblance and rebalanceLite can be called to drain funds from anyone who has approved PerpDepository - uxd.fi - 2023-Jan](https://github.com/sherlock-audit/2023-01-uxd-judging/issues/228)
* [[H-02] Malicious user can use an excessively large _toAddress in OFTCore#sendFrom to break layerZero communication - uxd.fi - 2023-Jan](https://github.com/sherlock-audit/2023-01-uxd-judging/issues/270)
* [[H-03] RageTrade senior vault USDC deposits are subject to utilization caps which can lock deposits for long periods of time leading to UXD instability - uxd.fi - 2023-Jan](https://github.com/sherlock-audit/2023-01-uxd-judging/issues/253)
* [[H-04] PerpDepository has no way to withdraw profits depriving stakers of profits owed - uxd.fi - 2023-Jan](https://github.com/sherlock-audit/2023-01-uxd-judging/issues/251)
* [[H-05] USDC deposited to PerpDepository.sol are irretrievable and effectively causes UDX to become undercollateralized - uxd.fi - 2023-Jan](https://github.com/sherlock-audit/2023-01-uxd-judging/issues/250)
* [[H-06] PerpDepository#getPositionValue uses incorrect value for TWAP interval allowing more than intended funds to be extracted - uxd.fi - 2023-Jan](https://github.com/sherlock-audit/2023-01-uxd-judging/issues/249)
* [[H-07] User specified slippage allows frontrunning - uxd.fi - 2023-Jan](https://github.com/sherlock-audit/2023-01-uxd-judging/issues/192)
---
<p align="center">
                                <a href="https://illuminate-app.vercel.app/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/as16x/2023-Midium-Risk-Findings-Sherlock/main/Sherlock/Illuminate.png" width="60" height="60" alt="Javascript" /></a></p>    
                                
* [[H-01] Illuminate's PT doesn't respect users' slippage specifications for underlyings - illuminate-app - 2023-Jan](https://github.com/sherlock-audit/2023-01-illuminate-judging/issues/16)
* [[H-02] The Notional version of ´lend()´ can be used to lock iPTs - illuminate-app - 2023-Jan](https://github.com/sherlock-audit/2023-01-illuminate-judging/issues/15)
