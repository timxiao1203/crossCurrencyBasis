# Cross Currency Basis Curve

Cross currency swap differs from single currency swaps in that the interest rate payments on the two legs are in different currencies. At inception of the trade, the notional principal amounts in the two currencies are usually set to be fair given the spot exchange rate. Contrary to single currency swap, there is an exchange of principals at inception and maturity, or even in each period of the swap.

Cross currency swaps are powerful instruments to transfer assets or liabilities from one currency to another. The market charges for this is a liquidity premium – the cross-currency basis spread. Thus, the market quoted cross-currency basis spreads usually relative to a liquidity benchmark. 

For a cross currency trade between one currency and another currency. If there is a higher demand for the currency, the party lending the dollar will ask for a premium. This premium is referred to as the cross currency basis. In general, the cross currency basis is a measure of the dollar shortage in the market. The more negative the basis is, the more severe the shortage.

Cross currency basis is an important element of currency management. To price a cross-currency product, the cross-currency basis spread has to be taken into account by adjusting either discounting or forecasting curves. For domestic currency investor, negative basis can work in their favour when they hedge currency exposures. For foreign investors, however, the basis can increase their hedging cost.

A cross currency basis curve is shown below:

CurveName	Instrument	Date	Tenor	Value
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.1W	2020-03-26	1W        	6.30E-05
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.1M	2020-03-26	1M        	-0.00042
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.2M	2020-03-26	2M        	-0.00042
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.3M	2020-03-26	3M        	0.005463
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.6M	2020-03-26	6M        	0.004225
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.9M	2020-03-26	9M        	0.0027
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.1Y	2020-03-26	1Y        	0.00255
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.2Y	2020-03-26	2Y        	0.002275
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.3Y	2020-03-26	3Y        	0.002113
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.4Y	2020-03-26	4Y        	0.00205
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.5Y	2020-03-26	5Y        	0.002025
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.7Y	2020-03-26	7Y        	0.002063
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.10Y	2020-03-26	10Y       	0.002175
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.15Y	2020-03-26	15Y       	0.001987
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.20Y	2020-03-26	20Y       	0.001125
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.25Y	2020-03-26	25Y       	0.0001
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.30Y	2020-03-26	30Y       	-0.00088
XCCY_AUD_USD	XccyBasis.AUD.BBSW3M-USD.LIBOR3M.40Y	2020-03-26	40Y       	-0.00088


References:
https://finpricing.com/lib/EqAsian.html

https://bitbucket.org/cmrm11/xccybasis/downloads/IrXccyBasisCurve-14.pdf
