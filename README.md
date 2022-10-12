# Magma Channel Shop
Sell your first channel on Magma and provide liquidity to an [Amboss Sticker Store](https://btcpay0.voltageapp.io/apps/4Sphr6c21FiYnRmXwqWVdKfAt4PP/pos).

## Log in to [Amboss.Space](https://amboss.space)
Sign the provided message using your node, WebLN, or with an Account Email (requires prior setup).
## Enable Magma Notifications
- Click on Account and go to the [Notifications section](https://amboss.space/owner?page=notifications).
- Connect Telegram (or Email)
- Under Notifications, Enable **Magma Marketplace Events** by selecting Telegram or Email.
## Create an Offer on Magma
1. Navigate to [amboss.space/magma](https://amboss.space/magma) and click “sell channels” to open an offer form. 
2. Complete the form with the following details:
	1. Total Size (sats) ≥ 1,000,000	(Don’t worry if you don’t have that many sats! Only 100k sats are needed for this exercise).
	2. Min Size (sats) = 100,000
	3. Max Size (sats) = You decide!
	4. Variable Fee (ppm) = ______________________________________________
        - This is a fee based on the size of the channel, but this is also the “cost of liquidity”. To see the current market price for liquidity, go to the [LOOP page on Amboss](https://amboss.space/node/021c97a90a411ff2b10dc2a8e32de2f29d2fa49d41bfbb52bd416e460db0747d0d) and find the Incoming Fee Distribution chart. Set a variable fee to match the tallest bar in LOOP’s incoming fee distribution. This is a good market price for liquidity.
        


	5. Fixed Fee (sats) = _________________________________________________
        - This is a fee that can help you recover the cost of opening and closing a channel (two on-chain transactions). To calculate a simple cost for this, let’s assume simple transactions with 1 input and 2 outputs: 141 bytes of data. Check the current mempool fees to find the sats/vbyte.

        - $141$  bytes $×$    2 txns     $× $ ______________           $\frac{sats}{vbyte}$ $=$ ______________


	6. Channel Duration = 1 week
	7. Max Fee Rate (ppm) = You decide!
	8. Max Base Fee (sats) = You decide!
3. Send your **node pubkey** or **amboss link** to [@jestopher on Telegram](https://t.me/jestopher) or <info@amboss.tech>.

## Fulfill the Order Requested!
You should receive a notification that you received an order. If you open the channel as ordered, you’ll receive your first payment from Magma!
